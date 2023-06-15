---
title: Projects
permalink: /projects/
layout: page
---

<div class="project-wrapper">
{% for project in site.data.projects %}
<div>
    <h2>
    {% if project.url %}
    <a href="{{ project.url }}">{{ project.project }}</a>
    {% else %}
    {{ project.project }}
    {% endif %}</h2>
    <p>{{ project.description }}</p>
</div>
<br/>
{% endfor %}

</div>

<style>
    .project-wrapper {
        display: flex;
        flex-direction: column;
    }
</style>
