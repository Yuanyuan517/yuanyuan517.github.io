---
layout: about
title: About
permalink: /
#subtitle: Postdoctoral Researcher at <a href="https://www.hec.ca/en/">HEC Montréal</a> and <a href="https://www.gerad.ca/en/">GERAD</a>

profile:
  align: right
  image: yuanyuan_li.png
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>Montréal, Québec, Canada</p>

selected_papers: false # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

I am a postdoctoral researcher at HEC Montréal and GERAD, where I work with Jean-François Cordeau, Yossiri Adulyasak, and Emma Frejinger. I received my PhD in Operations Research and Operations Management from ESSEC Business School under the supervision of Claudia Archetti, Ivana Ljubić, and Felix Papier.

## Research

My research studies how firms can design operational policies under uncertainty while accounting for customer behavior and operational constraints. I develop optimization- and learning-based methods for these settings, with recent applications to same-day delivery, entrepreneurial operations, and experiential services.

<h2>
  <a href="{{ '/research/' | relative_url }}" style="color: inherit;">
    Selected Research
  </a>
</h2>

<div class="publications home-selected-research">
  {% bibliography --group_by none --query @*[selected=true]* %}
</div>

<style>
  .home-selected-research {
    margin-top: 1rem;
  }

  .home-selected-research .row {
    margin-left: 0;
    margin-right: 0;
  }

  .home-selected-research .row > .col-sm-10 {
    flex: 0 0 100%;
    max-width: 100%;
    padding-left: 0;
    padding-right: 0;
  }
</style>
