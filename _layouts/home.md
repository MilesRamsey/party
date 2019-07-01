---
layout: default
---

<div class="home">

  {{ content }}
  
  {% capture intro_include %}{% include intro.md %}{% endcapture %}
  {{ intro_include | markdownify }}

</div>
