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

I am a first-year PhD student in the Faculty of Social Sciences at The University of Hong Kong. I earned a Bachelor’s degree in Economics <span style="color:#888888;">(First Class Honours)</span> from HKU’s Faculty of Business and Economics. My research interests lie at the intersection of **spatial economics** and **development studies**. 


My first name is pronounced rway-ee.
 





<div class="two-col">

<div markdown="1">

## Education
PhD in Geography, 2025–Present  
&nbsp;<span class="school">The University of Hong Kong</span>  

Bachelor of Economics, 2021–2025  
&nbsp;<span class="school">The University of Hong Kong</span>  

</div>

<div markdown="1">
 
## Research Interests

Economic Geography and Development

Spatial Networks and Urban Economics

Regional Political Economy

</div>
</div>





 
<style>
.two-col{
  display:flex;
  gap:2rem;
  align-items:flex-start;
  flex-wrap:wrap;      
  margin-top:2.5rem;
}
.two-col > div{
  flex:1 1 320px;   
}
.school {
  color: #bebebe;    
  font-weight: normal;
}
</style>





 {: #contact } 
<script type="text/javascript">
  var user = "ruiyi";
  var domain = "connect.hku.hk";
  document.write('Please contact me at <a href="mailto:' + user + '@' + domain + '">' + user + '@' + domain + '</a>.');
</script>


  

--- 
<link rel="stylesheet" href="https://unpkg.com/leaflet@1.9.4/dist/leaflet.css"> 
<div id="map" style="width:100%;height:300px;border-radius:8px;margin:1rem 0;background:#eee;"></div> 
<script>
  const map = L.map('map', { scrollWheelZoom: false })
               .setView([22.283, 114.137], 15);

  map.attributionControl.setPrefix('');

  // Stadia OSM Bright: osm_bright; Stadia watercolor: stamen_watercolor
  L.tileLayer(
    'https://tiles.stadiamaps.com/tiles/stamen_watercolor/{z}/{x}/{y}{r}.png?api_key=043d3228-23e1-4525-8324-ce817b4f940e',
    {
      maxZoom: 18, 
      detectRetina: true,
      attribution:
      '© <a href="https://stadiamaps.com/">Stadia Maps</a>, ' +
      '© <a href="https://openmaptiles.org/">OpenMapTiles</a> ' +
      '© <a href="https://www.openstreetmap.org/copyright">OpenStreetMap</a> contributors'
    }
  ).addTo(map);

  L.marker([22.284,114.136]).addTo(map)
    .bindPopup('<b>The University of Hong Kong</b><br>Pok Fu Lam, Hong Kong')
    .openPopup();
</script>
