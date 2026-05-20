# PsiloSoma Dataset

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.19224063.svg)](https://doi.org/10.5281/zenodo.19224063)

**PsiloSoma Dataset – Occurrence and Ethnomycological Data on *Psilocybe* spp. (2022–2024)**

The PsiloSoma Dataset is part of the **PsiloSoma Project**, an independent, non-commercial scientific initiative coordinated by Fabio Mao “NaturalMao” Valletta.

The dataset provides curated occurrence and contextual data for selected *Psilocybe* records documented between 2022 and 2024, integrating original field observations and literature-derived records.

The dataset is structured using **Darwin Core-aligned terms** to support interoperability with biodiversity data infrastructures, reproducible research, ecological documentation and responsible open science.

## Zenodo record and DOI

A citable archived version of the dataset is available on Zenodo:

**DOI:** https://doi.org/10.5281/zenodo.19224063  
**Record page:** https://zenodo.org/records/19224063

Please cite the DOI when using the dataset in publications, reports, presentations, derived datasets or other research outputs.

The Zenodo record page can be used as a public landing page for downloads, files, metadata, license and citation information.

## Suggested citation

Valletta FM (2024). *PsiloSoma Dataset – Occurrence and Ethnomycological Data on Psilocybe spp. (2022–2024)*. Zenodo. https://doi.org/10.5281/zenodo.19224063

## Scientific coordination and dataset curation

Fabio Mao Valletta  
Naturalist and Scientific Coordinator of the PsiloSoma Project  
ORCID: 0009-0003-0976-5464

The GitHub repository is maintained under the PsiloSoma Project identity. Fabio Mao Valletta is indicated as scientific coordinator, dataset author/curator and contact person for scientific and documentation-related matters.

## Repository contents

```text
README.md
psilosoma_dataset.csv
metadata.json
CITATION.cff
LICENSE
CHANGELOG.md
```

## Scope

The dataset is intended for scientific, naturalistic, educational and conservation-related purposes. It may support:

- fungal biogeography and distribution studies;
- ecological documentation and habitat comparison;
- ethnomycological research;
- biodiversity data standardization;
- integration with open biodiversity infrastructures;
- future taxonomic, ecological or conservation-related research.

This public dataset currently covers the **2022–2024** data package. Later fieldwork, including 2025 material and observations, is **not included** in this public dataset and will remain under internal curation until taxonomic, legal, geoprivacy, documentation and publication checks are completed.

## Data sources

The dataset integrates:

- original field observations;
- literature-derived records;
- ecological and habitat metadata;
- georeferenced occurrence data;
- source attribution for each record;
- non-sensitive ethnomycological or biocultural context where available.

Records are categorized using Darwin Core-compatible values such as:

- `HumanObservation` — original field-based observation records;
- `MaterialCitation` — literature-derived or publication-derived records.

## Data structure

The dataset is provided as a CSV file using Darwin Core-aligned fields, including:

- `occurrenceID`
- `datasetID`
- `datasetName`
- `occurrenceStatus`
- `basisOfRecord`
- `scientificName`
- `taxonRank`
- `kingdom`, `phylum`, `class`, `order`, `family`, `genus`
- `decimalLatitude`, `decimalLongitude`
- `geodeticDatum`
- `coordinateUncertaintyInMeters`
- `coordinatePrecision`
- `country`, `countryCode`
- `locality`
- `eventDate`
- `habitat`
- `minimumElevationInMeters`
- `recordedBy`, `identifiedBy`
- `identificationRemarks`
- `occurrenceRemarks`
- `informationWithheld`
- `georeferenceSources`
- `associatedReferences`

## Methodology

Data collection and curation followed these general principles:

- field observations and documentation conducted between 2022 and 2024;
- taxonomic identification based primarily on morphological assessment and comparison with mycological literature;
- integration of literature-derived records where relevant;
- georeferencing through GPS data or validated geospatial sources;
- assignment of coordinate uncertainty values according to data source and spatial precision;
- standardization of fields using Darwin Core-aligned terminology;
- internal consistency checks, duplicate review and taxonomic validation.

## Quality control

Quality-control procedures include:

- manual validation of records;
- cross-checking with scientific literature;
- taxonomic consistency review;
- coordinate plausibility checks;
- removal or consolidation of duplicate records;
- standardization of date, locality and terminology fields.

## Limitations

- Identifications are primarily morphology-based unless otherwise indicated.
- Genetic confirmation is not available for all records.
- Spatial uncertainty varies by record and data source.
- Some literature-derived records may lack precise coordinates.
- The dataset should not be interpreted as a complete distribution map.
- Sensitive locations or details may be generalized, withheld or treated cautiously for geoprivacy, conservation, legal or authorization-related reasons.

## Ethical and legal note

The PsiloSoma Project does **not** promote consumption, cultivation, trade, recreational use, unauthorized collection or practical use of any organism.

Some fungal taxa may be legally regulated, difficult to identify or potentially confused with toxic species. Any collection, transfer or analysis of biological material must comply with applicable laws, local regulations, protected-area rules and required authorizations.

The dataset is shared for scientific, naturalistic, educational and conservation-related purposes only.

## Future updates

Additional records and material from later fieldwork, including 2025 activities, are currently under curation and are not included in this public dataset.

Future updates may be released only after taxonomic, legal, geoprivacy, documentation, authorization and publication checks. Any future public release will be documented through the repository changelog and, where appropriate, through a new archived version on Zenodo.

## Related publication

This dataset is associated with and partly expands upon the following publication:

Valletta FM (2023). *Contribution to the knowledge of two species of psilocybin mushrooms with high therapeutic potential found along the Central-Southern Apennines (Italy): Psilocybe serbica and Psilocybe semilanceata*. DOI: 10.6093/2724-4393/10411

## License

This dataset is released under the **Creative Commons Attribution 4.0 International License (CC BY 4.0)**.

https://creativecommons.org/licenses/by/4.0/

## Contact

PsiloSoma Project: psilosoma.project@gmail.com  
Equivalent contact alias: psilosomaproject@gmail.com  

Fabio Mao Valletta  
Naturalist and Scientific Coordinator of the PsiloSoma Project  
maovalletta@gmail.com

## Keywords

*Psilocybe*, fungal biodiversity, mycology, ethnomycology, fungal ecology, biogeography, Darwin Core, GBIF, iNaturalist, open science, biodiversity data, Mediterranean biodiversity, ecological documentation.
