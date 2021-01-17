<template>
    <div id="app">
        <section class="hero" style="max-height: 760px;">
            <!-- Hero head: will stick at the top -->
            <div class="hero-head">
                <nav class="navbar">
                    <div class="container">
                        <div class="navbar-brand">
                            <a class="navbar-item is-hidden-desktop" style="display: inline-grid; margin-left: auto;">
                                <span class="logo-text">Tshidiso</span>
                                <span class="logo-text" style="padding-left:31px">Molupe</span>
                            </a>
                            <span 
                                class="navbar-burger"
                                :class="{'is-active':is_menu_active}"
                                @click="is_menu_active=!is_menu_active"
                                data-target="navbarMenuHeroA">
                                <span></span>
                                <span></span>
                                <span></span>
                            </span>
                        </div>
                        <div id="navbarMenuHeroA" class="navbar-menu" :class="{'is-active':is_menu_active}">
                            <div class="navbar-start">
                                <a class="navbar-item is-active">Work</a>
                                <a class="navbar-item">Contact</a>
                            </div>
                            <div class="navbar-item">
                                <a class="navbar-item is-hidden-touch" style="display: inline-grid; margin-left: auto;">
                                    <span class="logo-text">Tshidiso</span>
                                    <span class="logo-text" style="padding-left:31px">Molupe</span>
                                </a>
                            </div>
                            <div class="navbar-end">
                                <div class="navbar-item">
                                    <div class="field is-grouped">
                                        <p class="control">
                                            <a 
                                                href="https://dribbble.com/SydChill"
                                                target="_"
                                                 style="color:#000">
                                                <i class="fa fa-dribbble"></i>
                                            </a>
                                        </p>
                                        <p class="control">
                                            <a
                                            href="https://www.linkedin.com/in/tshidiso-molupe-68752899/"
                                            target="_"
                                            style="color:#000">
                                            <i class="fa fa-linkedin-square"></i>
                                            </a>
                                        </p>
                                        <p class="control">
                                            <a 
                                                href="https://www.instagram.com/tshidiso_designs/"
                                                target="_"
                                                class="contron"
                                                style="color:#000">
                                                <i class="fa fa-instagram"></i>
                                            </a>
                                        </p>
                                        <p class="control">
                                            <a
                                            href="mailto:stmolupe@gmail.com"
                                            target="_"
                                            style="color:#000" >
                                            <i class="fa fa-envelope-o"></i>
                                            </a>
                                        </p>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </nav>
            </div>

            <!-- Hero content: will be in the middle -->
            <div class="hero-body">
                <div class="container ">
                    <div class="columns">
                        <div class="column pl-6">
                            <h1 class="header-title title has-text-center-mobile is-size-1-desktop is-size-2-mobile is-size-2-tablet">Hello There.<br>My name is <span style="font-weight:bold">Tshidiso</span></h1>
                            <h2 class=" header-subtitle subtitle is-size-5-desktop is-size-6-mobile is-size-6-tablet pt-5">Let me  help you build a website<br>that add value to your business</h2>
                            <a class="button btn-hero">Hire Me</a>
                        </div>
                        <div class="column pr-6">
                            <figure class="image">
                                <img class="hero-image" src="@/assets/img/image_hero.svg">
                            </figure>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <!-- Section 2 -->
        <section class="section p-0 mt-6">
            <div class="container is-fluid section-2-background p-5">
                <div class="columns is-justify-content-center">
                    <div class="column">
                        <h1 class="title is-size-1 has-text-white has-text-centered section-2-header"> What can I do<br> for you</h1>
                        <h2 class="has-text-white has-text-centered">
                            Build and design beautiful website to turn<br>
                            visitors into paying customer
                        </h2>
                    </div>
                </div>
            </div>
        </section>
        <section class="section">
            <h1 class="title is-size-2 pb-4 is-size-4-mobile has-text-centered section-header">Latest Work</h1>
            <div class="columns">
                <div class="column is-4">
                    <div class="card" style="backgroun:#007C8E !important">
                        <div class="card-image">
                            <figure class="image is-4by3">
                                <img src="@/assets/img/work_1.png" alt="Placeholder image">
                            </figure>
                        </div>
                        <div class="card-content">
                            <div class="media"> 
                                <div class="media-content">
                                    <p class="title is-4">Legal firm website redesign</p>
                                    <a class="button is-small">View website</a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="column is-4">
                    <div class="card">
                        <div class="card-image">
                            <figure class="image is-4by3">
                                <img src="@/assets/img/work_2.png" alt="Placeholder image">
                            </figure>
                        </div>
                        <div class="card-content">
                            <div class="media"> 
                                <div class="media-content">
                                    <p class="title is-4">Legal firm website redesign</p>
                                    <p class="subtitle is-6 mt-4">Under construction</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="column is-4">
                    <div class="card">
                        <div class="card-image">
                            <figure class="image is-4by3">
                                <img src="@/assets/img/work_3.png" alt="Placeholder image">
                            </figure>
                        </div>
                        <div class="card-content">
                            <div class="media"> 
                                <div class="media-content">
                                    <p class="title is-4">Direct messaging application build with Vue.js and flask</p>
                                    <a class="button is-small">View website</a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section class="section">
            <div class="container is-fluid">
                <h1 class="title is-size-2 pb-4 is-size-4-mobile has-text-centered section-header">Approach</h1>
                <h3 class="subtitle is-size-6 section-subheader">In order to create the best website possible there is four main steps <br>taken before the final product is released</h3>
                <div class="columns is-flex-direction-column is-justify-content-center">
                    <div class="column ">
                        <div class="approach-box is-align-content-center bkg-img-1">
                            <h1 class="title is-size-3 pb-4 is-size-4-mobile has-text-left pl-5 pt-2">Interview</h1>
                            <h2 class="subtitle is-size-4 pb-4 is-size-6-mobile has-text-left pl-5 pt-4 has-text-white">Interview with the client to discuss business needs to get an idea of their requirements and get an understanding of their band goals.</h2>
                        </div>
                    </div>
                    <div class="column">
                        <div class="approach-box is-align-content-center bkg-img-2">
                            <h1 class="title is-size-3 pb-4 is-size-4-mobile has-text-left pl-5 pt-2">Design</h1>
                            <h2 class="subtitle is-size-4 pb-4 is-size-6-mobile has-text-left pl-5 pt-4 has-text-white">Design website using figma with the client involved throughout the whole process.</h2>
                        </div>
                    </div>
                    <div class="column">
                        <div class="approach-box is-align-content-center bkg-img-3">
                            <h1 class="title is-size-3 pb-4 is-size-4-mobile has-text-left pl-5 pt-2">Build Website</h1>
                            <h2 class="subtitle is-size-4 pb-4 is-size-6-mobile has-text-left pl-5 pt-4 has-text-white">Once the client is happy with the design, next step is to build the websites using htlm, css and javascript.</h2>
                        </div>
                    </div>
                    <div class="column">
                        <div class="approach-box is-align-content-center bkg-img-4">
                            <h1 class="title is-size-3 pb-4 is-size-4-mobile has-text-left pl-5 pt-2">Launch</h1>
                            <h2 class="subtitle is-size-4 pb-4 is-size-6-mobile has-text-left pl-5 pt-4 has-text-white">hooray!!! help client setup domain name if they don’t already have one and launch the website with Netlify. Also teach client how to do updates like changing photos and text</h2>
                        </div>
                    </div>

                </div>
            </div>
        </section>
        <section class="section p-0  m-6">
            <div class="container">
                <h1 class="title is-size-2  is-size-4-mobile has-text-centered section-header">About Me</h1>
                <div class="columns">
                    <div class="column is-7">
                        <h1 class="title is-size-3 m-5 is-size-4-mobile has-text-left pt-6 section-header has-text-weight-bold">
                            I’m Tshidiso, a software <br>
                            developer and designer<br> working as a UX/UI designer<br>
                            based in Johannesburg, South Africa
                        </h1>

                        <p class="m-5">
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur blandit cursus ex, eu sodales enim ultricies ut. In suscipit imperdiet viverra
                        </p>

                        <p class="m-5">
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur blandit cursus ex, eu sodales enim ultricies ut. In suscipit imperdiet viverra
                        </p>

                        <p class="m-5">
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur blandit cursus ex, eu sodales enim ultricies ut. In suscipit imperdiet viverra
                        </p>
                    </div>
                    <div class="column is-5 mt-4">
                        <figure class="image is-3by4 ">
                            <img class="my-image" src="@/assets/img/me.jpg" alt="Placeholder image">
                        </figure>
                    </div>
                </div>
            </div>
        </section>
        <footer class="footer section-2-background p-6">
            <div class="content has-text-centered">
                <h1 class="is-size-2 has-text-white has-text-weight-medium	">Hire Me</h1>
                <p class="has-text-white has-text-weight-light">Interested in building  a new website for your buisiness or<br> you just want to chat about I can be of service to<br> you, don’t be afraid to send a message.</p>

                <h1 class="is-size-4 has-text-white has-text-weight-medium">+27 73 232 4298</h1>           
                <h1 class="is-size-5 has-text-white has-text-weight-medium">
                    <a  href="mailto:stmolupe@gmail.com" class="has-text-white">hello@tshidiso-molupe.com</a>
                </h1>   
                <h1 class="is-size-5 mt-6 has-text-white has-text-weight-medium">Socials</h1>
                <div class="field " style="display:inline-flex">
                    <p class="control">
                        <a 
                            href="https://dribbble.com/SydChill"
                            target="_"
                                style="color:#fff">
                            <i class="fa fa-dribbble"></i>
                        </a>
                    </p>
                    <p class="control">
                        <a
                        href="https://www.linkedin.com/in/tshidiso-molupe-68752899/"
                        target="_"
                        style="color:#fff">
                        <i class="fa fa-linkedin-square"></i>
                        </a>
                    </p>
                    <p class="control">
                        <a 
                            href="https://www.instagram.com/tshidiso_designs/"
                            target="_"
                            class="contron"
                            style="color:#fff">
                            <i class="fa fa-instagram"></i>
                        </a>
                    </p>
                    <p class="control">
                        <a
                        href="mailto:stmolupe@gmail.com"
                        target="_"
                        style="color:#fff" >
                        <i class="fa fa-envelope-o"></i>
                        </a>
                    </p>
                </div>     
            </div>
        </footer>
    </div>
</template>

<script>
export default {
  name: "App",
  data (){
      return {
          is_menu_active: false
      }
  }
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Dancing+Script&family=Lato:wght@300;400;900&family=Playfair+Display:wght@700&display=swap");
@import url('https://fonts.googleapis.com/css2?family=Playfair+Display&display=swap');
:root {
    --primary-color: #fca311;
    --secondary-color: #14213d;
    --primary-font: "Dancing Script", cursive;
    --secondary-font: "Lato", sans-serif;
    --tertiary-font:  "Playfair Display", serif;
}

#app {
    font-family: var(--secondary-font);
}

.section-header {
    font-family: var(--tertiary-font);
    font-style: normal !important;
    font-weight: normal !important;
    line-height: 120% !important;
    color: var(--secondary-color) !important;
    text-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
    
}

.section-subheader {
    font-style: normal !important;
    font-weight: normal !important;
    line-height: 120% !important;
    text-align: center;
    color: #505561;
    text-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
    
}
.hero-body {
    padding: 5rem 5rem !important;
}
.header-title {
    font-style: normal;
    font-weight: 300 !important;
    align-items: center !important;
    color: #000000 !important;
}

.header-subtitle {
    font-style: normal;
    font-weight: 300 !important;
    line-height: 120%;
    color: #000000 !important;
}

.navbar-item {
    font-style: normal;
    font-weight: 500;
    font-size: 20px;
    line-height: 120%;
}

.control{
    font-size:25px !important;
    margin: 0px 10px;
}
.logo-text {
    font-family: var(--primary-font);
    font-size: 26px;
}
.btn-hero {
    background: #00AC90 !important;
    box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25) !important;
    border-radius: 5px !important;
    color: #ffff !important;
    width: 198px;
    font-style: normal;
    font-weight: 300;
    line-height: 120%;
    border-color: #00AC90 !important;
}

.about-me {
    font-family: var(--secondary-font);
    font-style: normal;
    line-height: 120% !important;
}
.section-2-background {
    background: var(--secondary-color) !important;
}
.section-2-header{
    font-family: var(--tertiary-font);
    font-style: normal;
    line-height: 120% !important;
}
.latest-work-img {
    filter: drop-shadow(0px 4px 4px rgba(0, 0, 0, 0.25));
    border-radius: 20px 0px 0px 20px ;
}

.approach-box {
    width: 50%;
    margin: 3rem auto;
    padding: 10px
}

@media only screen and (max-width: 760px) {
 .approach-box {
        width: 100%;

  }
}

.bkg-img-1 {
    background: url("./assets/img/approach_1.jpg");
    filter: drop-shadow(0px 4px 4px rgba(0, 0, 0, 0.25));
    border-radius: 35px;
    background-repeat: no-repeat;
    background-size: cover;
}

.bkg-img-2 {
    background: url("./assets/img/approach_2.jpg");
    filter: drop-shadow(0px 4px 4px rgba(0, 0, 0, 0.25));
    border-radius: 35px;
    background-repeat: no-repeat;
    background-size: cover;
}
.bkg-img-3 {
    background: url("./assets/img/approach_3.jpg");
    filter: drop-shadow(0px 4px 4px rgba(0, 0, 0, 0.25));
    border-radius: 35px;
    background-repeat: no-repeat;
    background-size: cover;
}

.bkg-img-4 {
    background: url("./assets/img/approach_4.jpg");
    filter: drop-shadow(0px 4px 4px rgba(0, 0, 0, 0.25));
    border-radius: 35px;
    background-repeat: no-repeat;
    background-size: cover;
}
.approach-box h1, h2{
    color: #fff;
}
.my-image{
    box-shadow: 4px 17px 28px 10px rgba(0, 0, 0, 0.36);
    border-radius: 63px !important;
}
a:hover {
  text-decoration: underline;
}

body {
    margin: 0px;
    background: rgba(252, 163, 17, 0.19) !important;
}


</style>
