PsiloSoma Dataset – Occurrence and Ethnomycological Data on Psilocybe spp. (2022–2024)

Overview

This dataset is part of the PsiloSoma Project, an independent research initiative focused on ethnomycology, fungal ecology, and biogeography. It provides a curated and georeferenced collection of occurrence records for species within the genus Psilocybe, collected between 2022 and 2024, and integrates both original field observations and verified literature records.

The dataset is structured according to the Darwin Core (DwC) standard to ensure interoperability with global biodiversity infrastructures.

Project Description

The PsiloSoma Project aims to document the distribution, ecology, and ethnomycological relevance of Psilocybe species and other psychotropic fungi. The project combines field research, literature review, and data curation to contribute to biodiversity knowledge and open science.

This dataset represents a hybrid data resource integrating:

Original field observations (new records)

Literature-based occurrences from published studies

Ecological and habitat data

Ethnomycological context where available

Dataset Description

The dataset includes:

Georeferenced occurrence records

Taxonomic identification based on morphological analysis

Ecological metadata (habitat, elevation)

Temporal data (eventDate in ISO 8601 format)

Distinction between field observations and literature records

Source attribution for each record

Coordinates were obtained via GPS or derived from reliable sources and validated during curation.

Methodology

Data collection and validation followed these principles:

Field observations conducted between 2022–2024

Morphological identification based on macroscopic and microscopic features

Comparison with peer-reviewed mycological literature

Integration of published records from scientific sources

Georeferencing using GPS devices or validated geospatial tools

Assignment of coordinate uncertainty values based on data source

Standardization using Darwin Core terms

Internal quality control and consistency checks

Records are categorized as:

HumanObservation → original field data

MaterialCitation → literature-derived records

Data Structure (Darwin Core)

The dataset is provided as a CSV file formatted according to Darwin Core standards.

Core fields include:

occurrenceID – unique identifier

datasetID – dataset name

occurrenceStatus – presence status

basisOfRecord – observation type

scientificName – taxon name

taxonRank – taxonomic rank

kingdom, phylum, class, order, family, genus

decimalLatitude, decimalLongitude

geodeticDatum – WGS84

coordinateUncertaintyInMeters

coordinatePrecision

country, countryCode

locality

eventDate

habitat

minimumElevationInMeters

recordedBy, identifiedBy

identificationRemarks

occurrenceRemarks

informationWithheld

georeferenceSources

dataSource

Quality Control

Manual validation of all records

Cross-checking with scientific literature

Taxonomic consistency verification

Coordinate validation and plausibility checks

Removal of duplicate records

Standardization of formats and terminology

Usage

This dataset can be used for:

Species distribution modeling

Biodiversity and conservation studies

Fungal ecology research

Ethnomycological studies

Integration into biodiversity platforms

Limitations

Identification is primarily morphology-based

Genetic confirmation is not available for all records

Some literature records lack precise coordinates

Spatial uncertainty varies by data source

Dataset does not represent full species distribution

License 

This dataset is released under the Creative Commons Attribution 4.0 International License (CC BY 4.0).

Related Resources

Part of the occurrence data is supported by field observations recorded through the iNaturalist platform:

https://www.inaturalist.org/

These observations contributed to the development and validation of the dataset.

Citation

If you use this dataset, please cite it as:

Valletta FM (2024). PsiloSoma Dataset – Occurrence and Ethnomycological Data on Psilocybe spp. (2022–2024). DOI: 10.5281/zenodo.19224063

Project Information

Project Name: PsiloSoma Project Research Area: Ethnomycology, Fungal Biogeography

Contact

psilosomaproject@gmail.com

Acknowledgments

This dataset was developed through independent research and incorporates contributions from literature sources and observational data platforms.

Keywords

Psilocybe, ethnomycology, fungi, biodiversity, Darwin Core, GBIF, ecology, mycology

Metadata (metadata.json)

A metadata.json file accompanies this dataset and provides structured metadata for repository indexing and interoperability.

Data Sources

- Field observations (2022–2024)
- Literature records
- iNaturalist observations (where applicable)

LICENSE FILE

A file named LICENSE is included in the dataset package containing the full text of the CC BY 4.0 license.

