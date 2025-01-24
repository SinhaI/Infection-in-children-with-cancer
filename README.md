
# Infection-in-children-with-cancer

**Publication:** The feasibility of host transcriptome profiling as a diagnostic tool for microbial etiology in childhood cancer patients with febrile neutropenia.

**Authors:** Martina Wahlund, Indranil Sinha, Kristina Broliden, Shanie Saghafian-Hedengren, Anna Nilsson, Anna Berggre 

**Publication date:** 2020/7/26

**Journal:** International Journal of Molecular Sciences

In this repository we have added the code used to generate the circos plot for this article. In this plot we wanted to show the gene expression profile detected throuth RNA sequencing. The Circos plot depicting up- and down-regulated genes for the three comparisons (virus vs. control = inner violet circle; co-infection vs control = middle green circle and unknown vs control = outer yellow circle).

To run this code DOWNLOAD CIRCOS, TUTORIALS AND TOOLS from http://circos.ca/software/download/circos/

To run Circos, you need Perl. To reproduce the circos plot one needs to run "RNA_Seq_kids.conf" file. One will need to invoke perl and pass the Circos script as an argument, along with following command-line parameters.

Below command is for windows OS.

C:>perl C:\path\to\circos\bin\circos -conf RNA_Seq_kids.conf
