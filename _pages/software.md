

# Software & Tools

 {: #software }

[**causalSenseCheck**](https://github.com/yryrena/causalSenseCheck) is an R package that provides a toolkit for researchers interested in evaluating the credibility of causal claims. It integrates a variety of diagnostic approaches, including placebo checks, robustness analyses, sensitivity methods, and multiple estimators, within a single, coherent workflow. The package is designed to make rigorous causal inference diagnostics more accessible. With clear syntax, intuitive visualizations, and automated reporting features, the package helps researchers stress-test their results, identify potential weaknesses, and present findings in a transparent and reproducible way.
 
Many forecasting errors start with messy inputs. [**timeSeriesQC**](https://github.com/yryrena/timeSeriesQC) tackles that directly: given panel/long time series, it detects irregularities (duplicates, gaps, outliers), highlights seasonal artifacts and breakpoints, and, when requested, applies reproducible fixes. Each operation is logged, and a lightweight HTML report captures what changed and why. The package is intentionally narrow in scope: prepare reliable time-series inputs, then hand off to your modeling stack.

[**historical_map_georef**](https://github.com/yryrena/historical_map_georef) is a pipeline for georeferencing scanned historical maps with printed graticules (longitude/latitude grids). The workflow guides users through interactively selecting ground control points, warping rasters via thin-plate spline transformation, and exporting results as georeferenced GeoTIFFs, static PNGs, or interactive Leaflet maps. 
