---
layout: page
title: Blog de Gobierno Fácil
description: Ideas, datos abiertos, investigación y periodismo de datos del equipo de Gobierno Fácil
tagline: Ideas, datos abiertos, investigación, periodismo de datos y experimentos del equipo de Gobierno Fácil
---
{% include JB/setup %}


<ul class="posts">
  {% for post in site.posts %}
    <li>
    	<h2> <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></h2>
    	<span class="des">{{ post.tagline}}</span>
		<span>{{ post.date | date_to_string }} / {{ post.author }}</span> 
    
    </li>
  {% endfor %}
</ul>


