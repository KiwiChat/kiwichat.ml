---
title: "Comments"
permalink: /comments
---
 <p>test comments</p>
<form method="POST" action="{{ site.staticman_url }}" onsubmit="return buttonPress();">
  <input name="options[redirect]" type="hidden" value="{{ site.url }}">
  <label>Name: <input name="fields[name]" type="text"></label><br>
  <label>Email: <input name="fields[email]" type="email"></label><br>
  <label>Message: <br><textarea name="fields[message]" id="comments" rows="12" cols="36"></textarea></label><br>
  <input type="submit" value="Submit">
</form>
{% include comments.html %}
