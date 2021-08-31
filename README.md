### Version: pGlycoQuant_V1.1
### Release Date: 2021.08.31


## Description
At present, pFind, pGlyco, Byonic and MSFragger software glycosylation identification results can be used for quantification by pGlycoQuant.


## GUI Operation Usage
1. Double-click pGlycoQuant.exe to generate the default config.txt file.
2. Double-click pGlycoQuantUI.exe to import the config.txt file and set parameters.
3. Save the parameter file and click Run to run the pGlycoQuant program.


## Other notes

### Notes for running Byonic result
1. It is found that the name of mass spectrum data recorded by Byonic software is inconsistent with the original data, when running pGlycoQuant in Byonic mode, it should be guaranteed that the name of the mass spectrum data recorded in the Byonic result file is the same as that of the entered mass spectrum data.
2. Byonic glycosylation modification reliable results screening commonly used scores are Score and LogProb, rather than FDR. FDR cannot be modified on the pGlycoQuant interface. To modify B4_THRESHOLD_SCORE_BYONIC and B5_THRESHOLD_PROB_BYONIC in the config file (default: 200 and 2, indicating score≥200 and absolute value of LogProb ≥2)
3. Byonic ini files are required for quantification, in the ./ini/ini_Byonic directory.

### Notes for running MSFragger result
MSFragger ini files are required for quantification, in the ./ini/ini_MSFragger directory.


## Cite us
The pGlycoQuant is not published yet, and we will show how to cite it after publication.
