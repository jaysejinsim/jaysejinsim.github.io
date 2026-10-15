---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a PhD candidate in the Department of Mechanical Engineering at Stanford University, where I work on projects related to stimuli-responsive materials, active metamaterials, soft robotics, and other reconfigurable devices. Graduated from Penn State University in 2022 with honors in mechanical engineering (grew up in State College, PA). Feel free to reach out if you'd like to collaborate or just chat about research.

<style>
.research-gallery {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 1.5em;
  margin-top: 2em;
}
.research-gallery figure {
  margin: 0;
}
.research-gallery img {
  width: 100%;
  aspect-ratio: 1 / 1;
  object-fit: cover;
  border-radius: 4px;
  display: block;
}
.research-gallery figcaption {
  display: block;
  width: 100%;
  margin-top: 0.5em;
  font-size: 0.7em !important;
  text-align: center !important;
  color: var(--global-text-color-light, #767676);
}
</style>

<div class="research-gallery">
  {% assign gallery = site.data.gallery %}
  {% for item in gallery %}
  <figure>
    <a href="{{ item.url }}" target="_blank" rel="noopener">
      <img src="{{ item.image }}" alt="{{ item.caption }}">
    </a>
    <figcaption>{{ item.caption }}</figcaption>
  </figure>
  {% endfor %}
</div>
