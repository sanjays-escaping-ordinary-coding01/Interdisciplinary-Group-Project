## **Interdisciplinary-Group-Project**

Machine Learning project on predicting justifiable Salary for Private and Public Firm Employees

**Directory Structure:**

<pre>
root
├── client_x generate (To produce data free of sensitive information)
|     |
|     └── anonymise_client.py, len_service_change.py
|
├── data_cleaning (Preprocessing scripts for each data)
|   └── payroll_data
│         └── CleaningClient1_4.py, CleaningClient1_5.py, clients_compile.py, data_cleansing_client_extra.py, data_cleansing_clienta.py 
│ 
├── etl (Extract-Load-Transform data)
│   ├── client_1_4
|   |        └── initial_model.py, k_models.ipynb
|   |
│   ├── client_1_5
|           └── Client1_5_ASmethod.py, Gapsquare_EDA_Client1_5.pdf, Gapsquare_KNN_Kmeans_Client1_5.Rmd, Gapsquare_Ridge_Lasso_Client1_5.pdf, KNN_KMeans.ipynb, KNN_KMeans.py, RidgeLassoPCA.py
|   |
│   ├── client_a
|   |       └── eda_stdifference.py, predict_salary_helper.py
|   |
│   └── client_extra
│         └── client_extra_analysis_ola_model.ipynb
│         └── output
│                 └── analysis1.png, analysis2.png, analysis3.png, analysis4.png, analysis5.png, analysis6.png
|
├── eda (Exploratory Data Analysis of each data)
│   └── src
│         └── app.ini, etl.py
│ 
├── data_helper (Anonymous Data Transformation)
│   └── load_transform.py
|
└─ model (Scripts related to feature selection, model creation)
   ├── feature_selection
   |       └── app_client_1_4.ini, app_client_1_5.ini, app_client_a.ini, app_client_extra.ini, fs_client1_5.py, fs_client_etra.ipynb, fs_generic.py
   |
   ├── model_selection
   |      └── app.ini, model_selection.py
   |
   ├──  regressor
   |      └── data_adjustment.py, data_from_postgresql.py, outliers_treatment.py, regressor_model.py, regressor_nn.py
   |
   └── rf_regressor
         └── app_client_1_4.ini, app_client_a.ini, app_client_extra.ini, rf_regress.py
  </pre>

