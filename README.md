# Expression Data Sets

Example datasets to teach some basic concepts post-primary analysis using R.   This is example dataset includes two pieces of data.  The first dataset are quantified gene transcripts using the program Salmon, where each value is a Transcripts per million.  The second dataset is information about each sample.

## expression_results.csv.gz
Contains gzipped results following Salmon quantification of samples from an RNA-seq dataset in comma delimited format.  The first row is the UID of each column.  The subsequent rows are "features" that will be analyzed.  In this case, they are Ensemble transcript ids are rows.


## sample_info.csv.gz

Contains gzipped sample info, where the first column is the sample UID, and the subsequent are information about the sample.  In this case, some patients have been run twice or have multiple entries for multiple timepoints.  

### Quality Control Metrics from the analysis run are included: 
PF_BASES, PCT_RIBOSOMAL_BASES,PCT_CODING_BASES, PCT_UTR_BASES, PCT_INTRONIC_BASES, PCT_INTERGENIC_BASES, PCT_USABLE_BASES

### Two visits are included: 
start,END

### Quality Control Of Samples:
RIN - a measure of integrity of the starting material.

### Three different kits are used: 
A,B,C



