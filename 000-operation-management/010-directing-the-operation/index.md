---
title: 010-directing-the-operation
permalink: 010-directing-the-operation.html
layout: page
unit:
    course: 'intro-operation-management'
    title: '010 Direction the operation'
    module: '000 Operation management'
---


# SCORM
{% assign files = site.static_files  %}
{% for file in files   %}
{% if file.path contains page.title and file.path contains  'zip' %}
[{{ file.basename }}]( {{  site.baseurl }}{{ file.path }})
{% endif %}
{% endfor %}


# Content
{% assign files = site.static_files  %}
{% for file in files   %}
{% if file.path contains page.title and file.path contains  'pdf' %}
[{{ file.basename }}]( {{  site.baseurl }}{{ file.path }})
{% endif %}
{% endfor %}

# Preview
[{{ file.basename }}]( {{  site.baseurl }}{{ file.path | replace: 'index.html', '' }}preview)