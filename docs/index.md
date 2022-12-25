---
layout: home
---



## Games for checker board

{% for page in site.checkerboardgames %}
[{{ page.title }}]({{site.baseurl}}{{ page.url }})
{% endfor %}

## Games for alquerque board

{% for page in site.alquerqueboardgames %}
[{{ page.title }}]({{site.baseurl}}{{ page.url }})
{% endfor %}
