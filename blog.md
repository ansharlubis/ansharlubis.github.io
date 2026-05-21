---
layout: default
title: 📝 blog
---
<h1>Posts</h1>

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      {% if post.categories %}<p class="post-categories">{{ post.categories | join: ", " }}</p>{% endif %}
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>