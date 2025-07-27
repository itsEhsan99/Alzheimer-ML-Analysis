The dataset consisted of 63 participants, including individuals diagnosed with Alzheimer's Disease (AD), those with Mild Cognitive Impairment (MCI), and healthy controls. To enhance the dataset, 200 synthetic data samples were generated using artificial methods.

The key features in this dataset include:

Age: Age of the participant in years.

Gender: Participant's gender.

MoCA_Score / ICA_Score: Cognitive assessment scores. Lower scores generally indicate greater cognitive impairment.

P_Tau_181_Level: Phosphorylated tau-181, a key protein biomarker for AD. Elevated levels are associated with AD pathology.

NfL: Neurofilament light chain, a biomarker indicating neuronal damage.

AB_42 / AB_40: Amyloid-beta peptides. The AB42/AB40 ratio is an important marker in Alzheimer's diagnosis.

AB42_40_Ratio: The calculated ratio of AB42 to AB40, often a stronger indicator than the individual peptide values.

APOE_Status: Apolipoprotein E genotype. The presence of the ε4 allele is a major genetic risk factor for AD.

Family_History_Binary: Indicates whether the participant has a family history of dementia.

Source: Identifies whether the sample is real or synthetically generated.

Data preprocessing and statistical analysis were performed using Pandas, NumPy, and Matplotlib.

In the next step, various machine learning models including Random Forest, SVM, K-Nearest Neighbors (KNN), and others were trained using Scikit-learn. Grid Search was applied to optimize hyperparameters for each model.

Finally, the best-performing model was evaluated using 5-fold Stratified Cross-Validation, and the most influential features in the model's decision-making process were identified using feature importance analysis. This added a level of interpretability to the results.

