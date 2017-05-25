---
layout: page
title: PORTFOLIO
permalink: /portfolio/
---
I have always been curious about a lot of things, from how the nature works to how mechanisms work, and try and do it myself. This has always been the best way to learn things. 

A good engineer does not mean good at structural engineering only or expert in geotechnical engineering, they involve in a whole wide range of problem analysis and solving, hence recently I have been working with a few of my friends on startup projects including MatesWeb and Openmusic. I have to admit the skills are not even remotely related to civil engineering, but through experiences like this I have learnt the most important skill that an engineer should have: problem solving. 

{% for project in site.portfolio %}

{% if project.redirect %}
<div class="project">
    <div class="thumbnail">
        <a href="{{ project.redirect }}" target="_blank">
        {% if project.img %}
        <img class="thumbnail" src="{{ project.img }}"/>
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
        <a href="{{ site.baseurl }}{{ project.url }}">
        {% if project.img %}
        <img class="thumbnail" src="{{ project.img }}"/>
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
