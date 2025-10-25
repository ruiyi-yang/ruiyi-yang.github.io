---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
layout: single
classes: wide
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span> 
 


My first name is pronounced rway-ee.
 
 {: #contact } 
<script type="text/javascript">
  var user = "ruiyi";
  var domain = "connect.hku.hk";
  document.write('Please contact me at <a href="mailto:' + user + '@' + domain + '">' + user + '@' + domain + '</a>.');
</script>






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
Urban Evolution  

Economic Development

Regional Political Economy

Computational Social Science

</div>
</div>
 
<style>
.two-col{
  display:flex;
  gap:2rem;
  align-items:flex-start;
  flex-wrap:wrap;      
  margin-top:1rem;
}
.two-col > div{
  flex:1 1 320px;   
}
.school {
  color: #bebebe;    
  font-weight: normal;
}
</style>



  

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
 



# Projects
 {: #projects }

<details class="proj">
  <summary markdown="span">**Governance Fragmentation and the Tragedy of the Commons: A Spatial Econometric Analysis of Groundwater Extraction in the U.S.**</summary>
  <div markdown="1">
  This paper investigates how governance fragmentation affects groundwater extraction in the United States, drawing on the broader literature on the "tragedy of the commons” and institutional design. The study develops a game-theoretic framework that models how neighboring jurisdictions compete or cooperate in shared resource extraction. Simulation results demonstrate that when governance is more evenly fragmented, competition intensifies, leading to higher extraction and resource depletion; conversely, highly asymmetric governance arrangements reduce over-extraction. The model also highlights the importance of intertemporal preferences in shaping extraction outcomes. From this theoretical basis, two testable hypotheses are proposed: (i) higher fragmentation increases groundwater withdrawal, and (ii) extraction decisions are spatially interdependent across districts. Empirically, the paper applies spatial econometric techniques to U.S. groundwater data. Using constructed proxies for governance fragmentation and extensive controls for geological, demographic, and land-use factors, the analysis reveals a complex picture: fragmentation heightens perceived scarcity but is associated with lower actual extraction. Strong spatial dependence is observed, confirming that districts’ decisions are influenced by their neighbors. Robustness checks, including PSM and alternative spatial weighting schemes, reinforce the main findings.
  </div>
</details>


<details class="proj">
  <summary markdown="span">**Building Knowledge Graphs from Classical Chinese Manuscripts with LLMs** <em>(in progress)</em></summary>
  <div markdown="1">
  This project develops a framework for digitizing and extracting structured knowledge from historical Chinese texts written in *wenyan* (Classical Chinese). It seeks to integrate digitization, character normalization, and punctuation restoration with fine-tuned large language models to achieve accurate interpretation of unpunctuated, context-dependent passages. The models are being trained to handle tasks including named entity recognition, event extraction, and relational mapping, with the goal of transforming raw manuscripts into structured knowledge graphs that capture the people, places, events, and institutions recorded in the texts. Ultimately, the project aims to enable semantic querying of complex historical records and to provide historians with a powerful tool for detecting patterns, validating interpretations, and linking disparate archival sources within a unified digital knowledge base.
  </div>
</details>
 
  
<style>
.proj { margin:.5rem 0 1rem; }

.proj > summary {
  cursor:pointer;
  font-weight:600;
  list-style:none;
  display:flex;               /* icon sits before the text */
  align-items:center;
  gap:.5rem;                  /* space between icon and title */
}

/* hide native markers */
.proj > summary::marker { content:""; }                  /* Firefox */
.proj > summary::-webkit-details-marker { display:none; } /* Chrome/Safari */

/* plus/minus at the FRONT */
.proj > summary::before { content:"+"; color:#666; font-weight:bold; }
details[open] > summary::before { content:"−"; } /* note: real minus sign, not hyphen */

/* if your theme injects anchor icons into summary, hide them */
.proj summary .anchorjs-link { display:none !important; }
</style>






   
 






# Software & Tools 
 {: #software }

[**causalSenseCheck**](https://github.com/yryrena/causalSenseCheck) is an R package that provides a toolkit for researchers interested in evaluating the credibility of causal claims. It integrates a variety of diagnostic approaches, including placebo checks, robustness analyses, sensitivity methods, and multiple estimators, within a single, coherent workflow. The package is designed to make rigorous causal inference diagnostics more accessible. With clear syntax, intuitive visualizations, and automated reporting features, the package helps researchers stress-test their results, identify potential weaknesses, and present findings in a transparent and reproducible way.
 
Many forecasting errors start with messy inputs. [**timeSeriesQC**](https://github.com/yryrena/timeSeriesQC) tackles that directly: given panel/long time series, it detects irregularities (duplicates, gaps, outliers), highlights seasonal artifacts and breakpoints, and, when requested, applies reproducible fixes. Each operation is logged, and a lightweight HTML report captures what changed and why. The package is intentionally narrow in scope: prepare reliable time-series inputs, then hand off to your modeling stack.

[**historical_map_georef**](https://github.com/yryrena/historical_map_georef) is a lightweight pipeline for georeferencing scanned historical maps with printed graticules (longitude/latitude grids). The workflow guides users through interactively selecting ground control points, warping rasters via thin-plate spline transformation, and exporting results as georeferenced GeoTIFFs, static PNGs, or interactive Leaflet maps. 
 
[**OCRFlow**](https://github.com/yryrena/OCRFlow) is a toolkit for automating the digitization of scanned documents. It streamlines the full workflow from image cleaning and binarization to intelligent column segmentation and OCR, within a reproducible pipeline. The toolkit supports both batch and single-image processing, integrating deep learning–based OCR models with classic computer vision preprocessing. The result is a flexible system that converts complex multi-column scans into structured, machine-readable text, ready for search, analysis, or archiving.


