---
layout: default 
permalink: /news/
---

<ul class="articles">
{% for post in site.posts %}
  <li>
    <h2>
      <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
    </h2>
    <div>{{ post.date | date: "%b %-d, %Y" }}</div>
    <div>{{ post.excerpt | remove: '<p>' | remove: '</p>' }}</div>
  </li>
{% endfor %}
</ul>