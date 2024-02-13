
This is a test task for lipidomics data analysis
xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

Data description.

The df_simplified.csv table contains abundances of lipid features (columns), measured in different mice tissue samples (rows) by liquid chromatography mass spectrometry.  

The data produced by the mass spectrometer have been pre-processed by a specialized software, resulting in the above-mentioned table of detected features. The feature values indicated in the table correspond roughly to the amount of the particular compound found in each of the samples. The data has pre-processed and is ready for downstream analysis. Note that the feature intensities have been log2 transformed before-hand. This mean that a difference of 1 in feature intensity between two samples corresponds to a two-fold increase in the original scale.

The samples_simplified.csv table contains basic description of samples: tissue of origin, as well as the experimental group of the mouse - young or old.

Number of samples:
![image](https://github.com/Annatkachev/test_task_simplified/assets/16876840/1125babe-ee85-404a-9ea1-e3e164ec53ec)


xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

Test task.

The dataset provides you with lipid measurements in three different tissues, blood plasma (PL), brain tissue (prefrontal cortex, PFC) and liver (LIV), for two experimental groups of mice: old and young. 

Your task consists of the following:
1. Assess the statistical differences in lipid abundances between old and young mice for each of the tissue: PL, PFC, LIV.
2. Assess which tissue, of the three, shows greater age-related changes in lipid abundances.
3. Assess whether differences in lipid abundances between old and young mice are similar or different between tissues. Which tissues show more similar changes in lipid abundances to each other? 


For all points, consider including evidence in the form of figures, visualizations, and/or numerical results from statistical tests. Combine all the results into a single file/presentation.
