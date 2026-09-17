# RefMat BAM-N010 PP data

This directory contains raw in-house measurement data acquired during the characterization of the BAM-N010 reference material and during the homogeneity and stability studies. The data focus on the hydrodynamic diameter of polypropylene nanoparticles and consist of instrument-generated raw data and associated measurement records. Dynamic light scattering (DLS) was used to measure the hydrodynamic diameter of the particles in accordance with ISO 22412. Data processing, statistical evaluation, and the resulting assessment of homogeneity and stability are provided in the associated analysis repository: https://github.com/BAMresearch/RefMat-BAM-N010-PP-analysis

## Availability

It can be found as a dataset on Zenodo: https://zenodo.org/records/22813696

## Expected Contents

    2026-05-07_BAM-N010
    data_2023
    data_2025-06-30
    data_2025-07-01_ALV
    data_2025-07-07
    data_2025-09-22_BAM-N010
    data_2025-09-25_BAM-N010
    data_2025_March
    data_homogeneity_2022
    data_short_term_stability_2022
    CITATION.cff
    LICENSE
    README.md

## License

This dataset is licensed under the Creative Commons Attribution 4.0 International license (CC BY 4.0).

SPDX-License-Identifier: CC-BY-4.0

You are free to share and adapt the data for any purpose, including commercial purposes, provided that appropriate credit is given, a link to the license is provided, and any changes are indicated.

The full license text is available at:
https://creativecommons.org/licenses/by/4.0/legalcode

Unless otherwise stated, all files in this repository are covered by this license. Third-party materials, if any, are excluded from this license and remain subject to their respective terms.

## Recommended citation

Please cite the raw measurement data as follows:

Bundesanstalt für Materialforschung und –prüfung (BAM), Unter den Eichen 87, 12205 Berlin, Germany (2026).
Instrument-generated raw data from dynamic light scattering measurements for the characterization of the BAM-N010 reference material and the assessment of its homogeneity and stability.
Version 1.0.0.
https://doi.org/10.5281/zenodo.22813696

## Commands for prepare & publish

Validate the `CITATION.cff` in this folder:

    cffconvert --validate 2>&1 | less

Create the archive for upload:

    zip -r RefMat-BAM-N010-PP-data-v1.0.0.zip data* 2026* README.md LICENSE CITATION.cff
