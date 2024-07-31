<script setup></script>

<template>
    <div class="hero_container">
        <div class="hero_content">
            <video loop muted autoplay>
                <source src="../assets/videos/hero.mp4" type="video/mp4" >
            </video>
            
            <div class="hero_details">
                <h1>Hi! we are <span>PF Plumbers</span></h1>
                <p>Where Dripes stops & satsifaction starts</p>

                <div class="btn">
                    <button>
                        <RouterLink :to="{ name: 'service'}">Our Service</RouterLink>
                    </button>

                    <button>
                        <a href="tel:+254769696309">Contact US</a>
                    </button>
                </div>
            </div>
        </div>
    </div>
</template>