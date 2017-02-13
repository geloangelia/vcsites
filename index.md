---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: home
---

Venture Capital List
{% for item in site.data.vclist %}
  <p><a class="page-link" href="vccontent"> {{ item.Name }}</a></p>
{% endfor %}
