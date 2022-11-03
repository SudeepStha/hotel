<template>
    <nav class="navbar navbar-expand-lg bg-light">
  <div class="container">
    <h1><a class="navbar-brand" href="#">HOTEL SANDHYA INN</a></h1>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
      <div class="navbar-nav ms-auto">
        <a class="nav-link" href="#" @click="$router.push({name:'contact'})" v-for="menu in menus" :key=menu.id>{{menu.name}}</a>
      </div>
    </div>
  </div>
</nav>
</template>


<script>
import axios from "axios"
export default {
    name: 'NavbarComponent',
    data(){
      return {
        menus : []
      }
    },

    mounted() {
     this.getMenus()
    },

    methods:{
      async getMenus(){
        try {
          let response = await axios.get("http://localhost:3000/menus")
          if(response.status == 200){
            console.warn(response.data);
            this.menus = response.data
          }
        } catch(e){
          console.warn(e.toString());
        }
      }
      
    }
}
</script>

<style>

</style>