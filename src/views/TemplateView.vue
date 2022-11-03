<template>
    <div>
        <header>
            <topbar-component />
            <navbar-component />
        </header>

        <main>
            <slot></slot>
        </main>

        <footer>

        </footer>
    </div>
</template>

<script>
import TopbarComponent from '../components/TopbarComponent.vue'
import NavbarComponent from '../components/NavbarComponent.vue'

export default {
    name: 'TemplateView',
    components:{
        TopbarComponent,
        NavbarComponent
    }
}
</script>

<style>

</style>