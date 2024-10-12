---
title: 03-deliver
permalink: 03-deliver.html
layout: page
unit:
    course: 'intro-operation-management'
    title: '03-deliver'
    module: '000 Operation management'
---

## Preview
You can have a look here
[preview]( 000-operation-management/010-directing-the-operation/preview/index.html )

## SCORM
You can download the SCORM package to be integrated into an LMS, e.g. Moodle.

{% assign files = site.static_files  %}
{% for file in files   %}
{% if file.path contains page.title and file.path contains  'zip' %}
[{{ file.basename }}]( {{  site.baseurl }}{{ file.path }})
{% endif %}
{% endfor %}


## Content
The theoretical contents of the course are shown below.

{% assign files = site.static_files  %}
{% for file in files   %}
{% if file.path contains page.title and file.path contains  'pdf' %}
[{{ file.basename }}]( {{  site.baseurl }}{{ file.path }})
{% endif %}
{% endfor %}




