# AmbiguityToVariability

This folder includes the data used in the paper ``Requirement Engineering of Software 
Product Lines: Extracting Variability using NLP'', submitted to RE'18 Data Track. 
It includes the requirements .txt files, and the annotations produced on the 
requirements belonging to the different files, based on the output of QuARS, which
identifies terms - single and multi-word - that can indicate ambiguity or variability
from an input text. The output of QuARS is based on different indicators. 
More details on the process followed are provided in the paper.

Specifically, the folder contains the following requirements files:

BLIT-Requirements.txt
Eirene-Requirements.txt
Library-Requirements.txt

The folder contains the following annotation files:

Blit-Annotation.xlsx
Eirene-Annotation.xlsx
Library-Annotation.xlsx

Each annotation file contains a set of sheet, one for each QuARS indicator.

Each sheet contains:
- line: LINE number of the requirements file to which the annotation refers.
- term: identified term, according to QuARS.
- annotation: annotation value, i.e. amb = ambiguity, var = variability, fp = false
positive.
