---
layout: default
permalink: /misc/
title: "Hobbies"
excerpt: ""
author_profile: true
---
# Hobbies 
- 🏀 Basketball: I play the shooting guard. A huuuuge fan of Steph Curry 30 and GSW.
- 🎿 Skiing: A group member in SJTU Skiing club. Double plate.
- 🍸 Mixing drinks: Enjoy creating and tasting new cocktails. You can get some research ideas when slightly drunk.

<style>
.photo-gallery {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 15px;
  margin-bottom: 30px;
}

.gallery-column {
  display: flex;
  flex-direction: column;
  gap: 15px;
}

.gallery-item {
  position: relative;
  overflow: hidden;
  border-radius: 8px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
  transition: transform 0.3s ease;
}

.gallery-item:hover {
  transform: translateY(-5px);
}

.gallery-item img {
  width: 100%;
  height: 200px;
  object-fit: cover;
  display: block;
}

.gallery-item .caption {
  position: absolute;
  bottom: 0;
  left: 0;
  right: 0;
  background: rgba(0,0,0,0.7);
  color: white;
  padding: 8px 12px;
  font-size: 14px;
  font-weight: bold;
}

@media (max-width: 768px) {
  .photo-gallery {
    grid-template-columns: 1fr;
  }
}

#chartdiv {
  width: 100%;
  height: 600px;
  margin: 20px 0;
  border-radius: 8px;
  overflow: hidden;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
}

.map-legend {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  margin: 20px 0;
}

.legend-item {
  display: flex;
  align-items: center;
  margin: 0 15px 10px 15px;
}

.legend-color {
  width: 20px;
  height: 20px;
  margin-right: 8px;
  border-radius: 3px;
}

.lived {
  background-color: #2255AA;
}

.visited {
  background-color: #5588DD;
}

.planned {
  background-color: #99CCFF;
}

.section-separator {
  margin: 50px 0;
  border: 0;
  border-top: 2px solid #f0f0f0;
}
</style>

<div class="photo-gallery">
  <!-- Basketball Column -->
  <div class="gallery-column">
    <div class="gallery-item">
      <img src="/assets/misc/basketball1.JPG" alt="Basketball">
      <div class="caption">Basketball</div>
    </div>
    <div class="gallery-item">
      <img src="/assets/misc/basketball2.JPG" alt="Basketball">
      <div class="caption">Basketball</div>
    </div>
  </div>

<!-- Skiing Column -->

<div class="gallery-column">
    <div class="gallery-item">
      <img src="/assets/misc/skiing1.jpg" alt="Skiing">
      <div class="caption">Skiing</div>
    </div>
    <div class="gallery-item">
      <img src="/assets/misc/skiing3.jpg" alt="Skiing">
      <div class="caption">Skiing</div>
    </div>
  </div>

<!-- Mixing drinks -->

<div class="gallery-column">
    <div class="gallery-item">
      <img src="/assets/misc/drink1.jpg" alt="Mixing drinks">
      <div class="caption">Mixing drinks</div>
    </div>
    <div class="gallery-item">
      <img src="/assets/misc/drink2.jpg" alt="Mixing drinks">
      <div class="caption">Mixing drinks</div>
    </div>
  </div>
</div>
