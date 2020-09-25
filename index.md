# NanoSafety cluster Work Group F FAIR maturity indicator analysis

This webpage summarizes the current outcomes of the effort by the European nanosafety community
into establishing more FAIR data sets and databases. For this, it has developed a Jupyter notebook
that applies a previously published approach to measure in initial level of FAIR-ness. This
commnunity is working on establishing additional maturity indicators specific and more relevant
to reuse of the data being analysed and needed for risk governance.

## Current analysis results

| Question | Database | Notebook | MyBinder |
| --- | --- | --- | --- |
| What are the differentially expressed genes between normal subjects and subjects with Parkinson’s diseases in the brain frontal lobe? | [ArrayExpress](https://www.ebi.ac.uk/arrayexpress/) | [FAIR_assessment_2.ipynb](https://github.com/BiGCAT-UM/FAIR_metrics/blob/master/code/FAIR_assessment_2.ipynb) | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/sbonaretti/FAIR_metrics/master?filepath=code%2FFAIR_assessment_2.ipynb)   |
| What is the effect of the WDR45 gene mutation in the brain? | [Gene Expression Omnibus](https://www.ncbi.nlm.nih.gov/geo/) | [FAIR_assessment_2.ipynb](https://github.com/BiGCAT-UM/FAIR_metrics/blob/master/code/FAIR_assessment_2.ipynb) | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/sbonaretti/FAIR_metrics/master?filepath=code%2FFAIR_assessment_2.ipynb)   |
| What can these datasets tell us about nanoscale titanium dioxide (TiO2) toxicity? | [eNanoMapper](http://enanomapper.net/) | [FAIR_assessment_eNanoMapper.ipynb](https://github.com/NanoCommons/wgf-fairdata-analysis/blob/master/FAIR_assessment_eNanoMapper.ipynb) | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/NanoCommons/wgf-fairdata-analysis/master?filepath=FAIR_assessment_eNanoMapper.ipynb)   |
|  | [caNanoLab](https://cananolab.nci.nih.gov/caNanoLab/) | [FAIR_assessment_cnanolab.ipynb](https://github.com/NanoCommons/wgf-fairdata-analysis/blob/master/FAIR_assessment_cnanolab.ipynb) | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/NanoCommons/wgf-fairdata-analysis/master?filepath=FAIR_assessment_cnanolab.ipynb)   |
|  | [ChEMBL](https://www.ebi.ac.uk/chembl/) | [FAIR_assessment_ChEMBL.ipynb](https://github.com/NanoCommons/wgf-fairdata-analysis/blob/master/FAIR_assessment_ChEMBL.ipynb) | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/NanoCommons/wgf-fairdata-analysis/master?filepath=FAIR_assessment_ChEMBL.ipynb)   |
|  | [NanoCommons](https://ssl.biomax.de/nanocommons/cgi/login_bioxm_portal.cgi) | [FAIR_assessment_NanoCommons.ipynb](https://github.com/NanoCommons/wgf-fairdata-analysis/blob/master/FAIR_assessment_NanoCommons.ipynb) | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/NanoCommons/wgf-fairdata-analysis/master?filepath=FAIR_assessment_NanoCommons.ipynb)   |

## Contributing

The Jupyter notebook can be applied to any database, and application to other databases is possible by following the
instructions on [this page](https://github.com/NanoCommons/wgf-fairdata-analysis). Basically, use
[this template](https://github.com/NanoCommons/wgf-fairdata-analysis/blob/master/FAIR_assessment_template.ipynb)
and update the details for the database of your interest.

## Funding

This work received funding from the European Union’s Horizon 2020 research and innovation programme
via NanoCommons Project under grant agreement No 731032, NanoSolveIT Project under grant agreement
No 814572, RiskGONE Project under grant agreement No 814425 and via Gov4Nano under grant agreement
No 814401. 
