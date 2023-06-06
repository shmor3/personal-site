---
layout: page
title: Work
permalink: /work/
---

<div class="wrapper">
  <form action="http://127.0.0.1:9387/$submit" method="POST">
    <div class="form-contact">
      <input
        class="form-input"
        style="margin-right: 1em"
        type="text"
        name="name"
        placeholder="Name"
        required
      />
      <input
        class="form-input"
        style="margin-right: 1em"
        type="email"
        name="email"
        placeholder="Email"
        required
      />
      <input
        class="form-input"
        type="text"
        name="company"
        placeholder="Company"
        required
      />
    </div>
    <div class="form-info">
      <input
        class="form-input"
        type="text"
        name="subject"
        placeholder="Subject"
        required
      />
      <textarea
        class="form-text"
        rows="10"
        name="message"
        placeholder="Message"
        required
      ></textarea>
      <br /><button class="form-button" type="submit">Send</button>
    </div>
  </form>
</div>