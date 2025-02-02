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

My research interests include Urban Development, Economic Geography, and Social Networks and Interactions. 
  


# Educations 
- *2025.09 - 2027.06*, M.Phil. in Geography, The University of Hong Kong. 
- *2021.09 - 2025.06*, Bachelor of Economics, The University of Hong Kong. 

# Honors and Awards
- HKU Worldwide Student Exchange Scholarships
- C.V. Starr Scholarship
- Dean’s Honours Lists

 

---

# Gallery
{: #gallery }


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
