---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
display_categories: [Papers, Poster Presentations]
---

{% include base_path %}

<div class="category_list">
{% for category in page.display_categories %}
    <div>
    <h2 class="research_category"><span>{{category}}</span></h2>
    {% assign categorized_items = site.paperspresentations | where: "category", category %}
    <ul class="simple_list">
    {% for item in categorized_items reversed %}
        {% include research-list-item.html %}
    {% endfor %}
    </ul>
    </div>
{% endfor %}
</div>

# Interests
My research interests revolve around the control of autonomous systems. In particular, the coordination and control of both heterogenous and homogenous multi-agent systems. I find all aspects of this problem fascinating - intercommunication amongst agents, outside control through an HMI, and internal control of individual agents. 

# Work
I have explored these interests through my research activities with CoRAL and other activities. My current funded work developing spatiotemporally varying wind simulation and wind-aware piloting interfaces is a direct application of my interests in human control of remote vehicles. It will serve as a stepping stone into further work in the control of multi-agent drone systems. The DORADO project is planned to involve complex inter-agent communication to coordinate the landing and takeoff of a drone onto a mobile aquatic platform. My work on the Autonomous Golf Cart, where I developed embedded low-level control software using PID and ROS, was my introduction to control and a key milestone in my development as a controls engineer.