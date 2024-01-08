<template>
    <div class="wrapper">
        <div class="main-container">
            <div class="container-one">
                <div class="profile">
                    <img src="../assets/profilepic.png" alt="">
                    <h3>Johnbosco</h3>
                    <p>Software Developer</p>
                </div>
                <div class="social-links">
                        <div class="link">
                            <a href="">
                                <img src="../assets/github.png" alt="">
                                <h2>Github</h2>
                            </a>
                        </div>
                        <div class="link">
                            <a href="">
                                <img src="../assets/linkedin.png" alt="">
                                <h2>LinkedIn</h2>
                            </a>
                        </div>
                        <div class="link">
                            <a href="">
                                <img src="../assets/twitter.png" alt="">
                                <h2>Twitter</h2>
                            </a>
                        </div>
                        <div class="link">
                            <a href="">
                                <img src="../assets/instagram.png" alt="">
                                <h2>Instagram</h2>
                            </a>
                        </div>
                </div>
            </div>

            <div class="container-two">
                <div class="about-me">
                    <h2>Greetings!</h2>
                    <p> I am Johnbosco Chukwudubem, a passionate programmer hailing from the vibrant town of Nimo in Anambra State, Nigeria. I am a dedicated professional with a profound interest in the world of programming.
                        My journey into the realm of programming reflects not only a career choice but a profound enthusiasm for problem-solving and innovation. I find joy in exploring the intricacies of code, continually expanding my knowledge, and honing my skills to contribute meaningfully to the tech landscape.
                        I believe in the power of collaboration and enjoy working with like-minded individuals to address real-world challenges using my programming expertise.
                        In my pursuit of excellence, I am constantly seeking opportunities to learn something new, staying at the forefront of technological advancements. My ultimate goal is to leverage my skills to provide effective and efficient solutions to the complex problems that shape our world.
                        Thank you for taking a moment to learn more about me. I am excited about the possibilities that lie ahead and eager to contribute my skills to meaningful projects.
                    </p>
                </div>
                <div class="technology-section">
                    <h2>Technologies Studied</h2>
                    <h3>Frontend</h3>
                    <div class="logos">
                        <img src="../assets/html.png" alt="">
                        <img src="../assets/css.png" alt="">
                        <img src="../assets/javascript.png" alt="">
                    </div>
                    <h3>Backend</h3>
                    <div class="logos">
                        <img src="../assets/php.png" alt="">
                    </div>
                    <h3>Frameworks</h3>
                    <div class="logos">
                        <img src="../assets/laravel.png" alt="">
                        <img src="../assets/vue.png" alt="">
                    </div>
                    <h3>Added to my Technologies </h3>
                    <div class="logos">
                        <img src="../assets/vuex.png" alt="">
                        <img src="../assets/json.png" alt="">
                        <img src="../assets/firestore.png" alt="">
                    </div>
                </div>
                <div class="button-container">
                    <div class="projects-btn">
                        <a href="">My Projects</a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'MainCard'
    }
</script>

<style scoped>
    .wrapper {
        display: flex;
        justify-content: center;

    } 

    img{
        height: 20px;
    } 

    .main-container{
        display: flex;
        flex-direction: row;
        /* background-color: #cecece; */
        border-radius: 25px;
        width: 60%; 
        background-color: #ecf3f8;
        box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px;

    } 

    .container-one{
        background-color: #ffffff;
        width: 30%;
        padding: 2.5%;
        border-radius: 25px;
        box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px;
    }
    
    .container-one:hover{
        box-shadow: rgba(0, 0, 0, 0.24) 2px 5px 12px;
    } 

    .profile img{
        height: 5rem;
        border-radius: 50%;
    } 

    .link a{
        text-decoration: none;
        color: #2c3e50;
        font-size: 10px;
    } 

    .link img{
        height: 2rem;
    } 

    .container-two{
        /* background-color: #cdc0fc; */
        margin: 2.5%;
        width: 70%;
    } 

    .about-me{
        text-align: left;
    } 

    .logos img{
        height: 2.5rem;
        margin: 20px;
    } 

    .button-container{
        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;
        margin-top: 5%;
    } 

    .projects-btn{
        background-color: #0da000;
        padding: 15px;
        border-radius: 10px;
        margin: 5px;
    } 

    .projects-btn a{
        text-decoration: none;
        color: #fff;

    } 

   @media only screen and (max-width: 950px) {
        .main-container {
            width: 100%;
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            align-items: center;
        } 
        .container-one {
            width: 100%;
        } 
        .about-me h2, p{
            text-align: center;
        } 
   } 
</style> 