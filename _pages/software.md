---
layout: default
permalink: /software/
title: "Software & Tools"
author_profile: true
---

# Software & Tools  

<!-- causalSenseCheck -->
<section style="display:flex; align-items:center; justify-content:space-between; flex-wrap:wrap; margin-bottom:2rem;">
  <div style="flex:1; min-width:250px; padding-right:1rem;">
    <p>
      <a href="https://github.com/yryrena/causalSenseCheck"><strong>causalSenseCheck</strong></a> is an R package that provides a toolkit for researchers interested in evaluating the credibility of causal claims. It integrates a variety of diagnostic approaches, including placebo checks, robustness analyses, sensitivity methods, and multiple estimators, within a single, coherent workflow. The package is designed to make rigorous causal inference diagnostics more accessible. With clear syntax, intuitive visualizations, and automated reporting features, the package helps researchers stress-test their results, identify potential weaknesses, and present findings in a transparent and reproducible way.
    </p>
  </div>
  <div style="flex:0 0 140px; text-align:right;">
    <img src="{{ '/images/causalSenseCheck_hex.png' | relative_url }}"
         alt="causalSenseCheck logo"
         style="width:130px; max-width:130px; height:auto; border-radius:10px; box-shadow:0 0 10px rgba(0,0,0,0.15);" />
  </div>
</section>

<hr style="border:none; border-top:1px solid #ddd; margin:1.5rem 0;" />

<!-- timeSeriesQC -->
<section style="display:flex; align-items:center; justify-content:space-between; flex-wrap:wrap; margin-bottom:2rem;">
  <div style="flex:1; min-width:250px; padding-right:1rem;">
    <p>
      Many forecasting errors start with messy inputs.
      <a href="https://github.com/yryrena/timeSeriesQC"><strong>timeSeriesQC</strong></a>
      tackles that directly: given panel/long time series, it detects irregularities (duplicates, gaps, outliers), highlights seasonal artifacts and breakpoints, and, when requested, applies reproducible fixes. Each operation is logged, and a lightweight HTML report captures what changed and why. The package is intentionally narrow in scope: prepare reliable time-series inputs, then hand off to your modeling stack.
    </p>
  </div>
  <div style="flex:0 0 140px; text-align:right;">
    <img src="{{ '/images/timeSeriesQC_hex.png' | relative_url }}"
         alt="timeSeriesQC logo"
         style="width:130px; max-width:130px; height:auto; border-radius:10px; box-shadow:0 0 10px rgba(0,0,0,0.15);" />
  </div>
</section>

<hr style="border:none; border-top:1px solid #ddd; margin:1.5rem 0;" />

<!-- historical_map_georef -->
<section style="display:flex; align-items:center; justify-content:space-between; flex-wrap:wrap; margin-bottom:2rem;">
  <div style="flex:1; min-width:250px; padding-right:1rem;">
    <p>
      <a href="https://github.com/yryrena/historical_map_georef"><strong>historical_map_georef</strong></a>
      is a lightweight pipeline for georeferencing scanned historical maps with printed graticules (longitude/latitude grids). The workflow guides users through interactively selecting ground control points, warping rasters via thin-plate spline transformation, and exporting results as georeferenced GeoTIFFs, static PNGs, or interactive Leaflet maps.
    </p>
  </div>
  <div style="flex:0 0 140px; text-align:right;">
    <img src="{{ '/images/historical_map_georef_hex.png' | relative_url }}"
         alt="historical_map_georef logo"
         style="width:130px; max-width:130px; height:auto; border-radius:10px; box-shadow:0 0 10px rgba(0,0,0,0.15);" />
  </div>
</section>

<hr style="border:none; border-top:1px solid #ddd; margin:1.5rem 0;" />

<!-- OCRFlow -->
<section style="display:flex; align-items:center; justify-content:space-between; flex-wrap:wrap; margin-bottom:2rem;">
  <div style="flex:1; min-width:250px; padding-right:1rem;">
    <p>
      <a href="https://github.com/yryrena/OCRFlow"><strong>OCRFlow</strong></a>
      is a toolkit for automating the digitization of scanned documents. It streamlines the full workflow from image cleaning and binarization to intelligent column segmentation and OCR, within a reproducible pipeline. The toolkit supports both batch and single-image processing, integrating deep learning–based OCR models with classic computer vision preprocessing. The result is a flexible system that converts complex multi-column scans into structured, machine-readable text, ready for search, analysis, or archiving.
    </p>
  </div>
  <div style="flex:0 0 140px; text-align:right;">
    <img src="{{ '/images/OCRFlow_hex.png' | relative_url }}"
         alt="OCRFlow logo"
         style="width:130px; max-width:130px; height:auto; border-radius:10px; box-shadow:0 0 10px rgba(0,0,0,0.15);" />
  </div>
</section>

