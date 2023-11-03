<template>
    <div>
        <Navbar />
        <section class="projects">
            <h1 class="heading"> <span>my</span> projects </h1>
        <h3>{{project_name}}</h3>
        <p> {{project_detail}} </p>
            <div class="box-container">
                <iframe width="720" height="405" src="https://www.youtube.com/embed/mY9qyx8iNro?si=tIFJu6WZi-pp4tS0"
                title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; 
            gyroscope; picture-in-picture" allowfullscreen></iframe>
            </div>
        </section>
    </div>
</template>

<script>
import Navbar from '../components/Navbar.vue';
export default {
    components: { Navbar },
    data() {
        return {
           project_name: 'This is my Takwondo Fight RSU OPEN'
           project_detail: 'คลิปวิดีโอการแข่งขัน เทควันโดของผม'
        }
    }
}
</script>

<style>

</style>