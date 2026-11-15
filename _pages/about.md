---
layout: about
title: about
permalink: /
subtitle: PhD Candidate in Aerospace Engineering, KAIST · <a href="https://arml.kaist.ac.kr/">ARML</a>

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>Aerospace Robotics and Mechanisms Laboratory</p>
    <p>Dept. of Aerospace Engineering, KAIST</p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: false # links live in the Connect row (_data/contact.yml)

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false # turned on once the first essay is published
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

I am a PhD candidate in Aerospace Engineering at KAIST, working with Prof. Dae-Young Lee at the Aerospace Robotics and Mechanisms Laboratory (ARML). My research is on robot mobility on soft, granular terrain, with a focus on planetary exploration rovers and deployable structures.

<p class="connect"><strong>Connect</strong>
  <span class="connect-item"><i class="fa-solid fa-envelope"></i> {% al_email_protect_link site.data.contact.email %}</span>
  {% if site.data.contact.linkedin %}<span class="connect-item">· <i class="fa-brands fa-linkedin"></i> <a href="{{ site.data.contact.linkedin }}">LinkedIn</a></span>{% endif %}
  <span class="connect-item">· <i class="fa-solid fa-flask"></i> <a href="{{ site.data.contact.lab }}">ARML Lab</a></span>
</p>

> _Planetary robots still get stuck in terrain we cannot predict. I work toward robot mobility that is designed, modeled, and verified before the robot touches the ground._

#### Highlights

{% assign pinned = site.news | where: "pin", true | sort: "date" | reverse %}

<ul class="highlights">
{% for item in pinned limit: 3 %}
  <li><span class="news-type news-type--{{ item.type | downcase }}">{{ item.type }}</span> <a href="{{ item.link }}">{{ item.title }}</a> <span class="text-muted">· {{ item.date | date: "%b %Y" }}</span></li>
{% endfor %}
</ul>

#### Current Focus

Physics-guided prediction of rover mobility on granular terrain

#### Research Themes

[Traversability Prediction](/research/#traversability-prediction) · [Terramechanics & Granular Physics](/research/#terramechanics) · [Adaptive Locomotion Hardware](/research/#adaptive-locomotion-hardware) · [Space Robotics](/research/#space-robotics)
