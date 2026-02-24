---
layout: archive
title: "San Diego Sunshine ☀️"
permalink: /gallery/
author_profile: true
---

<style>
.gallery-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 16px;
  padding: 20px 0;
}

@media (max-width: 900px) {
  .gallery-grid {
    grid-template-columns: repeat(2, 1fr);
  }
}

@media (max-width: 600px) {
  .gallery-grid {
    grid-template-columns: 1fr;
  }
}

.gallery-item {
  position: relative;
  overflow: hidden;
  border-radius: 12px;
  background: #f0f0f0;
  box-shadow: 0 2px 8px rgba(0,0,0,0.08);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.gallery-item:hover {
  transform: translateY(-4px);
  box-shadow: 0 8px 24px rgba(0,0,0,0.15);
}

.gallery-item img {
  width: 100%;
  height: auto;
  display: block;
  border-radius: 12px;
  transition: transform 0.4s ease;
}

.gallery-item:hover img {
  transform: scale(1.05);
}

.gallery-video {
  aspect-ratio: 16/9;
  margin-bottom: 24px;
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 0 2px 8px rgba(0,0,0,0.08);
}

.gallery-video iframe {
  width: 100%;
  height: 100%;
  border-radius: 12px;
}

@media (max-width: 600px) {
  .gallery-video {
    grid-column: span 1;
  }
}

.gallery-placeholder {
  text-align: center;
  padding: 80px 20px;
  color: #999;
  font-size: 1.3em;
}

.gallery-placeholder .emoji {
  font-size: 3em;
  display: block;
  margin-bottom: 16px;
}
</style>

Sunshine, ocean breeze, and daily life in San Diego.

---

<div class="gallery-item gallery-video">
  <iframe src="https://www.youtube.com/embed/Ik7-wn9qrc8" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

<div class="gallery-grid">
  <div class="gallery-item">
    <img src="/images/gallery/scripps-sunset.jpg" alt="Scripps Research sunset">
  </div>
  <div class="gallery-item">
    <img src="/images/gallery/scripps-bluesky.jpg" alt="Scripps Research blue sky">
  </div>
</div>
