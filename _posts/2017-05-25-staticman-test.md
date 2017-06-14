---
layout: post
title: staticman test
date: 2017-05-25
---

<form method="POST" action="https://api.staticman.net/v2/entry/tpmgt/situvieraalas/gh-pages/comments">
  <input name="options[redirect]" type="hidden" value="https://situvieraalas.cf/blog/2017/05/25/staticman-test">
  <!-- e.g. "2016-01-02-this-is-a-post" -->
  <input name="options[slug]" type="hidden" value="{{ page.slug }}">
  <label><input name="fields[name]" type="text">nombre</label><br/>
  <label><input name="fields[email]" type="email">correo electronico</label><br/>
  <label><textarea name="fields[message]"></textarea>mensaje</label><br/>
  <input type="hidden" name="options[reCaptcha][siteKey]" value="6Lda0yQUAAAAADRhdZERZOAdCBbcdshzO7kdGBKJ">
  <input type="hidden" name="options[reCaptcha][secret]" value="XFbotxzieZhcnKzBo+2L1VtDcHJTnSTYPQ4/6yPo7fSVNqggwj78TEbx6dMZ5eTqLF1A34gbltteTVV9HkZW14/XsXQ2vbmcYl4YT08ES5Zk81CbvWiXUoWH6vJZ4z4BiOn8EgCQKaJtQQp3DZU/XGuF5QlDGxsQqVg9OIUzuRA=">
  <div class="g-recaptcha" data-sitekey="6Lda0yQUAAAAADRhdZERZOAdCBbcdshzO7kdGBKJ"></div>
  
  <button type="submit">enviar</button>
</form>
