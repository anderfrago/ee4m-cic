---
layout: page
Introduction to Operation Management:
  title: "Introduction to Operation Management: Example"
  module: "Module 0: Placeholder"
---

# Content Directory

Hyperlinks to each of the docs are listed below.

## Labs

{% assign docs = site.pages | where_exp:"page", "page.url contains '/documentation'" %}
| Course | Module | Lab |
| --- |--- | --- | 
{% for activity in docs  %}| {{ activity.docs.course }} |{{ activity.docs.module }} | [{{ activity.docs.title }}{% if activity.docs.type %} - {{ activity.docs.type }}{% endif %}]({{ site.github.url }}{{ activity.url }}) |
{% endfor %}
