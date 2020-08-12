---
layout: post
title: "Contact me"
---

<h1 class="title is-size-2">{{ page.title }}</h1>

<p class="m-b-1-25">If you wish to contact me or say hi, please leave your message below or write me via <a href="mailto:cv@thinkjanis.com">email</a>.</p>

<form action="https://formspree.io/cv@thinkjanis.com" method="POST">

  <div class="field">
    <div class="control has-icons-left">
      <input name="name" class="input is-medium-mobile" type="text" placeholder="Your name">
      <span class="icon is-small is-left">
        <i class="fa fa-user"></i>
      </span>
    </div>
  </div>

  <div class="field">
    <div class="control has-icons-left">
      <input name="_replyto" class="input" type="email" placeholder="Your email">
      <span class="icon is-small is-left">
        <i class="fa fa-envelope"></i>
      </span>
    </div>
  </div>

  <div class="field">
    <div class="control">
      <textarea name="message" class="textarea" placeholder="Your message"></textarea>
    </div>
  </div>

  <div class="field">
    <div class="control">
      <button class="button is-primary">Submit</button>
    </div>
  </div>

</form>