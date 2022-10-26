---
layout: page
title: Categories

permalink: "/categories/"

---

<!--- {% for category in site.categories %} --->


 {% for page in site.pages %}
  {% if page.categories contains category %}
    <div class="item">
      <h3>{{page.title}}</h3>
      <p>{{page.description}}</p>
    </div>
  {% endif %}
 {% endfor %}
 
 s

<!---
  <h1>{{ category }}</h1>
  <ul>
    {% for post in site.categories[category] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
--->

<!--- {% endfor %} --->




