# RNA-Seq_Time_series
R code for analyzing time point RNA-Seq data using Deseq2

This script is part of a bioinformatics workflow that involves processing RNA-Seq data. It starts by loading necessary R libraries for handling transcript quantification data (tximport) and genomic annotations (GenomicFeatures). Then, it prepares file paths to the quantification results generated by a tool like Salmon, assigns names to these files for easier reference, creates a transcript database from a GTF file (which is a format for storing gene annotations), extracts a mapping of transcript names to gene IDs from this database, and finally writes this mapping to a CSV file for further analysis or reference.
This data is then analyzed using the DESeq2 R package for differential expression.
