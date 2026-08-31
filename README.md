# 🌍 Open-Source Geotechnical Engineering & Geospatial Calculators

A collection of **25 standalone, client-side HTML/JavaScript calculation tools** for geotechnical
engineers, civil engineering researchers, and geospatial analysts, developed by
**Ali Gheysari, PhD**.

🌐 **[Open the interactive portal](https://agheysari.github.io/geotechnical-toolbox/)**

[![Live portal](https://img.shields.io/badge/Live%20portal-GitHub%20Pages-success.svg)](https://agheysari.github.io/geotechnical-toolbox/)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![Calculators](https://img.shields.io/badge/Calculators-25-blue.svg)](https://github.com/agheysari/geotechnical-toolbox)

---

## ⚡ Key features

* **Runs entirely in your browser.** No backend, no build step, nothing uploaded. Open a file
  locally or serve it from any static host.
* **One file per tool.** Each calculator is a self-contained HTML page with its CSS and JavaScript
  inline, so it can be dropped into a portal, a course, or an intranet as-is.
* **Consistent SI units.** Every input label, result and chart axis states its unit explicitly
  (m, kPa, kN/m³, mm, years). Settlements are reported in mm, times in years.
* **Report-ready figures.** Charts share one theme, with consistent type, palette, gridlines and
  axis labelling, so a figure can be pasted straight into a report.
* **Consistent page shell.** All 25 pages share the same header, container, results and footer
  structure, and validate your inputs the same way before calculating.

---

## 📚 Calculation modules

| # | Module | Run it | Source | Key methods / theories |
|---|--------|--------|--------|------------------------|
| 1 | **Axial Pile Capacity** | [Launch](https://agheysari.github.io/geotechnical-toolbox/axial_pile_capacity.html) | [`axial_pile_capacity.html`](./axial_pile_capacity.html) | Alpha (API RP 2A), Beta (Burland), Lambda (Vijayvergiya & Focht) |
| 2 | **Pile Group Efficiency & Settlement** | [Launch](https://agheysari.github.io/geotechnical-toolbox/pile_group_efficiency.html) | [`pile_group_efficiency.html`](./pile_group_efficiency.html) | Converse-Labarre, Sayed-Baker, cohesive block shear, 2:1 raft model |
| 3 | **Shallow Bearing Capacity** | [Launch](https://agheysari.github.io/geotechnical-toolbox/bearing_capacity.html) | [`bearing_capacity.html`](./bearing_capacity.html) | Terzaghi, Meyerhof, Hansen, Vesic general formulations |
| 4 | **Lateral Pile P-y Curves** | [Launch](https://agheysari.github.io/geotechnical-toolbox/lateral_pile_py_curves.html) | [`lateral_pile_py_curves.html`](./lateral_pile_py_curves.html) | Matlock (1970) soft clay, API RP 2A sand |
| 5 | **Lateral Earth Pressure** | [Launch](https://agheysari.github.io/geotechnical-toolbox/earth_pressure.html) | [`earth_pressure.html`](./earth_pressure.html) | Rankine & Coulomb theories (Ka, Kp, Ko, surcharge) |
| 6 | **Cantilever Retaining Wall Stability** | [Launch](https://agheysari.github.io/geotechnical-toolbox/retaining_wall_stability.html) | [`retaining_wall_stability.html`](./retaining_wall_stability.html) | Sliding, overturning, base contact & eccentricity checks |
| 7 | **1D Consolidation Settlement** | [Launch](https://agheysari.github.io/geotechnical-toolbox/consolidation_calculator.html) | [`consolidation_calculator.html`](./consolidation_calculator.html) | Terzaghi primary NC/OC settlement, secondary compression |
| 8 | **Terzaghi Time Rate & Isochrones** | [Launch](https://agheysari.github.io/geotechnical-toolbox/terzaghi_consolidation.html) | [`terzaghi_consolidation.html`](./terzaghi_consolidation.html) | Tv vs. U% Fourier-series excess pore pressure dissipation |
| 9 | **Immediate Elastic Settlement** | [Launch](https://agheysari.github.io/geotechnical-toolbox/elastic_settlement.html) | [`elastic_settlement.html`](./elastic_settlement.html) | Theory of elasticity (Fox / Bowles) & Schmertmann (1978) CPT |
| 10 | **Multi-Layer Stratigraphy Settlement** | [Launch](https://agheysari.github.io/geotechnical-toolbox/layered_settlement.html) | [`layered_settlement.html`](./layered_settlement.html) | Sublayer integration & Boussinesq attenuation |
| 11 | **USCS Soil Classification** | [Launch](https://agheysari.github.io/geotechnical-toolbox/uscs_classifier.html) | [`uscs_classifier.html`](./uscs_classifier.html) | ASTM D2487 decision tree & Casagrande plasticity chart |
| 12 | **Particle Size Distribution (PSD)** | [Launch](https://agheysari.github.io/geotechnical-toolbox/gradation_plotter.html) | [`gradation_plotter.html`](./gradation_plotter.html) | Semi-log sieve curve, D10/D30/D60, Cu, Cc |
| 13 | **Proctor Compaction Curve Analyzer** | [Launch](https://agheysari.github.io/geotechnical-toolbox/proctor_analyzer.html) | [`proctor_analyzer.html`](./proctor_analyzer.html) | Quadratic regression, OMC, MDD & zero air voids (ZAV) |
| 14 | **Stress Distribution Calculator** | [Launch](https://agheysari.github.io/geotechnical-toolbox/stress_calculator.html) | [`stress_calculator.html`](./stress_calculator.html) | Boussinesq point/line/area load vertical stress isobars |
| 15 | **Rock Mass Classification** | [Launch](https://agheysari.github.io/geotechnical-toolbox/rock_mass_classification.html) | [`rock_mass_classification.html`](./rock_mass_classification.html) | Bieniawski RMR89, Barton Q-system, Hoek GSI matrix |
| 16 | **Hoek-Brown Failure Criterion** | [Launch](https://agheysari.github.io/geotechnical-toolbox/hoek_brown_criterion.html) | [`hoek_brown_criterion.html`](./hoek_brown_criterion.html) | Generalized Hoek-Brown (2002/2019) & equivalent Mohr-Coulomb |
| 17 | **Seismic Site Classification** | [Launch](https://agheysari.github.io/geotechnical-toolbox/seismic_site_classification.html) | [`seismic_site_classification.html`](./seismic_site_classification.html) | ASCE 7-16/22 & Eurocode 8 Vs30/N60 site class & response spectra |
| 18 | **CPT Soil Behavior Type (SBT)** | [Launch](https://agheysari.github.io/geotechnical-toolbox/cpt_soil_classification.html) | [`cpt_soil_classification.html`](./cpt_soil_classification.html) | Robertson (1990/2016) normalized & non-normalized SBT charts |
| 19 | **Soil Permeability Calculator** | [Launch](https://agheysari.github.io/geotechnical-toolbox/soil_permeability.html) | [`soil_permeability.html`](./soil_permeability.html) | Constant head, falling head & Hazen empirical conductivity |
| 20 | **Soil Phase Relationships** | [Launch](https://agheysari.github.io/geotechnical-toolbox/soil_phase_relationships.html) | [`soil_phase_relationships.html`](./soil_phase_relationships.html) | 3-phase weight-volume solver (w, e, n, Sr, Gs, unit weights) |
| 21 | **Liquefaction Potential Analyzer** | [Launch](https://agheysari.github.io/geotechnical-toolbox/liquefaction_potential.html) | [`liquefaction_potential.html`](./liquefaction_potential.html) | Idriss & Boulanger (2008) SPT triggering procedure |
| 22 | **Spatial & GIS Format Converter** | [Launch](https://agheysari.github.io/geotechnical-toolbox/spatial_converter.html) | [`spatial_converter.html`](./spatial_converter.html) | GeoJSON, KML, KMZ, GPX, CSV multi-format transformation |
| 23 | **CSV to KML Batch Converter** | [Launch](https://agheysari.github.io/geotechnical-toolbox/csv_to_kml.html) | [`csv_to_kml.html`](./csv_to_kml.html) | Borehole & CPT coordinate transform to styled Google Earth KML |
| 24 | **Geometry Simplifier & Optimizer** | [Launch](https://agheysari.github.io/geotechnical-toolbox/geometry_simplifier.html) | [`geometry_simplifier.html`](./geometry_simplifier.html) | Douglas-Peucker vertex reduction & interactive map preview |
| 25 | **Stress Calculator (Simple Edition)** | [Launch](https://agheysari.github.io/geotechnical-toolbox/stress_calculator_simple.html) | [`stress_calculator_simple.html`](./stress_calculator_simple.html) | Lightweight single-point Boussinesq & Westergaard solver |
| 26 | **AASHTO Flexible Pavement Design** | [Launch](https://agheysari.github.io/geotechnical-toolbox/flexible_pavement.html) | [`flexible_pavement.html`](./flexible_pavement.html) | Calculate required Structural Number (SN) using AASHTO 1993 |
| 27 | **AASHTO Rigid Pavement Design** | [Launch](https://agheysari.github.io/geotechnical-toolbox/rigid_pavement.html) | [`rigid_pavement.html`](./rigid_pavement.html) | Calculate required concrete slab thickness (D) using AASHTO 1993 |
| 28 | **ESAL Calculator** | [Launch](https://agheysari.github.io/geotechnical-toolbox/esal_calculator.html) | [`esal_calculator.html`](./esal_calculator.html) | Estimate cumulative traffic loading (W18) over pavement design life |

---

## Disclaimer

> **These tools are for preliminary estimation, screening, educational and verification purposes
> only.**
>
> Geotechnical engineering involves site-specific ground conditions, stratigraphy, soil-structure
> interaction and subsurface uncertainty. All results, methods and charts produced by these
> calculators **must be reviewed and validated by a licensed Professional Engineer**
> before use in final design, construction documents, or safety-critical decisions.
>
> The author assumes no liability for errors, omissions, or damages arising from the use or
> interpretation of these calculators.

---

## Support

These tools are free and open-source. If they save you time on a project or in the classroom, you
can [buy me a coffee](https://buymeacoffee.com/agheysari). Entirely optional, and never required
to use anything here.

---

## 📄 License

Released under the [GNU General Public License v3.0](LICENSE).
