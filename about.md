---
layout: thumbs
permalink: /about/
---

<p>
PEI Developers is simply an informal group of software developers, web designers, and other techies. It’s a Nerd Club.
</p>
<p>
We meet monthly, and organize hackathons on occasion. Some time back, our co-organizers drafted a mission statement. Here it is…
</p>
<p>
At PEI Developers, we value:
</p>
<p>
<strong>Inclusion.</strong> You are welcome here. We offer a friendly atmosphere regardless of gender, race, LGBT, and so on. We aren’t 
a youth centre, but we welcome talented young people who are engaged in software development.
</p>
<p>
<strong>Openness.</strong> We celebrate the principles of Open Data. Open-source is a given.
</p>
<p>
<strong>Individuals.</strong> We encourage the development of the individual software developer (as opposed to a business incubator). We 
mentor on development, presentation skills, project management and more. Our group ranges widely in experience, but 
we all share a common passion for software.
</p>
<p>
<strong>Community.</strong>  We want to interact with existing organizations to build a “tech scene” on PEI. We’ll work with government, 
industry, schools, youth: you name it. We’re opinionated, independent, and eager to help. Let’s go!
</p>
PEI Devs

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
