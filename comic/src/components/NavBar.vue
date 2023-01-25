<template>
    <div id="NavBox">
<div class="container">
    <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </nav></div>
    </div>
</template>

<script>
    export default {
        name:'NavBar',
        methods: {
        someMethod(event) {
            // clientX/Y gives the coordinates relative to the viewport in CSS pixels.
            console.log(event.clientX);
            console.log(event.clientY);

            // pageX/Y gives the coordinates relative to the <html> element in CSS pixels.
            console.log(event.pageX);
            console.log(event.pageY);

            // screenX/Y gives the coordinates relative to the screen in device pixels.
            console.log(event.screenX);
            console.log(event.screenY);
        }
    }
    }
</script>

<style lang="scss" scoped>
#NavBox{
    background-color: aquamarine;
    margin: 0 auto;


    display:flex;
    width:100%;
}

</style>