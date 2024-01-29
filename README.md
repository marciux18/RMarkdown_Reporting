# RMarkdown_Reporting
In this repository I will store the R Markdown files that I created to generate automatic reports of the sequencing runs performed at SSI. The aim of the reports is to determine the quality of the run and the samples. 

The file is divided in multiple sections.

- Overall section includes info on the sequencing run (eg the number of samples for each host species)
- Controls section: includes info on the negative and positive controls included in the run and if contamination was detected
- Host sections (Human, Swine and Avian): includes an overall idea of the samples that returned full or partial genome and how many failed. These sections also include info on how many gene segments failed and in which samples. Furthermore tables showing the subtype and/or genotype for each samples are shown. Samples with indeterminate genotypes or that failed are also listed. The Avian section also include a plot showing the genetic identification of the internal genotypes including the percentage of identity.
- Pairwise distance sections: for each host a pairwise distance plot at each gene segment (including all the samples processed in the sequencing run divided per host) is attached to the report.

The final report can be manually modified to include more information related to each sample or sequencing run.
This report is shared with human, swine and avian influenza experts within the Influenza group and used internally to assess the quality of the samples and their genotypes. The output will be used to further communications with internal and external stakeholders.

HOW TO USE IT.

In progress
