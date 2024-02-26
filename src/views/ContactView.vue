<template>
  <div class="contact-form">
    <h2>Get In Touch!</h2>
    <form action="https://formspree.io/f/xvojerye" method="POST">
        <label for="fullname">Full Name:</label>
        <input type="text" id="fullname" name="fullname" placeholder="Your Full Name" required>
        <label for="email">Email Address:</label>
        <input type="email" id="email" name="email" placeholder="Your Email Address" required>
        <label for="message">Message:</label>
        <textarea id="message" name="message" placeholder="Message Us" required></textarea>
        <div class="send-message">
            <button type="submit">Send</button>
        </div>
    </form>
</div>
</template>

