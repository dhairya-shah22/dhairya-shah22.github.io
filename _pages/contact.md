---
layout: page
title: Contact
permalink: /contact/
---

<div class="contact-page">

  <h2>Get in Touch</h2>
  <p>If you’d like to collaborate, ask a question, or just say hello, you can reach me via any of the methods below—or send a quick message using the form.</p>

  <!-- Contact Links -->
  <ul>
    <li><strong>Email:</strong> <a href="mailto:contact@drshah.me">contact@drshah.me</a></li>
    <li><strong>Signal:</strong> <a href="https://signal.me/#eu/irdorGIukyc7Gz8n648RzyfslZuwUsgwuKfmu8ChpQ9fVgVhG6BDAK2xoQoQKXZ5">Chat on Signal</a></li>
    <li><strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/dshah08">linkedin.com/in/dshah08</a></li>
  </ul>

  <!-- Accessible Contact Form -->
  <form action="/send-message" method="post" aria-labelledby="contact-form-title">
    <h3 id="contact-form-title">Send a Message</h3>

    <div class="form-group">
      <label for="name">Name<span aria-hidden="true">*</span></label>
      <input type="text" id="name" name="name" required aria-required="true">
    </div>

    <div class="form-group">
      <label for="email">Email<span aria-hidden="true">*</span></label>
      <input type="email" id="email" name="email" required aria-required="true">
    </div>

    <div class="form-group">
      <label for="subject">Subject</label>
      <input type="text" id="subject" name="subject">
    </div>

    <div class="form-group">
      <label for="message">Message<span aria-hidden="true">*</span></label>
      <textarea id="message" name="message" rows="6" required aria-required="true"></textarea>
    </div>

    <button type="submit">Send Message</button>
  </form>

  <p class="note">I aim to respond within 48 hours. All messages are treated confidentially.</p>

</div>
