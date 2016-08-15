---
layout: thumbs
permalink: /about/
---

Founded during the first long winter, during the battle with the First men. The PEI Developers group continues the power
struggle today during the battle of the 6 kings.


<div class="aboutus">
{% for elders in site.data.group.elders %}
    <div class="thumbnail">
      <img src="{{ elders.img }}" alt="{{ elders.name }}">
      <div class="caption">
        <h4>{{elders.name}}</h4>
        <p>{{ elders.description }}</p>
      </div>
    </div>
{% endfor %}
</div>
