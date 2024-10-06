---
title: 020-design-the-operation
permalink: 020-design-the-operation.html
layout: page
unit:
    course: 'intro-operation-management'
    title: '020 Design the operation'
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
[preview]({{ './preview' }})