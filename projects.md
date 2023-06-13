---
title: Projects
permalink: /projects/
layout: page
---

<div class="projects-wrapper">
{% for project in site.data.projects %}
<div>
    <h3>
    {% if project.url %}
    <a href="{{ project.url }}">{{ project.project }}</a>
    {% else %}
    {{ project.project }}
    {% endif %}</h3>
    <h4>{{ project.role }}  &bull; {{ project.duration }}</h4>
    <p>{{ project.description }}</p>
</div>
{% endfor %}

</div>

<style>
    .projects-wrapper {
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
    }
</style>
