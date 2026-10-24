# Research data package: confining-bed thermal coupling

This package contains the processed numerical results underlying the quantitative figures and reported comparisons in the manuscript *Semi-analytical thermal coupling of geothermal reservoirs with semi-infinite and finite confining beds: formulation, verification and applications* (manuscript version 1.0).

The data are organised by scientific application: local verification, the Barends layered cooling benchmark, advective cooling, and a Dogger-inspired geothermal doublet. CSV files use UTF-8 encoding, a comma delimiter, and a header row. Values have been copied from the existing numerical-output collection without numerical recalculation, interpolation, or rounding. `closed_capacity_equilibria.csv` is a direct tabular conversion of the existing equilibrium JSON record; its values are unchanged.

## Contents

- `data/local_verification/`: transient finite-bed histories, closed-capacity equilibria, continuous response and refinement data.
- `data/barends/`: temperature profiles and comparison metrics for the layered Barends benchmark.
- `data/advective_cooling/`: global energy histories, numerical reference observations and summary values for three remote-boundary representations.
- `data/geothermal_doublet/`: production-temperature histories, energy budgets, temporal-resolution results, energy audits and performance statistics for the geothermal-doublet cases.
- `documentation/`: numerical context, units and data provenance.

`DATA_MANIFEST.csv` describes every released CSV. `FIGURE_DATA_MAPPING.csv` maps each manuscript figure to its data or identifies it as a conceptual illustration. `CHECKSUMS.sha256` provides SHA-256 integrity checks.

## Scope and reuse

This is a results-and-documentation package. It intentionally excludes source code, executables, scripts, input decks, model configurations, full three-dimensional meshes, and proprietary files. No license is selected in this release; contact the corresponding author before redistribution or reuse beyond scholarly examination.

## Citation

Please use the citation metadata in `CITATION.cff`. Publication bibliographic details and a persistent repository DOI are pending.
