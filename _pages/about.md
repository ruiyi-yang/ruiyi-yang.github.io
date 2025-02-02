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
- *2025.09 - 2027.06*, M.Phil. in Geography, The University of Hong Kong. 
- *2021.09 - 2025.06*, Bachelor of Economics, The University of Hong Kong. 
  - HKU Worldwide Student Exchange Scholarships, C.V. Starr Scholarship, Dean’s Honours Lists
  - Student Ambassador, Asia Global Institute  (2022-2023) 

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
</style>

 
<div class="gallery-menu">
  <ul>
    <li><a href="#beijing">Beijing</a></li>
    <li><a href="#boston">Boston, Massachusetts</a></li>
    <li><a href="#california">California</a></li>
    <li><a href="#dali">Dali, Yunnan Province</a></li>
    <li><a href="#fuzhou">Fuzhou, Fujian Province</a></li>
    <li><a href="#hongkong">Hong Kong</a></li>
    <li><a href="#ny">New York</a></li>
  </ul>
</div>

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

## New York
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

<div class="gallery-grid">
  {% for image in site.static_files %}
    {% if image.path contains "/images/gallery/Gelato" and image.extname == ".jpg" %}
      <div class="gallery-item">
        <img src="{{ image.path | relative_url }}" alt="Gelato Image" style="width:100%; padding:5px;">
      </div>
    {% endif %}
  {% endfor %}
</div>

