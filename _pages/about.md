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
 
My research interests lie at the intersection of **economic geography**, **urban economics**, and **development studies**. I focus on two key areas. First, I explore how political structures and governance at various spatial scales shape policies and practices that affect intergenerational inequality. This includes examining how spatial planning and regional development strategies can either mitigate or reinforce disparities, as well as how institutional mechanisms influence mobility and the welfare of future generations. Second, I investigate how the quality and extent of social networks and spatial frictions shape urban evolution, and their implications for economic development.


My first name is pronounced rway-ee.



<div class="two-col">

<div markdown="1">

## Interests
Urban Evolution  

Regional Development   
</div>

<div markdown="1">
 
## Education
PhD in Geography, The University of Hong Kong <span class="time">(2025–Present)</span>    

Bachelor of Economics, The University of Hong Kong <span class="time">(2021–2025)</span>  
 
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
.time {
  color: #587998;    
  font-weight: normal;
}
</style>


 
 <br>
 
 {: #contact } 
<script type="text/javascript">
  var user = "ruiyi";
  var domain = "connect.hku.hk";
  document.write('Please contact me at <a href="mailto:' + user + '@' + domain + '">' + user + '@' + domain + '</a>.');
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
  <summary markdown="span">**Declining Population and Endogenous Growth: Evidence from Developed Economies**</summary>
  <div markdown="1">
  This coursework paper develops a framework that integrates Becker’s dynastic fertility theory with the Uzawa–Lucas approach to endogenous growth. The framework predicts that diminishing returns to human capital accumulation eventually induce a reallocation of factors toward a more efficient configuration, allowing economies to sustain per-capita output growth over time even under negative population growth. Using the system GMM estimator and panel data for 43 developed countries over 1970-2019, this endogenous mechanism of human capital accumulation sustaining economic growth is investigated by examining the relationship between human capital, the estimated rate of increasing returns to education, output growth, and population growth. The empirical evidence is consistent with the theoretical results.
  </div>
</details>

<details class="proj">
  <summary markdown="span">**Building Knowledge Graphs from Classical Chinese Manuscripts with LLMs** <em>(in progress)</em></summary>
  <div markdown="1">
  This project develops a framework for digitizing and extracting structured knowledge from historical Chinese texts written in *wenyan* (Classical Chinese). It seeks to integrate digitization, character normalization, and punctuation restoration with fine-tuned large language models to achieve accurate interpretation of unpunctuated, context-dependent passages. The models are being trained to handle tasks including named entity recognition, event extraction, and relational mapping, with the goal of transforming raw manuscripts into structured knowledge graphs that capture the people, places, events, and institutions recorded in the texts. Ultimately, the project aims to enable semantic querying of complex historical records and to provide historians with a powerful tool for detecting patterns, validating interpretations, and linking disparate archival sources within a unified digital knowledge base.
  </div>
</details>
 
  
<style>
.proj{ margin:.5rem 0 1rem; }
.proj > summary{ cursor:pointer; font-weight:600; list-style:none; }
.proj > summary::-webkit-details-marker{ display:none; }
.proj > summary::after{ content:" ▸"; color:#666; }
details[open] > summary::after{ content:" ▾"; }

/* If your theme injects anchor icons into headings/summary, hide them inside details */
.proj summary .anchorjs-link { display:none !important; }
</style>



   
 






# Software 
 {: #software }

[**causalSenseCheck**](https://github.com/yryrena/causalSenseCheck) is an R package that provides a unified toolkit for researchers interested in evaluating the credibility of causal claims. It integrates a variety of diagnostic approaches, including placebo checks, robustness analyses, sensitivity methods, and multiple estimators, within a single, coherent workflow. The package is designed to make rigorous causal inference diagnostics more accessible. With clear syntax, intuitive visualizations, and automated reporting features, the package helps researchers assess the stability of their results, identify potential weaknesses, and present findings in a transparent and reproducible way.


