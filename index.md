---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<h1>Models</h1>

{% for model in site.models %}
<a href="{{ model.url }}">
    {{ model.name }}
</a>
{% endfor %}

<h1>Datasets</h1>
{% for dataset in site.datasets %}
<a href="{{ dataset.url }}">
    {{ dataset.name }}
</a>
{% endfor %}