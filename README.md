# CD-MRG-metabolomics_summerschool_2023
This repository contains teaching material for the [3rd International Summer School on Non-Targeted Metabolomics Data Mining for Biomedical Research](https://en.ssi.dk/news/events/summer-school-on-non-targeted-metabolomics-data-mining-for-biomedical-research).

## Exercise

Non-invasive drug monitoring is desirable as it improves patient experience. Instead of relying on invasive blood draws drug pharmacokinetics and metabolism could for example be monitored through the skin. During the summer school, you will be working with a subset of the data published by [Panitchpakdi and collaborators (2022)](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0271794). The datasets consists of plasma and skin swabs (forearm, forehead and upper back) collected from healthy volunteers (n=7) over the course of 24 hours, who have been administered the antihistaminic diphenhydramine. Your task will be to investigate whether:

- Diphenhydramine and its metabolites can be detected in the skin and whether it exhibits similar pharmacokinetics as in plasma?
- You can observe other metabolites that exhibit interesting time trends in plasma and whether those metabolites can also be detected in the skin?

## Data

Metabolomics mass spectrometry data are publicly available in the open .mzML format at: [MSV000092389](https://massive.ucsd.edu/ProteoSAFe/dataset.jsp?task=c0f3e5587cb54a01ba5782ff7a442249).

As a student you will be divided into two groups. Group 1 will be working with skin samples collected from the forehead, whereas Group 2 will work on skin samples collected from the forearm. Both groups 
will be investigating whether their respective skin samples could be suitable for non-invasive drug monitoring by comparing them to the plasma samples. The instructor team will be be working with skin samples collected from the upper back. 

## MZmine 3

Preprocessed data are available in the subfolders [data/mzmine_output](https://github.com/ssi-dk/CD-MRG-metabolomics_summerschool_2023/tree/main/data/mzmine_output). [We added some placeholders for now, MZmine 3 team, please replace with the corresponding outputs for 
downstream analysis]


## GNPS

Mass spectral molecular networks of the data are publicly accessible through the links below.

Example: https://gnps.ucsd.edu/ProteoSAFe/status.jsp?task=6c9c4b22970f448d933a6fc7fa13227e

Group 1: https://gnps.ucsd.edu/ProteoSAFe/status.jsp?task=a2baed56d46648898aad480f9e484160

Group 2: https://gnps.ucsd.edu/ProteoSAFe/status.jsp?task=ca64bf41771b4152a3f94cc09b93c546

## Sirius+CSI:FingerID

Results are available as complete SIRIUS project spaces and via corresponding summary files.

Summary files for molecular formula annotations (`formula_identifications.tsv`), molecular structure annotations (`compound_identifications.tsv`) and compound class annotations (`canopus_compound_summary.tsv`)
can be found in subfolders of
[data/sirius_output](https://github.com/ssi-dk/CD-MRG-metabolomics_summerschool_2023/tree/main/data/sirius_output).

Complete SIRIUS project spaces are available through the links below.

Example:  https://upload.uni-jena.de/data/64cb6d9e183353.74747773/example-sirius-projectspace.zip

Group1: https://upload.uni-jena.de/data/64cb6b5f245b16.51592951/group1-sirius-projectspace.zip

Group2: https://upload.uni-jena.de/data/64cb6cbadf6b89.77294609/group2-sirius-projectspace.zip

## MS2LDA

Results are available through the provided GNPS and MS2LDA.org links below. Briefly, the GNPS-MS2LDA links provide quick insights
in especially mass spectra that are linked to annotated Mass2Motifs from selected MotifSets from MotifDB. If there are un-annotated
Mass2Motifs that require further investigation, the .dict file (downloaded from GNPS) can be uploaded into MS2LDA.org to explore the
mass fragment and/or neutral loss features that are associated to the Mass2Motif. Further information such as statistics on how many
mass spectra are connected to Mass2Motifs are also available.

GNPS-MS2LDA results are available through the links below.

Example: https://gnps.ucsd.edu/ProteoSAFe/status.jsp?task=15fbb620a6f24582a8d1b25e54ecc2f5

Group1: https://gnps.ucsd.edu/ProteoSAFe/status.jsp?task=396fbe18da6d4da8aadf08afa8037614

Group2: https://gnps.ucsd.edu/ProteoSAFe/status.jsp?task=ab533f6174d84759af509792570814b7

MS2LDA.org results are available through the links below.

Example: https://ms2lda.org/basicviz/summary/2988/

Group1: https://ms2lda.org/basicviz/summary/2990/

Group2: https://ms2lda.org/basicviz/summary/2991/

## matchms

## Statistics

Example jupyter notebooks used for data analysis are available in the subfolder [notebooks](https://github.com/ssi-dk/CD-MRG-metabolomics_summerschool_2023/tree/main/notebooks). 
Interactive jupyter notebooks can be launched in Google Colaboratory here:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ssi-dk/CD-MRG-metabolomics_summerschool_2023/blob/main/) 
