### US_Min_Wage_Trends Data Prep and Visualizations
#### 1. Data_prep_and_compile.ipynb
- Acquires FIPS data and merges it with the file ""Minimum Wage Data_2022.csv"" (the one created from the R notebook) recalculates the effective min rate and effective min in 2022 dollars.
- Saves the pertinent columns to two new CSV files (these new files are now used for the visualizations - eliminates any mixup between the previous two versions of "Minimum Wage Data_2022.csv"
	
#### 2. Historical_State_Min_Wage_2022Dollars.ipynb
- Uses "Effective_Rate_2022_Dollars.csv" to create the visualization
	
#### 3. Living_vs_Min_Wage_2022.ipynb
- Uses "Effective_Rate_2022_Dollars.csv" (and all_living_wage.csv) to create the visualization
	
#### 4. Historical_State_Min_Wage_ActualDollars.ipynb
- Uses "State_Actual.csv" to create the visualization
	
### CSV files
#### 1. Effective_Rate_2022_Dollars.csv
- Created by "Data_prep_and_compile.ipynb"

#### 2. State_Actual.csv
- Created by "Data_prep_and_compile.ipynb"

#### 3. all_living_wage.csv
- Copied and pasted data from https://livingwage.mit.edu/
- Glasmeier, Amy K. Living Wage Calculator. 2020. Massachusetts Institute of Technology. Livingwage.mit.edu.

#### 4. Minimum Wage Data_2022.csv
- Created by "Update_Minimum_Wage_data.ipynb" (updated R code from original Kaggle dataset)
- US Minimum Wage by State from 1968 to 2020. (2020, December 31). Kaggle. Retrieved October 13, 2022, from https://www.kaggle.com/datasets/lislejoem/us-minimum-wage-by-state-from-1968-to-2017
