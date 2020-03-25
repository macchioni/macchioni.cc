+++
type = "static"
page = "static/contatti.html"
title = "contact me"
description = "contact me - Piero Macchioni, journo"
menu = "main"
weight = "6"
date = "2016-05-05T21:48:51-07:00"
+++

You can contact me using the form below, or via <a rel="me" target="_blank" class="u-url" href="https://twitter.com/pieromacchioni_">Twitter</a>. I'm also on <a rel="me" class="u-url" href="https://github.com/macchioni" target="_blank" >Github</a> and <a href="https://instagram.com/pieromacchioni" rel="me" target="_blank" >Instagram</a>. At the moment I do not fancy Facebook that much (a few reasons <a href="https://macchioni.cc/open-web/">here</a>).


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
