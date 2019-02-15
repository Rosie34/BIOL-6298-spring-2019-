########################################################################
#################### ADHD SEX-SPECIFIC GWAS READ-ME #####################
########################################################################
JOANNA MARTIN - AUGUST 2017

These are the GWAS results files from sex-specific meta-analyses of 
case-control clinical ADHD by the Psychiatric Genomics Consortium (PGC) 
and the Lundbeck Foundation Initiative for Integrative Psychiatric Research (iPSYCH).

N.B Please refer to the following bioRxiv pre-print for details:
"A genetic investigation of sex bias in the prevalence of attention deficit hyperactivity disorder"
http://www.biorxiv.org/content/early/2017/06/23/154088
(peer-reviewed publication pending as of writing this note)
Please cite this paper when using these data.

Disclaimer:
These data are provided "as is", and without warranty, for scientific and educational use only. If
you download these data, you acknowledge that these data will be used only for non-commercial
research purposes; that the investigator is in compliance with all applicable state, local, and
federal laws or regulations and institutional policies regarding human subjects and genetics
research; that secondary distribution of the data without registration by secondary parties is
prohibited; and that the investigator will cite the appropriate PGC publication in any
communications or publications arising directly or indirectly from these data. 

Sample sizes:
Male-only GWAS: N=14,154 cases & 17,948 controls
Female-only GWAS: N=4,945 cases & 16,246 controls

Ancestry: 
All samples are of European ancestry

Other notes:
In addition to standard QC, results have been filtered for: 
MAF > 0.01
Mean imputation quality (INFO > 0.8)
Sample size (N > 50% of total sample size)

Files:
META_PGC_iPSYCH_males.gz
META_PGC_iPSYCH_females.gz

File header rows:
SNP - Marker name
CHR - Chromosome (hg19)
BP - Base pair location (hg19)
A1 - Reference allele for OR (may or may not be minor allele)
A2 - Alternative allele
Effect - log(OR) for the effect of the A1 allele
SE - Standard error of the log(OR)
P - P-value for association test in the meta-analysis

For questions, contact: Joanna Martin (jmartin@broadinstitute.org)