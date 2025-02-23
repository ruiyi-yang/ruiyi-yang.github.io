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
 
My research interests lie at the intersection of **Development Economics**, **Spatial Interaction**, and **Political Geography**. I focus on two key areas. First, I explore how political structures and governance at various spatial scales shape policies and practices that affect intergenerational inequality. This includes examining how spatial planning and regional development strategies can either mitigate or reinforce disparities, as well as how institutional mechanisms influence mobility and the welfare of future generations. Second, I investigate how the quality and extent of social networks shape urban dynamics—with implications for neighborhood formation, segregation, and economic growth.

My first name is pronounced rway-ee.

 
## Degree Educations  
- *2021.09 - 2025.06*, Bachelor of Economics, The University of Hong Kong.  

## International Studies
- *2024.06 - 2024.08*, Johns Hopkins University.
- *2023.09 - 2023.12*, Tufts University. 
- *2023.02 - 2023.05*, University of California, Berkeley. 
- *2022.07 - 2022.08*, Pembroke College, University of Cambridge. 



# Contact
 {: #contact }
Please contact me at ruiyi_yang[at]connect.hku.hk.



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
      [9.5120, 100.0136, "Ko Samui, Surat Thani"]
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

## Gelato
{: #gelato }
 
Meet Gelato (雪糕), my short-legged Napoleon cat born on September 4, 2023. She joined my life on my 22nd birthday and has been my little bundle of joy ever since. You can catch more of her adorable adventures on her Instagram account [@gelato_meowmeow](https://www.instagram.com/gelato_meowmeow).

 

<div class="gallery-grid">
  {% for image in site.static_files %}
    {% if image.path contains "/images/gallery/Gelato" and image.extname == ".jpg" %}
      <div class="gallery-item">
        <img src="{{ image.path | relative_url }}" alt="Gelato Image" style="width:100%; padding:5px;">
      </div>
    {% endif %}
  {% endfor %}
</div>







# Reading  
{: #reading }


## Reading Group | The Weight of the World: Fate, Marginality, and the Search for Meaning

*We are the entropy of the world, forever bound by the gravity of our being.*

In this reading group, we will explore how literature captures the tension between individual agency and the vast, inescapable forces of history and society. Through novels, poetry, philosophy, and social criticism, we will examine the weight of existence, the marginalization of certain voices, and our place in an ever-shifting world. By engaging with diverse perspectives, we will reflect on how stories—both real and imagined—shape our understanding of fate, identity, and the struggle for meaning.

##### Week 1: Entropy, the Everyday, and the Marginalized Figures of History

##### Week 2: The Weight of the Past and the Fiction of Reality

##### **Week 3: Gender and Power—Tangled Structures of the Patriarchy**

##### Week 4: The Masses, the Individual, and the Struggle for Meaning

##### Week 5: Ethics, Altruism, and Repairing the World

##### Week 6: Mythology, Artificial Beings, and the Fear of Creation

##### Week 7: The Education of the Self—Art, Teaching, and the Search for Meaning

##### Week 8: Facing Extinction—Humanity, Nature, and the Future


---

## Reading Group | Global Prioritization and Effective Altruism

This reading group explores global prioritization—the systematic identification and evaluation of the world’s most pressing problems—through the lens of Effective Altruism. Using foundational and applied research, we will investigate how individuals, philanthropists, and policymakers can allocate resources to maximize social impact.

##### Session 1: Introduction to Global Prioritization and Effective Altruism

##### Session 2: Strategic Issues in Altruistic Decision-Making

##### Session 3: Forecasting and Long-Term Impact

##### Session 4: Welfare and Decision Procedures in Prioritization

##### Session 5: Evidence, Cost-Effectiveness, and Marginal Impact

##### Session 6: Catastrophic Risks and Global Prioritization

##### Session 7: AI, Technological Change, and Global Prioritization

##### Session 8: Population, Inequality, and Intergenerational Governance

##### Session 9: Policy-Making for Long-Term Global Prioritization

##### Session 10: Critiques and Open Questions in Global Prioritization


---

## Reading Group | **High-Impact Social Innovation: Charity Entrepreneurship & Effective Altruism**

This reading group explores the intersection of charity entrepreneurship, social innovation, and Effective Altruism—examining how evidence-based strategies can create and scale high-impact organizations. Participants will engage with key ideas, frameworks, and case studies to understand how to apply rigorous reasoning to solving global problems.

##### **Session 1: Introduction to Effective Altruism & Social Innovation**

##### **Session 2: Charity Entrepreneurship – A Framework for Impact**

##### **Session 3: Cause Prioritization & Problem Selection**

##### **Session 4: Innovation in Global Health & Development**

##### **Session 5: Longtermism & Social Innovation for Future Generations**

##### **Session 6: Effective Giving & Venture Philanthropy**

##### **Session 7: Scaling Social Ventures & Measuring Impact**

##### Session 8: Critiques of EA & The Future of Social Innovation

 
