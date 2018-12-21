---
layout: default
---

<div class="home">

  {{ content }}
  
  {% capture intro_include %}{% include intro.md %}{% endcapture %}
  {{ intro_include | markdownify }}
  
  {% include salesforce.md %}
  
  {% include certifit.md %}
  
  {% include utah.md %}
  
  <!--{% include youtube.md %}-->

</div>
