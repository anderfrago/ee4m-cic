---
title: 020-design-the-operation
permalink: 020-design-the-operation.html
layout: page
unit:
    course: 'intro-operation-management'
    title: '020 Design the operation'
    module: '000 Operation management'
---
The SCORM package (accesible to download from [here]({{ page.path }}/ee4m-scorm-020.zip){:target="_blank"} ) is integrable in LMSs like Moodle
You can access to a [preview]({{ page.path }}/preview){:target="_blank"}

{% assign files = site.static_files  %}
{% for file in files   %}
{% if file.path contains page.title and file.path contains  'pdf' %}
[{{ file.basename }}]( {{  site.baseurl }}{{ file.path }})
{% endif %}
{% endfor %}