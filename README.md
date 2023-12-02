# BreastCancerML
Predicting the recurrence of breast cancer in women by analyzing various factors that can influence the likelihood of the cancer returning. In this project, we experiment with multiple machine learning models in search of a model that best fits the data and has high accuracy.

The data set contains patient records from a 1984-1989 trial conducted by the German Breast Cancer Study Group (GBSG) of 720 patients with node positive breast cancer; it retains the 686 patients with complete data for the prognostic variables. These data sets are used in the paper by Royston and Altman (2013). The Rotterdam data is used to create a fitted model, and the GBSG data for validation of the model. The paper gives references for the data source. 
The Rotterdam dataset contains information about patients with node-positive breast cancer. It includes variables such as hormone receptor status, tumor size, lymph node involvement, histological grade, HER2 status, Ki-67 index, and treatment response, among others. The GBSG dataset serves as a validation dataset for the model developed using the Rotterdam dataset. In this context, the GBSG dataset would include similar prognostic variables for patients with node-positive breast cancer, and it is likely that this dataset was not used in the training phase of the model.
In summary, the paper by Royston and Altman follows a common approach in predictive modeling by using one dataset for model development (Rotterdam) and another for validation (GBSG).
FEATURES:
•	pid (patient identifier):
This column likely serves as a unique identifier for each patient in the dataset. It is used to distinguish between individual records.
•	age (age, years):
Represents the age of the patient in years at the time of data collection. Age is often a significant factor in cancer prognosis.
•	meno (menopausal status):
A binary variable indicating the menopausal status of the patient.
0 = premenopausal
1 = postmenopausal
•	size (tumor size, mm):
Provides information about the size of the tumor in millimeters. grade (tumor grade):
Describes the grade or level of differentiation of the tumor cells
•	nodes (number of positive lymph nodes):
Indicates the number of lymph nodes with cancer involvement. 
•	pgr (progesterone receptors):
Represents the concentration of progesterone receptors in femtomoles per liter (fmol/l).
•	er (estrogen receptors):
Represents the concentration of estrogen receptors in femtomoles per liter (fmol/l). 
•	hormon (hormonal therapy):
A binary variable indicating whether the patient received hormonal therapy.
0 = no
1 = yes
•	rfstime (recurrence-free survival time):
Represents the time in days to the first occurrence of either recurrence, death, or the last follow-up. 
•	status:
A binary variable indicating the patient's status.
0 = alive without recurrence
1 = recurrence or death

EXPLORATORY DATA ANALYSIS (EDA):
Exploratory Data Analysis (EDA) is a crucial step in the data analysis process that involves visually and statistically summarizing the main characteristics of a dataset. The primary goal of EDA is to understand the structure, patterns, relationships, and anomalies within the data


Data Summary:
 
Frequency Distributions: 
Create histograms or frequency tables to understand the distribution of values in each variable.
 
Data Visualization: 
Visualize relationships involving three or more variables using techniques like heatmaps, 3D plots, or parallel coordinates.
 
Correlation Analysis:
Examine the correlation between variables to identify potential relationships. This can be visualized using correlation matrices or scatter plots.
   
EDA is an iterative process, and the insights gained during this phase can inform subsequent steps in data analysis, modeling, and decision-making. It helps analysts and data scientists better understand their data and formulate hypotheses, guiding the development of more accurate and meaningful models.
