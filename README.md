# AI Art Survey Paper 

## Data Processing 

#### Raw Full Corpus CSV Data

-All Survey Data: `ai_art_surveydata_anon.csv`

#### Cleaned data 

Creating numeric values for strings, one hot encoding financial compensation question, renaming columns, dropping or coding open response text values, 
- `survey_AI_Art_Paper_DataCleaning.ipynb`

#### Ordinal Logistic Regression Analysis by Variable Combination Type 

- `Ai_Art_Paper_Regressions_3P.ipynb` (3point Likert Scale using compressed Likert where disagree and strongly disagree are compressed to disagree, and strongly agree and agree are compressed to just agree, neutral remains the same) 

#### Kruskal-Wallis Test

Categorical variables with Ordinal variables 

- `AI_Art_Paper_Categorical_to_Ordinal_Kruskal_Wallis_5P.ipynb` 

#### Cochran–Armitage Test 
Ordinal variables with Binary variables 

- `AI_Art_Paper_Ordinal_to_Binary_Cochran_Armitage_5p.ipynb` 
