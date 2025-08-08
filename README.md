Feature Descriptions

Average_Temperature – Average temperature during the crop cycle.

Organic_Manure – Quantity/type of organic manure used.

Soil_Type – Categorical indicator of soil classification.

Field_size – Size of the cultivated field.

Crop_Type – Type of crop being grown.

Climatic_Conditions – Categorical descriptor of climate during cultivation.

Pesticide_Used – Indicates whether pesticides were applied.

Plant_Disease – Presence or absence of plant diseases.

Irrigation_availability – Availability of irrigation facilities.

Natural_calamity – Occurrence of natural calamities affecting crops.

Fertilizers_used – Type/usage of fertilizers.

Fertilizers_cost – Expenditure on fertilizers.

Water_soil_erosion – Impact of water or soil erosion.

Number_doses_week – Number of doses applied per week.

Number_weeks_used—Duration of usage in weeks.

Season – Season during cultivation.

Anonymous_1, Anonymous_2 – Hidden/encoded features with potential predictive value.

Target Variable

Crop_Damage – A numeric indicator representing the severity/extent of crop damage.


Task Requirements:->


Data Preprocessing

Median imputation for missing numeric values.

Constant imputation and one-hot encoding for categorical variables.

Model Development

Baseline Model: Random Forest Regressor for interpretability and non-linear relationship handling.

Enhanced Model: Stacking Ensemble with Random Forest & Gradient Boosting as base models, RidgeCV as meta-model.

Training & Validation

Use an 80/20 train-validation split with 3-fold cross-validation on the training set.

Evaluation Metric

Root Mean Squared Error (RMSE).
