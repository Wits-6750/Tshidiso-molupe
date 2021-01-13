<template>
    <div id="app">
        <section class="hero">
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
        <section class="section p-0">
            <div class="container is-fluid section-2-background p-5">
                <div class="columns is-justify-content-center">
                    <div class="column">
                        <h1 class="title has-text-white has-text-centered section-2-header"> What can I do<br> for you</h1>
                        <h2 class="has-text-white has-text-centered">
                            Build and design beautiful website to turn<br>
                            visitors into paying customer
                        </h2>
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
    --tertiary-font:  "Playfair Display", serif;
    --tertiary-font: "Playfair Display", serif;
}

#app {
    font-family: var(--secondary-font);
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

.section-2-background {
    background: var(--secondary-color);
}
.section-2-header{
    font-family: var(--tertiary-font);
    font-style: normal;
    line-height: 120% !important;
}
body {
    margin: 0px;
    background: rgba(252, 163, 17, 0.19) !important;
}


</style>
