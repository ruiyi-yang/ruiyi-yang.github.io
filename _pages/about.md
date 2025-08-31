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
 
My research interests lie at the intersection of **Development Economics**, **Spatial Interaction**, and **Political Geography**. I focus on two key areas. First, I explore how political structures and governance at various spatial scales shape policies and practices that affect intergenerational inequality. This includes examining how spatial planning and regional development strategies can either mitigate or reinforce disparities, as well as how institutional mechanisms influence mobility and the welfare of future generations. Second, I investigate how the quality and extent of social networks shape urban dynamics, with implications for neighborhood formation and economic growth.


My first name is pronounced rway-ee.

 
## Degree Education
- *2021.09 - 2025.06*, Bachelor of Economics, The University of Hong Kong.  

 
{: #contact } 
<script type="text/javascript">
  var user = "ruiyi";
  var domain = "connect.hku.hk";
  document.write('Please contact me at <a href="mailto:' + user + '@' + domain + '">' + user + '@' + domain + '</a>.');
</script>



# Projects
 {: #projects }

**Governance Fragmentation and the Tragedy of the Commons: A Spatial Econometric Analysis of Groundwater Extraction in the U.S.**

**Declining Population and Endogenous Growth: Evidence from Dynamic Panel Data of Developed Economies**

**From Manuscript to Knowledge Graph: LLMs for Classical Chinese Texts** *(in progress)*
 


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

 



<div class="gallery-menu">
  <ul>
    <li><a href="#beijing">Beijing</a></li>
    <li><a href="#california">Berkeley</a></li>
    <li><a href="#boston">Boston</a></li>
    <li><a href="#cambridge">Cambridge</a></li>
    <li><a href="#dali">Dali</a></li>
    <li><a href="#fuzhou">Fuzhou</a></li>
    <li><a href="#hongkong">Hong Kong</a></li>
    <li><a href="#samui">Samui</a></li>
    <li><a href="#ny">NYC</a></li>
    <li><a href="#newzealand">New Zealand</a></li>
    <li><a href="#xinjiang">Xinjiang</a></li>
    <li><a href="#gelato">Gelato 🐈</a></li> 
  </ul>
</div>
  
  
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
      [-40.9006, 174.8860, "New Zealand"],
      [42.3601, -71.0589, "Boston, Massachusetts"],
      [37.8715, -122.2730, "Berkeley, California"],
      [22.3964, 114.1095, "Hong Kong"],
      [52.2053, 0.1218, "Cambridge, England"],
      [25.5842, 100.2257, "Dali, Yunnan"],
      [26.0745, 119.2965, "Fuzhou, Fujian"],
      [40.7128, -74.0060, "New York City"], 
      [9.5120, 100.0136, "Ko Samui, Surat Thani"],
      [43.7934, 87.6271, "Xinjiang"]
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
 
## Cambridge, England
{: #cambridge }

<div class="gallery-grid">
  {% for image in site.static_files %}
    {% if image.path contains "/images/gallery/Cambridge" and image.extname == ".JPG" %}
      <div class="gallery-item">
        <img src="{{ image.path | relative_url }}" alt="Cambridge Image" style="width:100%; padding:5px;">
      </div>
    {% endif %}
  {% endfor %}
</div>


---

## Dali, Yunnan  
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

## Fuzhou, Fujian   
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

## Ko Samui District, Surat Thani, Thailand
{: #samui }

<div class="gallery-grid">
  {% for image in site.static_files %}
    {% if image.path contains "/images/gallery/Samui" and image.extname == ".jpg" %}
      <div class="gallery-item">
        <img src="{{ image.path | relative_url }}" alt="samui Image" style="width:100%; padding:5px;">
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

## New Zealand
{: #newzealand }

<div class="gallery-grid">
  {% for image in site.static_files %}
    {% if image.path contains "/images/gallery/NewZealand" and image.extname == ".jpg" %}
      <div class="gallery-item">
        <img src="{{ image.path | relative_url }}" alt="NewZealand Image" style="width:100%; padding:5px;">
      </div>
    {% endif %}
  {% endfor %}
</div>

---

## Xinjiang
{: #xinjiang }

<div class="gallery-grid">
  {% for image in site.static_files %}
    {% if image.path contains "/images/gallery/Xinjiang" and image.extname == ".jpg" %}
      <div class="gallery-item">
        <img src="{{ image.path | relative_url }}" alt="Xinjiang Image" style="width:100%; padding:5px;">
      </div>
    {% endif %}
  {% endfor %}
</div>

---

## Gelato
{: #gelato }

<div class="gallery-grid">
  {% for image in site.static_files %}
    {% if image.path contains "/images/gallery/Gelato" and image.extname == ".jpg" %}
      <div class="gallery-item">
        <img src="{{ image.path | relative_url }}" alt="Gelato Image" style="width:100%; padding:5px;">
      </div>
    {% endif %}
  {% endfor %}
</div>





