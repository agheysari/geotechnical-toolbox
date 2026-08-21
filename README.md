# 🌍 Open-Source Geotechnical Engineering & Geospatial Calculators

A comprehensive collection of **25+ standalone, client-side HTML/JavaScript calculation tools and utilities** for geotechnical engineers, civil engineering researchers, and geospatial analysts.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Calculators](https://img.shields.io/badge/Calculators-25%2B-blue.svg)](https://github.com/agheysari/geotechnical-tools)
[![Support](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-Donate-orange.svg)](https://buymeacoffee.com/agheysari)

---

## ⚡ Key Features

* **100% Client-Side:** No server execution or backend required; run directly in any modern web browser or host on GitHub Pages.
* **Metric (SI) & Imperial (US) Unit Support:** Instant real-time unit conversions with automatic parameter scaling.
* **Interactive Visualizations:** Canvas/SVG charts (Boussinesq stress isobars, P-y curves, 2:1 stress dispersion, Hoek-Brown failure envelopes, particle size distribution).
* **Easy Embedding:** Clean standalone HTML structures ready to be integrated into portals, educational courses, or intranet sites.

---

## 📚 Included Calculation Modules

| # | Calculator Module | Filename | Key Methods / Theories |
|---|-------------------|----------|------------------------|
| 1 | **Axial Pile Capacity** | [`axial_pile_capacity.html`](./axial_pile_capacity.html) | Alpha (API RP 2A), Beta (Burland), Lambda (Vijayvergiya & Focht) |
| 2 | **Pile Group Efficiency & Settlement** | [`pile_group_efficiency.html`](./pile_group_efficiency.html) | Converse-Labarre, Sayed-Baker, Cohesive Block Shear, 2:1 Raft Model |
| 3 | **Shallow Bearing Capacity** | [`bearing_capacity.html`](./bearing_capacity.html) | Terzaghi, Meyerhof, Hansen, Vesic General Formulations |
| 4 | **Lateral Pile P-y Curves** | [`lateral_pile_py_curves.html`](./lateral_pile_py_curves.html) | Matlock (1970) Soft Clay, API RP 2A Sand |
| 5 | **Lateral Earth Pressure** | [`earth_pressure.html`](./earth_pressure.html) | Rankine & Coulomb Theories (Ka, Kp, Ko, Surcharge) |
| 6 | **Cantilever Retaining Wall Stability** | [`retaining_wall_stability.html`](./retaining_wall_stability.html) | Sliding, Overturning, Base Contact & Eccentricity Checks |
| 7 | **1D Consolidation Settlement** | [`consolidation_calculator.html`](./consolidation_calculator.html) | Terzaghi Primary NC/OC Settlement, Secondary Compression |
| 8 | **Terzaghi Time Rate & Isochrones** | [`terzaghi_consolidation.html`](./terzaghi_consolidation.html) | Tv vs. U% Fourier Series Excess Pore Pressure Dissipation |
| 9 | **Immediate Elastic Settlement** | [`elastic_settlement.html`](./elastic_settlement.html) | Theory of Elasticity (Fox / Bowles) & Schmertmann (1978) CPT |
| 10 | **Multi-Layer Stratigraphy Settlement** | [`layered_settlement.html`](./layered_settlement.html) | Multi-Layer Sublayer Integration & Boussinesq Attenuation |
| 11 | **USCS Soil Classification** | [`uscs_classifier.html`](./uscs_classifier.html) | ASTM D2487 Coarse/Fine Decision Tree & Casagrande Plasticity |
| 12 | **Particle Size Distribution (PSD)** | [`gradation_plotter.html`](./gradation_plotter.html) | Semi-Log Sieve Curve, D10/D30/D60, Cu, Cc Calculations |
| 13 | **Proctor Compaction Curve Analyzer** | [`proctor_analyzer.html`](./proctor_analyzer.html) | Quadratic Regression, OMC, MDD & Zero Air Voids (ZAV) |
| 14 | **Stress Distribution Calculator** | [`stress_calculator.html`](./stress_calculator.html) | Boussinesq Point/Line/Area Load Vertical Stress Isobars |
| 15 | **Rock Mass Classification** | [`rock_mass_classification.html`](./rock_mass_classification.html) | Bieniawski RMR89, Barton Q-System, Hoek GSI Matrix |
| 16 | **Hoek-Brown Failure Criterion** | [`hoek_brown_criterion.html`](./hoek_brown_criterion.html) | Generalized Hoek-Brown (2002/2019) & Equivalent Mohr-Coulomb |
| 17 | **Seismic Site Classification** | [`seismic_site_classification.html`](./seismic_site_classification.html) | ASCE 7-16/22 & Eurocode 8 Vs30/N60 Site Class & Response Spectra |
| 18 | **CPT Soil Behavior Type (SBT)** | [`cpt_soil_classification.html`](./cpt_soil_classification.html) | Robertson (1990/2016) Non-Normalized & Normalized SBT Charts |
| 19 | **Soil Permeability Calculator** | [`soil_permeability.html`](./soil_permeability.html) | Constant Head, Falling Head & Hazen Empirical Conductivity |
| 20 | **Soil Phase Relationships** | [`soil_phase_relationships.html`](./soil_phase_relationships.html) | 3-Phase Weight-Volume Solver (w, e, n, Sr, Gs, Unit Weights) |
| 21 | **Liquefaction Potential Analyzer** | [`liquefaction_potential.html`](./liquefaction_potential.html) | Idriss & Boulanger (2008) SPT Triggering Procedure |
| 22 | **Spatial & GIS Format Converter** | [`spatial_converter.html`](./spatial_converter.html) | GeoJSON, KML, KMZ, GPX, CSV Multi-Format Transformation |
| 23 | **CSV to KML Batch Converter** | [`csv_to_kml.html`](./csv_to_kml.html) | Borehole & CPT Coordinate Transform to Styled Google Earth KML |
| 24 | **Geometry Simplifier & Optimizer** | [`geometry_simplifier.html`](./geometry_simplifier.html) | Douglas-Peucker Vertex Reduction & Interactive Map Preview |
| 25 | **Stress Calculator (Simple Edition)** | [`stress_calculator_simple.html`](./stress_calculator_simple.html) | Lightweight Single-Point Boussinesq & Westergaard Solver |

---

## ☕ Support & Sponsorship

If these open-source calculation tools and charts help your engineering projects, practice, or academic research, consider supporting continued open-source development:

👉 **[Buy Me a Coffee](https://buymeacoffee.com/agheysari)**

---

## 📄 License
This repository is open-sourced under the [MIT License](LICENSE).
