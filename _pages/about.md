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
  


# Educations 
- *2025.09 - 2027.06*, M.Phil. in Geography, The University of Hong Kong. 
- *2021.09 - 2025.06*, Bachelor of Economics, The University of Hong Kong. 
  - HKU Worldwide Student Exchange Scholarships, C.V. Starr Scholarship, Dean’s Honours Lists



 

---

# Gallery
{: #gallery }

<style>
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

## Boston
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

## California
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

## Dali, Yunnan Province 大理 
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

## Fuzhou, Fujian Province 福州 
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
