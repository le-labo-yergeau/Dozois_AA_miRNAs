R code used for data manipulation, statistical analyses and figure generation for the manuscript "Plant miRNAs and amino acids interact to shape soil bacterial communities".

![Graphical_Abstract_AA_miRs](https://github.com/user-attachments/assets/0225b308-9a6e-4e6a-9844-87894c62ad0d)

The codes are structured in three folders: miRNA_statistics, Microbial_statistics and Final_Figures.

-miRNA_statistics: 
This folder contains 
A) The analyses the small RNA sequencing data in the roots of Arabidopsis under three fertilization treatments (RMD files #2-5). 
B) The correlations and linear models of the relative abundance of miRNAs with the relative abundance of bacterial taxa (RMD file #6).

-Microbial_statistics: 
This folder contains 
A) The analyses of the 16S amplicon sequencing data in  the roots of Arabidopsis under three fertilization treatments (In_planta_16S folder).
B) The effect of miRNAs on the growth of the simplified microbial community (Community_Growth_curves folder).
C) The analyses of the  16S amplicon sequencing data of the simplified microbial community exposed to miRNAs (16SvsmiRNAs).
D) The impact of miRNAs on the bacterial consumption of amino acids (AA_consumption).
E) The effect of miRNAs on the growth of three bacterial isolates (ASVgrowth_vs_miRNA).
F) The germination assay analyses where Arabidopsis was inoculated with bacterial isolates (Germination_test_ACR). 

-Final_figures: 
This folder contains
All of the publication-ready figures for both the main text and supplementary material. 

It is important to use the Rproject associated to the analyses you want to run. 
In each subfolder, the Rproject, numbered as 1, must be opened prior to any RMD file. 
