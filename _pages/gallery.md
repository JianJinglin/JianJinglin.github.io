---
layout: archive
title: "圣地亚哥的阳光 ☀️"
permalink: /gallery/
author_profile: true
---

<style>
.gallery-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
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
  aspect-ratio: 4/3;
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
  height: 100%;
  object-fit: cover;
  transition: transform 0.4s ease;
}

.gallery-item:hover img {
  transform: scale(1.05);
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

San Diego 的阳光、海风、和日常。

---

<div class="gallery-placeholder">
  <span class="emoji">📸</span>
  Photos coming soon...
</div>

<!--
To add photos: drop images into /images/gallery/ and uncomment below.
Copy the gallery-item div for each new image.

<div class="gallery-grid">
  <div class="gallery-item">
    <img src="/images/gallery/example.jpg" alt="Description">
  </div>
</div>
-->
