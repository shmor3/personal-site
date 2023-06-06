---
layout: page
title: "Work"
permalink: /work/
---

<form action="{FORM_ENDPOINT}" method="POST" target="_blank">
  <div class="name-field">
    <input type="text" placeholder="Your name" name="name" required />
  </div>
  <div class="email-field">
    <input type="email" placeholder="Email" name="email" required />
  </div>
  <div class="message-field">
    <textarea placeholder="Your message" name="message" required></textarea>
  </div>
  <div class="form-submit">
    <button type="submit">Send a message</button>
  </div>
</form>