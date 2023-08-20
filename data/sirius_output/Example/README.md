# Preparation

Make sure you have:

-   downloaded (and installed) SIRIUS
-   are logged in
    - either with you personal account
    - or the provided workshop account: https://bio.informatik.uni-jena.de/workshops/2023-non-targeted-metabolomics-data-mining-for-biomedical-research/
-   have the latest version of the GitHub workshop repository
-   downloaded and extracted the SIRIUS example workspace (https://upload.uni-jena.de/data/64d7efdfbb3653.86496924/example-sirius-projectspace-structure.zip)
-   downloaded and extracted the custom database zip (https://upload.uni-jena.de/data/64df28e7adacf7.83901104/customdbs.zip)

# Follow along the examples

## General look at the SIRIUS interface

## Import the file `CD-MRG-metabolomics_summerschool_2023/data/mzmine_output/Example/example_sirius.mgf`

## Load the precomputed worksapce from the exctracted zip (`example-sirius-projectspace-structure`)

## Examples found with the (SIRIUS-annotated) molecular network

### Compound connected to "Pipperine" (responsible for the spiciness of pepper)

-> search for feature `_9065` in SIRIUS

### Compound connected to "Vanilline" (vanilla flavor)

-> search for feature `_3636` in SIRIUS

## Custom structure database created from PubChem transformations for Diphenhydramine

-   search "Diphenhydramine" in PubChem, go to "Transformations" (<https://pubchem.ncbi.nlm.nih.gov/compound/3100#section=Transformations>)
-   import from the extraced `customdbs.zip`: `customdbs/customdb-diphenhydramine-pubchem`

## Look for custom database hits in `CD-MRG-metabolomics_summerschool_2023/data/sirius_output/Example/compound_identifications.tsv` (optional)

- for SIRIUS >= 5.8.3, the integrated filtering feature can be used

### Diphenhydramine itself

-> search for feature `_4511` in SIRIUS

### Create a new custom database

- open [sirius_output/Example/customdb-diphenhydramine-pubchem-smiles.tsv](https://github.com/ssi-dk/CD-MRG-metabolomics_summerschool_2023/blob/main/data/sirius_output/customdb-diphenhydramine-pubchem-smiles.tsv)
- copy SMILES

### Another example from the custom database

-> search for feature `_2483` in SIRIUS

### N-Desmethyldiphenhydramine, also part of the publication

-> search for feature `_4194` in SIRIUS
