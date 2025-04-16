# BMI620-Project
This project is contributed by Steven DING, Mario MA and Haorui WU.
The topic is concerning Insominia.

Data link: https://vu.data.surfsara.nl/index.php/s/06RsHECyWqlBRwq

## Data description
Summary statistics files for "Genome-wide meta-analysis of insomnia prioritizes genes associated with metabolic and psychiatric pathways" Watanabe et al. Nat. Genet. 2022

- insomnia_female_ukb2b_EUR_sumstats_20190311_with_chrX_mac_100.txt.gz
  Summary statistics for UK Biobank unrelated EUR female samples
  Sample size: 66,976 cases and 141,982 controls
  Analysis: PLINK 2.0 logistic regression 
  File format:
    SNP: unique SNP ID
    CHR: chromosome
    BP: position
    A1: allele 1
    TEST: tested allele
    NMISS: Sample size
    OR: Odds Ratio
    SE: Standard error of log(OR)
    L95: lower bound of 95% confidence interval
    U95: upper bound of 95% confidence interval
    STAT: Test statistics
    P: P-value
    A2: allele 2
    SNPID_UKB: ID of SNP in UKB dataset
    RSID_UKB: rsID of SNP in UKB dataset
    A1_UKB: A1 allele in UKB dataset
    A2_UKB: A2 allele in UKB dataset
    INFO_UKB: Info score from UKB dataset
    MAF_UKB: Minor allele frequency from UKB dataset
    MAF: Minor allele frequency calcualted for samples included in the analysis


