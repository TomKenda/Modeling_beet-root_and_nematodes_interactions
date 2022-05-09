# Modeling_beet-root_and_nematodes_interactions

In this project we tryed to model the interactions between beet's root and the nematodes to understand how root architecture could affect the nematodes population. We did this by combining, root scan, ImageJ software, CRootBox model and a soil temperature model.

In this project you will find two code file : 

- `LBRAI2219_group4_model_soil-temperature` include all the code to model the soil temperature using the Newtown equation and the temperature data from Charleroi Belgium.
- `LBRAI2219_group4_model_nematod-betterave` include all the code to model the beet roosystem aswell as the nematode population and the intercations between the two.

The CRootBox model is explained in detail in the following paper and can be downloaded from this repository : https://plant-root-soil-interactions-modelling.github.io/CRootBox/ 

*Andrea Schnepf, Daniel Leitner, Magdalena Landl, Guillaume Lobet, Trung Hieu Mai, Shehan Morandage, Cheng Sheng, Mirjam Zörner, Jan Vanderborght, Harry Vereecken, CRootBox: a structural–functional modelling framework for root systems, Annals of Botany, Volume 121, Issue 5, 18 April 2018, Pages 1033–1053, https://doi.org/10.1093/aob/mcx221*

Some parameters were found using the SmaartRoot software (integrated in ImageJ, see source below) combined with beet root scans. For some other parameter we could not find any information in the litterature and thus we had to set them arbitrarly. 

*A Novel Image Analysis Toolbox Enabling Quantitative Analysis of Root System Architecture. Guillaume Lobet, Loic Pages and Xavier Draye, 2011*
