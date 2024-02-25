---
module:
    course: 'intro-operation-management'
    title: 'Introduction to operation management'
    module: 'Introduction to operation management'
---

# Content Directory

Hyperlinks to each of the docs are listed below.

## Units

{% assign units = site.pages | where_exp:"page", "page.url contains '/*'" %}
| Course | Module | Lab |
| --- |--- | --- | 
{% for activity in units  %}| {{ activity.units.course }} |{{ activity.units.module }} | [{{ activity.units.title }}{% if activity.units.type %} - {{ activity.units.type }}{% endif %}]({{ site.github.url }}{{ activity.url }}) |
{% endfor %}
