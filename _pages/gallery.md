---
layout: archive
title: "Photo Gallery"
permalink: /gallery/
author_profile: false
---

<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@500;700&display=swap" rel="stylesheet">

<style>
.gallery-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 1.2rem;
  margin-top: 2rem;
}
.gallery-item {
  position: relative;
  overflow: hidden;
  border-radius: 14px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.1);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}
.gallery-item:hover {
  transform: scale(1.03);
  box-shadow: 0 4px 16px rgba(0,0,0,0.15);
}
.gallery-item img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}
.caption {
  text-align: center;
  margin-top: 0.5rem;
  font-size: 0.9rem;
  font-style: italic;
  color: #666;
}
</style>

# Gallery

A few memorable moments from my academic journey — research, collaboration, and graduation.

<div class="gallery-grid">

  <div class="gallery-item">
    <img src="/images/with PI at Universitas Indonesia.jpg" alt="with PI at Universitas Indonesia">
    <div class="caption">With Supervisors and Group colleague(2024)</div>
  </div>

  <div class="gallery-item">
    <img src="/images/Master Graduation.jpg" alt="Master Graduation">
    <div class="caption">Graduation ceremony with colleagues (2024)</div>
  </div>

  <div class="gallery-item">
    <img src="/images/with Lab Colleagues.jpg" alt="with Lab Colleagues">
    <div class="caption">Lab portrait, TCMP, Universitas Indonesia, 2024</div>
  </div>

</div>
