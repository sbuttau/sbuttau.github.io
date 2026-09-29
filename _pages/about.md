---
layout: about
title: about
permalink: /
subtitle: University of Padua

profile:
  align: right
  image: prof_pic2.JPEG
  image_circular: true # crops the image to make it circular
  more_info: >
    <p>sara.buttau@phd.unipd.it</p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: false # social icons are rendered in the page content below, under the profile picture

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

<style>
  /* square crop so the circular mask is a circle, not an oval */
  .profile img {
    aspect-ratio: 1 / 1;
    object-fit: cover;
  }
  .profile-social {
    float: right;
    clear: right;
    width: 30%;
    margin: 0 0 1rem 1rem;
    text-align: center;
  }
  .profile-social .contact-icons {
    font-size: 1.6rem;
  }
  @media (max-width: 576px) {
    .profile-social {
      float: none;
      width: 100%;
      margin-left: 0;
    }
  }
</style>

<div class="social profile-social">
  <div class="contact-icons">{% social_links %}</div>
</div>

I'm Sara, a PhD student at the University of Padua, Department of Mathematics. I'm part of the [Visual Intelligence and Machine Perception (VIMP)](http://vimp.math.unipd.it/)  group, supervised by [Prof. Lamberto Ballan](https://www.lambertoballan.net/). My research lies at the intersection of **3D computer vision** and **natural language**, with a focus on **3D visual grounding**. I am particularly interested in understanding how these models work internally, and how different visual representations affect grounding.

I also have research experience in **medical imaging**, **3D human pose estimation** and **mesh recovery**, and **3D occupancy prediction**.
