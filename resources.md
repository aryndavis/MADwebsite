---
layout: default
title: "RESOURCES"
permalink: /resources/

---

# Here are links to our resources and graphics detailing more information around why our demands should be met:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{site.baseurl}}{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>


