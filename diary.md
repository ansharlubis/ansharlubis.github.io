---
layout: default
title: If you found this, then so be it 
---
<h1>Logs</h1>

<ul>
  {% for post in site.diary %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>