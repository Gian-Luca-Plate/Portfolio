<template>
    <div id="About-page">
        <h1 class="überschrift">About Me</h1>
        <Navbar />
        <div style="display: flex; justify-content: center;">
            <AboutText />
        </div>


    </div>
</template>
  
<script>
import Navbar from './Navbar.vue';
import AboutText from './About-text.vue';

export default {
    name: "About-Page",
    components: {
        Navbar,
        AboutText
    }
}
</script>
  
<style>
@import url('https://fonts.googleapis.com/css2?family=Comfortaa:wght@300..700&family=Playpen+Sans&display=swap');


.überschrift {
    font-weight: bold;
    font-family: "Comfortaa", sans-serif;
    display: flex;
    justify-content: center;
    margin-top: 130px;
    margin-bottom: 60px;
    font-size: 50px;
}
</style>