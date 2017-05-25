---
layout: post
title: staticman test
date: 2017-05-25
---

<form method="POST" action="https://api.staticman.net/v2/entry/tpmgt/situvieraalas/gh-pages/comments">
  <input name="options[redirect]" type="hidden" value="blog/2017/05/25/staticman-test">
  <!-- e.g. "2016-01-02-this-is-a-post" -->
  <input name="options[slug]" type="hidden" value="{{ page.slug }}">
  <label><input name="fields[name]" type="text">nombre</label><br/>
  <label><input name="fields[email]" type="email">correo electronico</label><br/>
  <label><textarea name="fields[message]"></textarea>mensaje</label><br/>
  
  <button type="submit">enviar</button>
</form>
