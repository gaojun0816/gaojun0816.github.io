---
layout: page
title: Email Me
sidebar_link: true
---

<div class="email">
    <p>
        Please leave your message below and I will reply you as soon as possible.
    </p>
    <form action="https://formspree.io/f/xvovqkgz" method="POST">
        <p>
            Your Name:
            <br>
        <label>
            <input type="text" value size="40" name="_name" required>
        </label>
        </p>
        <p>
            Your Email:
            <br>
        <label>
            <input type="email" value size="40" name="_replyto" aria-invalid="true" required>
        </label>
        </p>
        <p>
            Subject:
            <br>
        <label>
            <input type="text" value size="40" name="_subject" required>
        </label>
        </p>
        <p>
            Your Message:
            <br>
        <label>
            <textarea name="message" cols="70" rows="15" required></textarea>
        </label>
        </p>
        <p>
            <div class="g-recaptcha" data-sitekey="6LfMOOIZAAAAADZLPk0LDJvUi5ckE1iMSRrgqhdc"></div>
        </p>
        <p>
            <input type="submit" value="Send">
        </p>
    </form>
</div>
