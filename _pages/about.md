---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

My research interests include Development Economics, Social Networks and Interactions, and Economic Geography. 
  
 
## Degree Educations  
- *2021.09 - 2025.06*, Bachelor of Economics, The University of Hong Kong.  

## International Studies
- *2024.06 - 2024.08*, Johns Hopkins University.
- *2023.09 - 2023.12*, Tufts University. 
- *2023.02 - 2023.05*, University of California, Berkeley. 
- *2022.07 - 2022.08*, Pembroke College, University of Cambridge. 




# Projects
 {: #projects }

  



# Gallery
{: #gallery }

<style>
  .gallery-menu {
    margin-bottom: 20px;
    padding: 10px;
    background-color: #f2f2f2;
    border-radius: 5px;
  }
  .gallery-menu ul {
    list-style-type: none;
    padding: 0;
    display: flex;
    gap: 15px;
    flex-wrap: wrap;
  }
  .gallery-menu li {
    display: inline;
  }
  .gallery-menu a {
    text-decoration: none;
    color: #007acc;
    font-weight: bold;
  }
  .gallery-menu a:hover {
    text-decoration: underline;
  }

  .gallery-grid {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 15px;
    margin-bottom: 20px;
  }
  .gallery-item img {
    width: 100%;
    height: auto;
    border-radius: 5px;
    border: 1px solid #ddd;
  }

  #map {
    height: 500px;
    margin-bottom: 20px;
    border-radius: 5px;
    border: 1px solid #ddd;
  }
</style>


---

<div class="gallery-menu">
  <ul>
    <li><a href="#beijing">Beijing</a></li>
    <li><a href="#boston">Boston</a></li>
    <li><a href="#california">Berkeley</a></li>
    <li><a href="#cambridge">Cambridge</a></li>
    <li><a href="#dali">Dali</a></li>
    <li><a href="#fuzhou">Fuzhou</a></li>
    <li><a href="#hongkong">Hong Kong</a></li>
    <li><a href="#ny">NYC</a></li>
    <li><a href="#gelato">Gelato</a></li>
  </ul>
</div>

---
  
<div id="map"></div>

<!-- Leaflet.js -->
<script src="https://unpkg.com/leaflet/dist/leaflet.js"></script>
<link rel="stylesheet" href="https://unpkg.com/leaflet/dist/leaflet.css" />

<style>
  #map {
    height: 500px;
    width: 100%;
    margin-bottom: 20px;
    border: 1px solid #ccc;
    border-radius: 5px;
  }
</style>

<script>
  document.addEventListener('DOMContentLoaded', function () {
    var map = L.map('map').setView([20.0, 0.0], 2); // Center on the world

    // OpenStreetMap tile layer
    L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', {
      maxZoom: 18,
      attribution: '&copy; <a href="https://www.openstreetmap.org/copyright">OpenStreetMap</a> contributors'
    }).addTo(map);

    // Custom locations (latitude, longitude, name)
    var locations = [
      [39.9042, 116.4074, "Beijing"],
      [42.3601, -71.0589, "Boston, Massachusetts"],
      [37.8715, -122.2730, "Berkeley, California"],
      [22.3964, 114.1095, "Hong Kong"],
      [52.2053, 0.1218, "Cambridge, England"],
      [25.5842, 100.2257, "Dali, Yunnan"],
      [26.0745, 119.2965, "Fuzhou, Fujian"],
      [40.7128, -74.0060, "New York City"]
    ];

    // Add markers to map
    locations.forEach(function (loc) {
      L.marker([loc[0], loc[1]]).addTo(map).bindPopup("<b>" + loc[2] + "</b>");
    });
  });
</script>

 
---


## Beijing
{: #beijing }

<div class="gallery-grid">
  {% for image in site.static_files %}
    {% if image.path contains "/images/gallery/Beijing" and image.extname == ".jpg" %}
      <div class="gallery-item">
        <img src="{{ image.path | relative_url }}" alt="Beijing Image" style="width:100%; padding:5px;">
      </div>
    {% endif %}
  {% endfor %}
</div>

---

## Boston, Massachusetts
{: #boston }

<div class="gallery-grid">
  {% for image in site.static_files %}
    {% if image.path contains "/images/gallery/Boston" and image.extname == ".jpg" %}
      <div class="gallery-item">
        <img src="{{ image.path | relative_url }}" alt="Boston Image" style="width:100%; padding:5px;">
      </div>
    {% endif %}
  {% endfor %}
</div>

---

## Berkeley, California 
{: #california }

<div class="gallery-grid">
  {% for image in site.static_files %}
    {% if image.path contains "/images/gallery/California" and image.extname == ".jpg" %}
      <div class="gallery-item">
        <img src="{{ image.path | relative_url }}" alt="California Image" style="width:100%; padding:5px;">
      </div>
    {% endif %}
  {% endfor %}
</div>

---
 
## Cambridge, England
{: #cambridge }

<div class="gallery-grid">
  {% for image in site.static_files %}
    {% if image.path contains "/images/gallery/Cambridge" and image.extname == ".jpg" %}
      <div class="gallery-item">
        <img src="{{ image.path | relative_url }}" alt="Cambridge Image" style="width:100%; padding:5px;">
      </div>
    {% endif %}
  {% endfor %}
</div>


---

## Dali, Yunnan 大理 
{: #dali }

<div class="gallery-grid">
  {% for image in site.static_files %}
    {% if image.path contains "/images/gallery/Dali" and image.extname == ".jpg" %}
      <div class="gallery-item">
        <img src="{{ image.path | relative_url }}" alt="Dali Image" style="width:100%; padding:5px;">
      </div>
    {% endif %}
  {% endfor %}
</div>

---

## Fuzhou, Fujian 福州 
{: #fuzhou }

<div class="gallery-grid">
  {% for image in site.static_files %}
    {% if image.path contains "/images/gallery/Fuzhou" and image.extname == ".jpg" %}
      <div class="gallery-item">
        <img src="{{ image.path | relative_url }}" alt="Fuzhou Image" style="width:100%; padding:5px;">
      </div>
    {% endif %}
  {% endfor %}
</div>


---

## Hong Kong
{: #hongkong }

<div class="gallery-grid">
  {% for image in site.static_files %}
    {% if image.path contains "/images/gallery/HongKong" and image.extname == ".jpg" %}
      <div class="gallery-item">
        <img src="{{ image.path | relative_url }}" alt="HongKong Image" style="width:100%; padding:5px;">
      </div>
    {% endif %}
  {% endfor %}
</div>

---

## NYC, New York State
{: #ny }

<div class="gallery-grid">
  {% for image in site.static_files %}
    {% if image.path contains "/images/gallery/NY" and image.extname == ".jpg" %}
      <div class="gallery-item">
        <img src="{{ image.path | relative_url }}" alt="NY Image" style="width:100%; padding:5px;">
      </div>
    {% endif %}
  {% endfor %}
</div>

---

## Gelato
{: #gelato }
 
Meet Gelato, my short-legged Napoleon cat born on September 4, 2023. She joined my life on my 22nd birthday, February 6, 2024, and has been my little bundle of joy ever since. You can catch more of her adorable adventures on Instagram [@gelato_meowmeow](https://www.instagram.com/gelato_meowmeow).

 

<div class="gallery-grid">
  {% for image in site.static_files %}
    {% if image.path contains "/images/gallery/Gelato" and image.extname == ".jpg" %}
      <div class="gallery-item">
        <img src="{{ image.path | relative_url }}" alt="Gelato Image" style="width:100%; padding:5px;">
      </div>
    {% endif %}
  {% endfor %}
</div>

