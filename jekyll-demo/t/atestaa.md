---
permalink: /atest/
title: atest
---
aaaa
<ul>
{% for item in site.atest %}
    <li>
        {{item.title}}
        <p>{{item.content}}</p>
    </li>

{% endfor %}
</ul>