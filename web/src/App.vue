<template>
    <div id="app">
        <section class="hero hero-entities">
            <!-- Hero head: will stick at the top -->
            <div class="hero-head">
                <nav class="navbar">
                    <div class="container">
                        <div class="navbar-brand">
                            <a class="navbar-item is-hidden-desktop" style="display: inline-grid; margin-left: auto;">
                                <span class="logo-text">Tshidiso</span>
                                <span class="logo-text" style="padding-left:31px; margin-top: -18px;">Molupe</span>
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
                                    <span class="logo-text" style="padding-left:31px; margin-top: -18px;">Molupe</span>
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
                <div class="container">
                    <div class="columns">
                        <div class="column">
                            <h1 class="header-title is-size-1-desktop is-size-2-mobile is-size-1-tablet">Hello There.<br>My name is <span style="font-weight:bold">Tshidiso</span></h1>
                            <h2 class="header-subtitle is-size-5-desktop is-size-5-mobile is-size-5-tablet">Let me  help you build a website<br>that add value to your business</h2>
                            <a class="button btn-hero">Hire Me</a>
                        </div>
                        <div class="column">
                            <figure class="image">
                                <img class="hero-image" src="@/assets/img/image_hero.svg">
                            </figure>
                        </div>
                    </div>
                </div>
            </div>
        </section>
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

:root {
    --primary-color: #fca311;
    --secondary-color: #14213d;
    --primary-font: "Dancing Script", cursive;
    --secondary-font: "Lato", sans-serif;
    --tertiary-font: "Playfair Display", serif;
}

#app {
    font-family: var(--secondary-font);
    height: 100vh;
}

.hero {
    height: 100vh;
}

.header-title {
    font-style: normal;
    font-weight: 300;
    line-height: 120%;
    text-align: left;
    position: absolute;
    top: 80px;
    left: 10px;
    color: #000000;
}

.header-subtitle {
    font-style: normal;
    font-weight: 300;
    font-size: 20px;
    line-height: 120%;
    text-align: left;
    position: absolute;
    top: 240px;
    left: 10px;
    color: #000000;
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
    position: absolute;
    top: 320px;
    left: 10px;
    font-style: normal;
    font-weight: 300;
    line-height: 120%;
    border-color: #00AC90 !important;
}

@media screen and (max-width: 769px){
.hero-image {
    height: auto;
    width: 100%;
    position: absolute;
    top: 338px;
   }
}


body {
    margin: 0px;
    height: 100vh;
    background: rgba(252, 163, 17, 0.19);
}

@media screen and (max-width: 769px){
body {
    height: 115vh !important;
   }
}
</style>
