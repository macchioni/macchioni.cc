+++
type = "static"
page = "static/single.html"
title = "about"
description = "Piero Macchioni, journo"
menu = "main"
weight = "4"
+++

<form name="contact" method="POST" data-netlify="true" netlify-honeypot="bot-field">
	<div hidden aria-hidden="true">
    <label>
      Don’t fill this out if you're human: 
      <input name="bot-field" />
    </label>
  </div>
  <p>
    <label>Your Name: <input type="text" name="name" /></label>   
  </p>
  <p>
    <label>Your Email: <input type="email" name="email" /></label>
  </p>
 
  <p>
    <label>Message: <textarea name="message"></textarea></label>
  </p>
  <p>
    <button type="submit">Send</button>
  </p>
</form>
