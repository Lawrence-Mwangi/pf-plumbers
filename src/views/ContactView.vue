<script setup></script>

<template>
    <div class="contact_container">
        <h1>Contact Us</h1>
        
        <div class="contact_content">
            <div class="contact_infor">
            <p>pfplumbers@gmail.com</p>
            <p><a href="tel:+254769696309">+254 769 696 309</a></p>
        </div>

        <form action="#" method="post">
            <div class="input_group">
                <label for="client_names">Client Names</label>
                <input type="text" name="client_names" id="client_names" placeholder="Enter your names">
            </div>

            <div class="input_group">
                <label for="email">Email </label>
                <input type="email" name="email" id="email" placeholder="Enter your email">
            </div>

            <div class="input_group">
                <label for="message">Message</label>
                <textarea name="message" id="message" cols="10" rows="7" placeholder="Type you message here"></textarea>
            </div>

            <div class="btn">
                <button type="submit">Send Message</button>
            </div>
        </form>
        </div>
    </div>
</template>