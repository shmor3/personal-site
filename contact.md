---
layout: page
title: Contact
permalink: /contact/
---
<div class="form-wrapper">
  <form action="{{ site.form-endpoint }}" method="POST">
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
    <span>
    <a style="padding-right: 7px !important;" href="https://github.com/shmor3"><img class="social-media-darkmode" src="../media/GitHub-Mark-64px.png" height="25rem" alt="github"/></a>
    <a href="https://www.linkedin.com/in/robertestanford/"><img class="social-media" src="../media/LI-In-Bug.png" height="23rem" alt="linkedin"/></a>
    <a href="mailto:contact@rstanford.com"><img class="social-media-darkmode" src="../media/586624.png" height="25rem" alt="email"/></a>
  </span>
</div>

<style>
  .form-wrapper {
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .form-contact {
    display: flex;
    flex-direction: row;
    align-content: stretch;
  }
  .form-info {
    display: flex;
    flex-direction: column;
    align-content: stretch;
  }
  .form-input {
    padding: 1em 1.5em;
    border: 1px solid #e5e5e5;
    border-radius: 1rem;
    margin-bottom: 1em;
    resize: none;
  }
  .form-text {
    padding: 1em 1.5em;
    border: 1px solid #e5e5e5;
    border-radius: 1rem;
    resize: none;
  }
  .form-button {
    padding: 1em 1.5em;
    border: 1px solid #e5e5e5;
    border-radius: 1rem;
    background-color: #e5e5e5;
  }
  .form-button:hover {
    border: 1px solid #ff5277;
    background-color: #ff5277;
    cursor: pointer;
  }
</style>