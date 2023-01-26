<template>
    <div id="NavBox">
<div class="container">
RESPONSIVE COMIC-TEMPLATE 
<br />
 <img class="logos" src="@/assets/pics/star_logo.png"/>
    <nav>
        <router-link to="/test">test</router-link> |
        <router-link to="/">E02</router-link> |
        <router-link to="/">E03</router-link> |
    <router-link to="/">E01</router-link> |
    <router-link to="/about">About</router-link>
  </nav></div>

    </div>
</template>

<script>
    export default {
        name:'NavBar',
        methods: {
    
    }
    }
</script>

<style lang="scss" scoped>

</style>