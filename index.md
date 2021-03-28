---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

{% t rufus.tagline %}

Test:
{% for lang in site.data.languages %}{% assign language = lang[1] %}* [{{ language.icon }} {{ language.label }}]({{ site.url }}/{{ lang[0] }})
{% endfor %}

