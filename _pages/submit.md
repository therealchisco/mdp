---
layout: page
title: Submit
permalink: /submit/
---

<form id="fs-frm" name="simple-contact-form" accept-charset="utf-8" action="https://formspree.io/YOUR_EMAIL_HERE" method="post">
  <fieldset id="fs-frm-inputs">
    <label for="full-name">Full Name</label>
    <input name="name" id="full-name" placeholder="First and Last" required="" type="text">
    <label for="email-address">Email Address</label>
    <input name="_replyto" id="email-address" placeholder="email@domain.tld" required="" type="email">
    <label for="message">Message</label>
    <textarea rows="5" name="message" id="message" placeholder="Aenean lacinia bibendum nulla sed consectetur. Vivamus sagittis lacus vel augue laoreet rutrum faucibus dolor auctor. Donec ullamcorper nulla non metus auctor fringilla nullam quis risus." required=""></textarea>
    <input name="_subject" id="email-subject" value="Contact Form Submission" type="hidden">
  </fieldset>
  <input value="Submit" type="submit">
</form>