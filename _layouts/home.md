---
layout: default
---

<div class="home">

  {{ content }}
  
  {% capture intro_include %}{% include party.md %}{% endcapture %}
  {{ intro_include | markdownify }}

</div>
