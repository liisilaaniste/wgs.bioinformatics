![alt text](https://github.com/liisilaaniste/wgs.bioinformatics/blob/main/Cosyne%20logo%20transparent%20background.png)
# 

This page is intended for candidates interviewing for the Bioinformatician role at CoSyne Therapeutics. The exercise reflects some of the main tasks this role would be undertaking, namely whole genome sequencing analysis, genomics analysis tool selection, pipeline builiding, as well as data visualisation and communication.

There are multiple ways to answer these questions, therefore feel free to showcase your creativity both in pseudocode as well as data visualisaiton tasks. Please reach out with any questions you may have on this or if you encounter any problems. 

📬 **You can submit the answers as a notebook or files by email. Please ensure that the code for question 11 is reproducible (i.e., can be run by another user). Please don't forget to note your name and date of submission.**

Hope you have fun! 

### WXS questions

1. Quality control of FASTQ and mapped reads. What abnormalities, errors & metrics do you look out for?

2. Cancer genomes are highly mutated. What would your mapping strategy be? Assuming paired end reads, please provide pseudocode for mapping and highlight important hyperparameters.
```
<>
```
3. What different types of genomic alterations in cancer do you know of? 

4. **Variant calling pipeline**: What are the considerations and challenges when analysing cancer genomes without matched control tissue (i.e., blood)? How would you overcome some of the problems you've identified?

5. Please write pseudocode of your preferred variant calling pipeline describing the journey of a cancer genome .bam file and giving a brief overview of the output files.
```
<>
```
6. Variant allele frequency (VAF). What is the importance of VAF in cancer?

7. **Variant interpretation**: What are considered deleterious mutations in cancer? How would you differentiate between driver and passenger mutations, and what tools would you use to assess this? 

8. **Complex features**: What are some of the tools and approaches you would use to characterise kataegis, chromoplexy and chromothripsis?

9. Please write pseudocode using your favourite tool for copy-number gain/loss analysis assuming a .bam file.
```
<>
```
10. What would your strategy be to identify whole genome duplication events? 

11. **Data visualisation**:

:black_square_button: Please find a list of tumour sample IDs below. Go to [Genomic Data Commons Data Portal](https://portal.gdc.cancer.gov) and download mutation annotation format (.maf) files for the samples listed in sample.unique.csv file. Extract the mutations in *TP53* and plot the location in protein, the amino acid change and mutation type (for example, in a lollipop plot). Is there a hot-spot mutation? Repeat the same exercise for *IDH1* mutation.
```
code + image
```

:black_square_button: Unbalanced translocation and subsequent deletion of chromosomes 1p and 19q in oligodendroglioma are an early event and diagnostic of the disease. Could you visualise that event in a plot (for example a circos plot). Feel free to generate your own example data assuming a perfect 1p:19q fusion from the centromeres.
```
code + image
```


