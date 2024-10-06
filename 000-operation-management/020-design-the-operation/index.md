---
title: 020-design-the-operation
permalink: 020-design-the-operation.html
layout: page
unit:
    course: 'intro-operation-management'
    title: '020 Design the operation'
    module: '000 Operation management'
---
The SCORM package (accesible to download from [here](./020-design-the-operation/SCORM-020-design-the-operation.zip){:target="_blank"} ) is integrable in LMSs like Moodle
You can access to a [preview](./020-design-the-operation/preview){:target="_blank"}

{% for file in site.static_files %}
    {% if file.path contains page.title and file.path contains  'pdf' %}
        [ {{ file.basename }} ]( {{ file.path }} ){:target="_blank"}
        <a href="{{ file.path }}"> {{ file.basename }} </a>
    {% endif %}
{% endfor %}