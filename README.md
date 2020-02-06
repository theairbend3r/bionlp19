# bioNLP19

## Overview
This repo contains that attempts three tasks mentioned in the [BioNLP OST 2019 (AGAC Track)](https://sites.google.com/view/bionlp-ost19-agac-track/description).  


### Task 1: Trigger Words NER
Named entity extraction and classification of trigger words in the PubMed abstracts.   
The trigger labels are:  
* Var
* MPA
* Interaction
* Pathway
* CPA
* Reg
* PosReg
* NegReg
* Disease
* Gene
* Protein
* Enzyme  


### Task 2: Thematic Roles Identification
Identify the thematic roles between the trigger 1. The thematic roles are:  
* ThemeOf: pointing from the theme to the center 
* CauseOf  pointing from the cause to center

This task requires the results from Task 1.



### Task 3: "Gene;Function change;disease" link discovery  
Extract the gene - function_change - disease link from a sentence.  
This task can either be performed based on the results of task-1 and task-2 or it can be performed independently.
