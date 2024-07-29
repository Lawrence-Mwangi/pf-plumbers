<script setup>
import Navbar from '@/components/navbarComponent.vue'
import Hero from '@/views/HeroView.vue'
import About from '@/views/AboutView.vue'
import Work from '@/views/WorkView.vue'
import Contact from '@/views/ContactView.vue'
import Footer from '@/components/footerComponent.vue'
</script>

<template>
    <Navbar/>

    <div class="hero_infor" id="Hero">
        <Hero/>
    </div>

    <div class="main_container" id="About">
        <About/>
    </div>

    <div class="main_container" id="work">
        <Work/>
    </div>

    <div class="main_container" id="Contact">
        <Contact/>
    </div>


    <Footer/>
    
</template>
