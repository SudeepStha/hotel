<template>
    <div class="bg-blue">
        <div class="container">
            <div class="flex topbar"> 
                <div>{{company.address}}</div>
                <div>
                    <div>Facebook, Youtube</div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
import axios from 'axios'
export default {
    name: 'TopbarComponent',
    data(){
        return{
            company:{}
        }
    },

    mounted(){
        this.getCompanyinfo()
    },

    methods: {
        async getCompanyinfo(){
            try {
                let response = await axios.get("http://localhost:3000/company")
                if(response.status == 200){
                    console.warn(response.data)
                    this.company = response.data
                }
            } catch (e) {
                console.warn(e.toString());
            }
        }
    }
}
</script>

<style>

</style>