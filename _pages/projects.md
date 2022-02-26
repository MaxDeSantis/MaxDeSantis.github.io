---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---


<!-- {% include base_path %}

{% for post in site.projects reversed %}
  {% include archive-single.html %}
{% endfor %} -->

{% include base_path %}

<div class="project_list">
  <!-- Loop through categories -->
  <div class = "item-list">
  {% for item in site.projects reversed %}
    <!-- For each category, add header -->
    <ul class="archive-list">
        {% include archive-list-item.html %}
    </ul>
  {% endfor %}
  </div>
</div>