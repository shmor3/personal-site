---
title: Work
permalink: /work/
layout: page
---

<div class="pdf-resume">
    <a href="/work/resume">View PDF Version</a>
</div>

<div class="work-wrapper">
    {% for work in site.data.work %}
        <div class="work-item">
            <img class="logo" src="{{ work.logo }}">
            <h2><a href="{{ work.url }}">{{ work.company }}</a></h2>
            <h5>{{ work.role }}  &bull; {{ work.duration }}</h5>
            {% if work.role-1 %}
            <h5>{{ work.role-1 }}  &bull; {{ work.duration-1 }}</h5>
            {% endif %}
            <div class="case-study">
            <a href="{{ work.case-study }}"> View Case Study</a>
        </div>
        </div><br/>
    {% endfor %}
</div>

<style>
    .pdf-resume {
        text-align: right;
    }
    .work-wrapper {
        display: flex;
        flex-direction: column;
        margin-top: 2rem;
    }
    .logo {
        width: 7rem;
        float: left;
        margin: 1.5rem 2rem 10rem 2rem;
        }
    .case-study {
        margin-top: 1rem;
    }
</style>
