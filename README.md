# Wenderski-ATACseq-Output

This is the output from the ATACseq analysis of the Wenderski paper. Link to the analysis portion of the paper in the about section. Note: these are the output files only. The output logs are not included (they are for your own viewing and troubleshooting when doing the analysis). 

For the html files, download the files and you can load them on a web browser by clicking on them. 

# Step 3: QC of the Fastq Files

Along with the output log, the PretrimFastQC_multiqc_report.html can be checked to help inform your trimming.

# Step 5: Repeat QC on post trim files

The PosttrimFastQC_multiqc_report.html is compared to the pretrim.

# Step 6: QC of the Fastq Files: Contamination Screening

FastqScreen_multiqc_report.html

# Step 7: Align to mm10 genome using Bowtie2

bowtie2_multiqc_report.html

# Step 8: Filter aligned files

sam_multiqc_report.html

# Step 10: QC with Deeptools

Plot the correlation between samples as either a PCA or a Correlation Plot: Deeptools/PCA_ATAC10kbins.pdf and Deeptools/SpearmanCorr_ATAC10kbins.pdf

# Step 13: QC all peaks with Deeptools

For Homerpeaks_ATAC.Steady.bed: Deeptools/profile_baselineATACpeaks.pdf and Deeptools/Heatmap.Allpeaks.SteadyState.pdf
For Homerpeaks_ATAC.Knockout.bed: Deeptools/profile_KnockoutATACpeaks.pdf and Deeptools/Heatmap.Allpeaks.Knockout.pdf

# Step 15: Make Deeplots heatmap and profile over TSS and DE peaks

Deeptools/profile_mouseTSS.ATAC.pdf and Deeptools/Heatmap.MouseTSS.ATAC.pdf
Deeptools/profile_FDRfiltered.baselinevsknockout_ATACdiffpeaks.pdf and Deeptools/Heatmap.FDRfiltered.baselinevsknockout_ATACdiffpeaks.pdf
