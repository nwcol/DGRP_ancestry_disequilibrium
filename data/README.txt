This directory holds input files for the DGRP ancestry epistasis analysis.

chr_map.txt
Maps chromosome arm string names to numeric codes, e.g. X -> 4.

inverse_chr_map.txt
Similar to chr_map.txt but with columns flipped, e.g. 4 -> X. For renaming
chromosome arms in VCF files.

r6.genome
Table of chromosome/chromosome arm lengths in the release 6 genome assembly.
From Table 2 (release 6 genome assembly) of Santos et al (2014) FlyBase paper.

recomb_r6.txt
Sex-averaged recombination maps, originally from Comeron (2012) but lifted
over from release 5 to release 6.

vcfs/DGRP-3_final_biallelic-new.vcf.gz
Downloaded from the DGRP version 3 website (see ../README.md for link)

vcfs/DGRP_samples.txt
Created with the command
    bcftools query -l DGRP-3_final_biallelic-new.vcf.gz > DGRP_samples.txt

vcfs/ZI_ET_FR_combined_all_num_biallelic.vcf.gz
Ancestral panel genotypes.

