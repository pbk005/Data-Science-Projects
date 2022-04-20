DIABETES PREDICTION

According to National Diabetes Statistics Report more than 1.5 million people die each day worldwide. Diabetes is caused mainly due to high glucose/sugar levels in the blood. After analysis, some of the features which leads to high sugar levels are discussed below
1. tx -	On Insulin or Diabetes Meds
2. dx -	Diagnosed with DM or Pre-DM
3. tri - Triceps Skinfold
4. sub -	Subscapular Skinfold
5. gh -	Glycohemoglobin
6. bun -	Blood urea nitrogen
7. SCr	Creatinine

The NHANES dataset is taken from UCI machine learning repository. A classification task is carried out which deals with diabetes prediction. 

Steps which have been carried out:
1. Feature engineering and analysis -  Data Cleaning and removing outliers, null values, duplicates.
2. The correlation matrix is generated and a heatmap is plotted as a part of EDA.
3. Data visualization of various features is plotted using bar graphs, scatter plots, histograms for better understanding of the data
4. Feature scaling operation is performed to normalize the range of independent features which is a pre-processing step.
5. ML algorithms are trained on the dataset and the outputs are predicted.
6. Accuracy score of each model is calculated and subsequently the k fold cross validation is performed.
7. The confusion matrix is plotted for each model and the classification report is generated.   
