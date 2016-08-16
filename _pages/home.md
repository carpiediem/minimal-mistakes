---
layout: archive
permalink: /
header:
  overlay_color: "#5e616c"
  overlay_image: home-page-feature.jpg
  #cta_label: "<i class='fa fa-download'></i> Install Now"
  #cta_url: "/docs/quick-start-guide/"
  caption:
excerpt: 'A look into the big data of Hong Kong politics, <br/>using public records and the R language'
---

{% include base_path %}

{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}

{% include paginator.html %}
