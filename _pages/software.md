---
layout: default
permalink: /software/
title: "Software & Tools"
author_profile: true
---

# Software & Tools

[**causalSenseCheck**](https://github.com/yryrena/causalSenseCheck) is an R package that provides a toolkit for researchers interested in evaluating the credibility of causal claims. It integrates a variety of diagnostic approaches, including placebo checks, robustness analyses, sensitivity methods, and multiple estimators, within a single, coherent workflow. The package is designed to make rigorous causal inference diagnostics more accessible. With clear syntax, intuitive visualizations, and automated reporting features, the package helps researchers stress-test their results, identify potential weaknesses, and present findings in a transparent and reproducible way.
 
Many forecasting errors start with messy inputs. [**timeSeriesQC**](https://github.com/yryrena/timeSeriesQC) tackles that directly: given panel/long time series, it detects irregularities (duplicates, gaps, outliers), highlights seasonal artifacts and breakpoints, and, when requested, applies reproducible fixes. Each operation is logged, and a lightweight HTML report captures what changed and why. The package is intentionally narrow in scope: prepare reliable time-series inputs, then hand off to your modeling stack.

[**historical_map_georef**](https://github.com/yryrena/historical_map_georef) is a lightweight pipeline for georeferencing scanned historical maps with printed graticules (longitude/latitude grids). The workflow guides users through interactively selecting ground control points, warping rasters via thin-plate spline transformation, and exporting results as georeferenced GeoTIFFs, static PNGs, or interactive Leaflet maps. 

<div class="mermaid">flowchart LR
    A["Scanned Map Input"] --> B["Pick Ground Control Points"]
    B --> C["Save GCPs"]
    C --> D["Warp Raster with Thin Plate Spline"]
    D --> E["GeoTIFF & Visualization Exports"]
    E --> F["Optional Extract Blue Contours GeoJSON"]
</div>



[**OCRFlow**](https://github.com/yryrena/OCRFlow) is a toolkit for automating the digitization of scanned documents. It streamlines the full workflow from image cleaning and binarization to intelligent column segmentation and OCR, within a reproducible pipeline. The toolkit supports both batch and single-image processing, integrating deep learning–based OCR models with classic computer vision preprocessing. The result is a flexible system that converts complex multi-column scans into structured, machine-readable text, ready for search, analysis, or archiving.
