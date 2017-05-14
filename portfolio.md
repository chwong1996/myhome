---
layout: page
title: PORTFOLIO
permalink: /portfolio/
---

{% for project in site.portfolio %}

{% if project.redirect %}
<div class="project">
    <div class="thumbnail">
        <a href="{{ portfolio.redirect }}" target="_blank">
        {% if project.img %}
        <img class="thumbnail" src="{{ portfolio.img }}"/>
        {% else %}
        <div class="thumbnail blankbox"></div>
        {% endif %}    
        <span>
            <h1>{{ project.title }}</h1>
            <br/>
            <p>{{ project.description }}</p>
        </span>
        </a>
    </div>
</div>
{% else %}

<div class="project ">
    <div class="thumbnail">
        <a href="{{ site.baseurl }}{{ portfolio.url }}">
        {% if project.img %}
        <img class="thumbnail" src="{{ portfoliko.img }}"/>
        {% else %}
        <div class="thumbnail blankbox"></div>
        {% endif %}    
        <span>
            <h1>{{ project.title }}</h1>
            <br/>
            <p>{{ project.description }}</p>
        </span>
        </a>
    </div>
</div>

{% endif %}

{% endfor %}
