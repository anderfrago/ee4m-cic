---
title: 010-directing-the-operation
permalink: 010-directing-the-operation.html
layout: page
unit:
    course: 'intro-operation-management'
    title: '010 Direction the operation'
    module: '000 Operation management'
---
The SCORM package (accesible to download from [here](./010-directing-the-operation/SCORM-010-directing-the-operation.zip){:target="_blank"} ) is integrable in LMSs like Moodle
You can access to a [preview](./010-directing-the-operation/preview){:target="_blank"}

{% assign files = site.static_files  %}
{% for file in files   %}
{% if file.path contains page.title and file.path contains  'pdf' %}
[{{ file.basename }}]({{  file.path }})
{% endif %}
{% endfor %}