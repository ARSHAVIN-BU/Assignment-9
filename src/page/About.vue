<template>
    <div>
        <Navbar />

        <section class="about">

            <h1 class="heading"> about <span>me</span> </h1>

            <div class="row">

                <div class="info-container">

                    <h1>personal info</h1>

                    <div class="box-container">

                        <div class="box">
                            <h3> <span>name : </span> {{Name}} </h3>
                            <h3> <span>age : </span> {{age}} </h3>
                            <h3> <span>email : </span> {{email}} </h3>
                            <h3> <span>address : </span> {{address}} </h3>
                        </div>
    
                        <div class="box">
                            <h3> <span>freelance : </span> available </h3>
                            <h3> <span>skill : </span> Adobe PS,AI,AE,PR </h3>
                            <h3> <span>fav colour : </span> Red </h3>
                            <h3> <span>language : </span> Thai </h3>
                        </div>

                    </div>

                    
                <a href="https://www.facebook.com/arshavin.jaruchun/" class="btn"> Facebook <i class="fas fa-download"></i> </a>

            </div>

            <div class="count-container">

                <div class="box">
                    <h3>RED</h3>
                    <p>My favorite colour</p>
                </div>

                <div class="box">
                    <h3>Football</h3>
                    <p>My Hobby</p>
                </div>

                <div class="box">
                    <h3>Male</h3>
                    <p>Gender</p>
                </div>

                <div class="box">
                    <h3>Bangkok University</h3>
                    <p>Study</p>
                </div>

            </div>

        </div>

    </section>

        <!-- about section ends -->

        <!-- skills section starts  -->

    <!-- about section ends -->

    <!-- skills section starts  -->

    <section class="skills">

        <h1 class="heading"> <span>my</span> skills </h1>

        <div class="box-container">
            <div class="box">
                <img src="images/icon-1.png">
                <h3>Football</h3>
            </div>
            <div class="box">
                <img src="images/icon-2.png">
                <h3>Basketball</h3>
            </div>
            <div class="box">
                <img src="images/icon-3.png">
                <h3>Baseball</h3>
            </div>
            <div class="box">
                <img src="images/icon-4.png">
                <h3>Taekwondo</h3>
            </div>
            <div class="box">
                <img src="images/icon-5.png">
                <h3>Guitar</h3>
            </div>
            <div class="box">
                <img src="images/icon-6.png">
                <h3>Play Game</h3>
            </div>
        </div>

    </section>

        <!-- skills section ends -->

        <!-- education section starts  -->

        <section class="education">

            <h1 class="heading"> <span>my</span> experience </h1>

        <div class="box-container">

            <div class="box">
                <i class="fas fa-briefcase"></i>
                <span>High school</span>
                <h3>Suankularb Wittayalai Rangsit</h3>
                <p>I started studying at Suankularb Wittayalai Rangsit School. From grade level Mathayom 1 to Mathayom 6.</p>
            </div>

            <div class="box">
                <i class="fas fa-briefcase"></i>
                <span>AFS Study</span>
                <h3>Study in Canada</h3>
                <p>I am an exchange student of the AFFS program where I study at Charles P. Allen High School.</p>
            </div>

            <div class="box">
                <i class="fas fa-briefcase"></i>
                <span>My University</span>
                <h3>Bangkok University</h3>
                <p>Currently, I am a student at Bangkok University
                </p>
            </div>

        </div>

        </section>
    </div>
</template>

<script>
import Navbar from "../components/Navbar.vue";
export default {
    components: { Navbar },
    data() {
        return {
            Name: 'Arshavin Jaruchun'
            age: '23'
           email: 'arm_pjt@hotmail.com'
            address: 'Phathumtani, Thailand 12120'  
        }
    }

}
</script>

<style>

</style>