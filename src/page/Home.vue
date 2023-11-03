<template>
    <div>
        <Navbar />
        <section class="home">
            <div class="image">
                <img src="images/profile.png" alt="">
            </div>
            <div class="content">
                <h3>hi I am {{name}}</h3>
        <span>{{motto}}</span>
        <p>{{content}}</p>
                <router-link to="/about" class="btn"> about me <i class="fas fa-user"></i> </router-link>
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
            name: 'Arshavin Jaruchun'
            motto: 'Impossible is nothing'
            content: 'Im Arshavin Jaruchun Nickname is Arsher My fav colour is red My hobby is playfootball some time i like to go to cafe im a lil brother in my family now im study at Bangkok University.'
        }
    }
}
</script>

<style>

</style>