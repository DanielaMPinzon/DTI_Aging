# DTI_Aging
Scripts related to the DTI analysis related to the functional values 


Script: regression_analysis_volumeparam.ipynb
Analysis of the Gray Matter volume in Postcentral and precentral regions in Righ (rh) and Left (lh) hemisphere. 
To analyze volumes I perform a normalization of the value, diving the ROI volume / intrcranial total volume. 
out of curiosity i added ROIs: White matter volume of 5 regions of the CC
First, an initial analysis of multiple regression is done  to predic JND and IHD. 
Second, a Mediation model analysis. age (x) ---> JND (Y) => is this relation mediated by structural factors? (Volume or FA in CC ROIs)
for this part I included the FA values evaluated in 7 ROIs manualy drawn at the midline of the corpus callosum. 
