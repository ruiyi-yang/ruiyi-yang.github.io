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


## Degree Education
<div style="display: flex; justify-content: space-between; gap: 40px; flex-wrap: wrap;">

  <!-- Left column -->
  <div style="flex: 1; min-width: 250px;">
    <h3>Interests</h3>
    <ul>
      <li>Development Economics</li>
      <li>Spatial Interaction</li>
      <li>Economic Geography</li>
    </ul>
  </div>

  <!-- Right column -->
  <div style="flex: 1; min-width: 250px;">
    <h3>Education</h3>
    <ul style="list-style-type: none; padding-left: 0;">
      <li>🎓 <em>2025.11 - Present<em>, <strong>PhD in Geography</strong>, The University of Hong Kong</li> 
      <li>🎓 <em>2021.09 - 2025.06<em>, <strong>Bachelor of Economics</strong>, The University of Hong Kong</li>
    </ul>
  </div>

</div>


# Projects
 {: #projects }

**Governance Fragmentation and the Tragedy of the Commons: A Spatial Econometric Analysis of Groundwater Extraction in the U.S.**  

This paper investigates how governance fragmentation affects groundwater extraction in the United States, drawing on the broader literature on the "tragedy of the commons” and institutional design. The study develops a game-theoretic framework that models how neighboring jurisdictions compete or cooperate in shared resource extraction. Simulation results demonstrate that when governance is more evenly fragmented, competition intensifies, leading to higher extraction and resource depletion; conversely, highly asymmetric governance arrangements reduce over-extraction. The model also highlights the importance of intertemporal preferences in shaping extraction outcomes. From this theoretical basis, two testable hypotheses are proposed: (i) higher fragmentation increases groundwater withdrawal, and (ii) extraction decisions are spatially interdependent across districts. Empirically, the paper applies spatial econometric techniques to U.S. groundwater data. Using constructed proxies for governance fragmentation and extensive controls for geological, demographic, and land-use factors, the analysis reveals a complex picture: fragmentation heightens perceived scarcity but is associated with lower actual extraction. Strong spatial dependence is observed, confirming that districts’ decisions are influenced by their neighbors. Robustness checks, including PSM and alternative spatial weighting schemes, reinforce the main findings.


**Declining Population and Endogenous Growth: Evidence from Developed Economies**  

This coursework paper develops a framework that integrates Becker’s dynastic fertility theory with the Uzawa–Lucas approach to endogenous growth. The framework predicts that diminishing returns to human capital accumulation eventually induce a reallocation of factors toward a more efficient configuration, allowing economies to sustain per-capita output growth over time even under negative population growth. Using the system GMM estimator and panel data for 43 developed countries over 1970-2019, this endogenous mechanism of human capital accumulation sustaining economic growth is investigated by examining the relationship between human capital, the estimated rate of increasing returns to education, output growth, and population growth. The empirical evidence is consistent with the theoretical results.

**Building Knowledge Graphs from Classical Chinese Manuscripts with LLMs** *(in progress)*

This project develops a framework for digitizing and extracting structured knowledge from historical Chinese texts written in *wenyan* (Classical Chinese). It seeks to integrate digitization, character normalization, and punctuation restoration with fine-tuned large language models to achieve accurate interpretation of unpunctuated, context-dependent passages. The models are being trained to handle tasks including named entity recognition, event extraction, and relational mapping, with the goal of transforming raw manuscripts into structured knowledge graphs that capture the people, places, events, and institutions recorded in the texts. Ultimately, the project aims to enable semantic querying of complex historical records and to provide historians with a powerful tool for detecting patterns, validating interpretations, and linking disparate archival sources within a unified digital knowledge base.
