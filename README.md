# VKOR abundance and activity score analysis
  
This repository houses the files needed to recreate the anaylses required for the manuscript "Multiplexed measurement of variant abundance and activity reveals VKOR topology, active site and human variant impact." The "VAMP-seq_analysis.Rmd" R Markdown file is intended to be run with R Studio. This R markdown file will go through the processes of analyzing the data for the VKOR manuscript, using 2 files as the starting point. These files are the VKOR variant abundance and activity score data tables, as well as the VKOR and TPMT positional score data tables. These files were provided as supplementary data files from the journal, and can also be obtained at our GitHub repo. Please place these files in the same directory as this R Markdown file to allow the analyses to proceed:

1) "VKOR_variant_data.tsv"
2) "VKOR_positional_data.tsv"
3) "TPMT_variant_data.tsv"
4) "PTEN_variant_data.tsv"
  
Furthermore, create a directory titled "Output" in the same directory as this R Markdown file to create the graphics files used to generate the figures.
  
Notably, once run, this R Markdown will also create a series of ".pml" files in the "Output" directory. These ".pml" files can be loaded into PyMOL to start interactive sessions with the scores overlaid on the VKOR homology model.
  
<br />
  
### VKOR Protein Variant Abundance and Activity Scores Academic License Agreement
  
The University of Washington hereby allows User and Institution to search, download, copy or use VKOR Variant Abundance and Activity Scores on the following conditions:
  
1. The scores are being made available here for non-profit, non-commercial uses only. If User wishes to use VKOR variant abundance and activity scores, derivatives of VKOR variant abundance and activity scores, or the data on which they are based, for any commercial or for-profit purpose, please contact the corresponding authors. Low-cost or no-cost licenses will be extended for commercial or for-profit uses, contingent on the engagement of the licensing entity in best practices specified by ClinGen for VKOR variant data sharing.
  
2. The University of Washington owns the intellectual property for VKOR variant abundance and activity scores. In any reposting of the scores or their derivatives, User agrees to retain the copyright, trademark, or other notices pertaining to VKOR variant abundance and activity scores as provided by UW associated with the VKOR variant scores. Use of the copyright in any printed excerpts shall include the following notice (or the equivalent thereof): 'VKOR variant abundance and activity scores are the copyright of the University of Washington.'
  
3. Any risk associated with using VKOR variant abundance and activity scores by User is with User and Institution. VKOR variant abundance and activity scores are experimental in nature and is made available as a research courtesy 'AS IS,' without obligation by the University of Washington to provide accompanying services or support. The VKOR variant abundance and activity scores are for informational purposes only, and is not intended to be a substitute for professional medical advice, diagnosis, or treatment. UW and the developer expressly disclaim any and all warranties regarding the VKOR abundance and activity scores, whether expressed or implied, including but not limited to warranties pertaining to non-infringement, merchantability or fitness for a particular purpose.
  
<br />
