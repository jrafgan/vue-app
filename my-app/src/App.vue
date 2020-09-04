<template>
    <div id="app">
        <NavBar msg="Welcome to Your Vue.js App"/>
        <Body />
    </div>
</template>

<script>
    import './AppCustom.css'
    import NavBar from './components/NavBar.vue'
    import Body from './components/Body'

    export default {
        name: 'App',
        components: {
            NavBar,
            Body
        }
    }
</script>
