# Breast-Cancer-Survival-Prediction-

The aim of this project was to build numerous classification models using single-cell image mass cytometry (IMC), gene expression, and clinical data to predict the survival status for breast cancer patients. With advancements in high-throughput technologies such as IMC, I wanted to investigate whether using datasets built on this new technology has more predictive power than using a more novel approach. Thus, a comprehensive analysis using cross-validation and model stability was conducted to determine the dataset with the most predictive power.

The best performing model was the logistic model built through stepwise regression. This model had an accuracy of 78% and the lowest level of variablity in k-fold CV relative to the other models. 

Other Key highlights:
-	Utilised ‘spicyR’ to investigate the spatial interaction between cells in breast cancer single cell tissue images 
-	Used statistical analysis to determine which 35,000 genes were differentially expressed genes in patients that survived and those that didn't
-	Developed a model that predicted the survival of a particular subtype (Luminal A) of breast cancer patients with 90% accuracy and 0.53 kappa
