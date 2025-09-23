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
  This coursework paper develops a framework that integrates Becker’s dynastic fertility theory with the Uzawa–Lucas model of endogenous growth. The framework predicts that diminishing returns to human capital accumulation eventually induce a reallocation of factors toward a more efficient configuration, enabling economies to sustain per-capita output growth even under conditions of demographic decline. To test this mechanism, I employ system GMM estimators on panel data from 43 developed economies over the period 1970–2019, examining the dynamic relationship between human capital accumulation, the estimated rate of increasing returns to education, output growth, and population trends. The empirical results are consistent with the theoretical predictions, suggesting that this endogenous mechanism of human capital accumulation has the potential to mitigate the growth-reducing effects of negative population growth. 
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





