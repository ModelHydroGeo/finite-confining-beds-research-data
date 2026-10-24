# Data provenance

Each released CSV derives from a pre-existing v0.6 numerical-result export used to prepare the associated manuscript. Files were selected for their direct relationship to quantitative figures, reported comparison values, energy checks or resolution/performance statements. For copied files, numeric content and precision are byte-preserved from the source result export.

`data/local_verification/closed_capacity_equilibria.csv` is the sole format conversion. It is a direct CSV projection of the `equilibria` records in the original `closed_equilibria.json`, retaining the fields `case`, `ratio`, `MHX_Tr`, `physical_Tf`, `MHX_Sb` and `reference_Sb` without calculation.

No simulation was executed, no new figure was generated, and no numerical value was recalculated, interpolated or edited while preparing this package. Source code, scripts, executable files, input configurations, meshes and proprietary material were excluded by design. File names in `DATA_MANIFEST.csv` identify the result category and scenario, while `FIGURE_DATA_MAPPING.csv` documents the manuscript linkage.
