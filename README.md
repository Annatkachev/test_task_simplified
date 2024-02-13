# test_task_simplified
This is a test task for lipidomics data analysis
xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

The df.csv table contains intensities of lipid features (columns), measured in different mice tissue samples (rows) by liquid chromatography mass spectrometry.  

The data produced by the mass spectrometer have been pre-processed by a specialized software, resulting in the above-mentioned table of detected features. The feature values indicated in the table correspond roughly to the amount of the particular compound found in each of the samples. The data has not been extensively filtered and may include noisy features.

The samples corresponding to particular tissues are indicated in the sample name, for example, “2018-06-10_rats_MS61_Plasma_pos” is a blood plasma (PL) samples, “2018-0610_rats_MS5_Brain(PFC)_pos” is a sample from the preforntal cortex (PFC), and “2018-06-10_rats_MS1_Brain(CB)_pos” is a sample from the cerebellum (CB). 

In addition to these three tissues, the table includes measurements in so-called blank samples (for example, “'2018-07-10_rats_ExtrBlank-4_pos”). These samples have underwent the same sample preparation and mass spectrometry measurements as the other samples, but no biological material has been added at all. This means that any signal found in these samples represent some sort of contamination or some noise signal falsely detected by the pre-processing software as a lipid feature. 

Note that the feature intensities have been log2 transformed before-hand. This mean that a difference of 1 in feature intensity between two samples corresponds to a two-fold increase in the original scale.![image](https://github.com/Annatkachev/test_task_simplified/assets/16876840/e32d8621-2d34-4627-9a2f-6503d5f429b0)


xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

The dataset provides you with lipid measurements in three different tissues, blood plasma (PL) and two brain tissues, CB and PFC. Aditionally, there are blank samples included in the dataset.

Your task consists of the following:
1. Asses the differences in lipid abundances between CB and PFC, CB and PL, and PFC and PL.
2. Assess whether lipid profiles of CB and PFC  could be considered similar. Same question for PFC and PL, CB and PL.
3. Are there lipids that could be considered “house-keeping” in the brain and blood plasma, i. e. are there lipids with similar abundances in the brain and blood plasma? Defining an arbitrary threshold of your choice, assess the proportion of lipids with similar abundance in the brain (PFC or CB) and PL, lipids with higher abundance in the brain, and lipids with higher abundace in PL.
4. Can you use information from the blank samples for this analysis? How would the results of p.3 change in this case. Explain any obtained results.


For all points, consider including evidence in the form of figures, visualizations, and/or numerical results from statistical tests. Combine all the results into a single file/presentation.
