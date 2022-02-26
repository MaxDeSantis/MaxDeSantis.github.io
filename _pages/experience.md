---
layout: archive
title: "Experience"
permalink: /experience/
author_profile: true
---


{% include base_path %}

<div class="experience_list">
  <!-- Loop through categories -->
  <div class = "item-list">
  {% for item in site.experience reversed %}
    <!-- For each category, add header -->
    <ul class="archive-list">
        {% include archive-list-item.html %}
    </ul>
  {% endfor %}
  </div>
</div>