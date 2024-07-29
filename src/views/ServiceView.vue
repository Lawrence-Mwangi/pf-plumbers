<script setup>
import Navbar from '@/components/navbarComponent.vue'
import Footer from '@/components/footerComponent.vue'
</script>

<template>
    <Navbar/>

    <div class="main_container">
        <h1>Service Page</h1>

        <div class="service_container">
            <p>PF plumbers offer the following services to they client and many more</p>

            <div class="service_content">
                <div class="service_items">
                    <h3>Leak Detection & Repair</h3>
                    <p>Advanced techniques to identify, detect and fix leaks, 
                        saving on water bills, wastage and save money.
                    </p>

                    <div class="btn">
                        <button>
                            <a href="tel:+254769696309">Inquire</a>
                        </button>
                    </div>
                </div>

                <div class="service_items">
                    <h3>Drain Cleaning</h3>
                    <p>Comprehensive drain cleaning services to eliminate 
                        clogs and ensure smooth drainage for your system.
                    </p>

                    <div class="btn">
                        <button>
                            <a href="tel:+254769696309">Inquire</a>
                        </button>
                    </div>
                </div>

                <div class="service_items">
                    <h3>Pipe Replacement & Repair</h3>
                    <p>Durable solutions for damaged or outdated pipes, ensuring long-lasting performance.</p>

                    <div class="btn">
                        <button>
                            <a href="tel:+254769696309">Inquire</a>
                        </button>
                    </div>
                </div>

                <div class="service_items">
                    <h3>Water Heater Services</h3>
                    <p> Installation, maintenance, and repair of water heaters to ensure 
                        consistent hot water supply for you house.
                    </p>

                    <div class="btn">
                        <button>
                            <a href="tel:+254769696309">Inquire</a>
                        </button>
                    </div>
                </div>

                <div class="service_items">
                    <h3>Fixture Installation & Repair</h3>
                    <p>Expert installation and repair of faucets, sinks, toilets, showers, and more.</p>

                    <div class="btn">
                        <button>
                            <a href="tel:+254769696309">Inquire</a>
                        </button>
                    </div>
                </div>

                <div class="service_items">
                    <h3>Bathroom & Kitchen Remodeling</h3>
                    <p>Remodeling services to upgrade and modernize
                        your plumbing fixtures and systems.
                    </p>

                    <div class="btn">
                        <button>
                            <a href="tel:+254769696309">Inquire</a>
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <Footer/>
</template>