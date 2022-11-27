# US_Min_Wage_Trends
Data_prep_and_compile.ipynb	"acquires FIPS data and merges it with the file ""Minimum Wage Data_2022.csv"" (the one created from the R notebook)
recalculates the effective min rate and effective min in 2022$
saves the pertinent columns to two new CSV files (these new files are now used for the visualizations - eliminates any mixup between the previous two versions of ""Minimum Wage Data_2022.csv"")"
	
min_wage_bluegrey_next.ipynb	uses "Effective_Rate_2022_Dollars.csv" to create the visualization
	
Living_vs_Min_wage_red_next.ipynb	uses "Effective_Rate_2022_Dollars.csv" (and all_living_wage.csv) to create the visualization
	
Actual_rates_next.ipynb	uses "State_Actual.csv" to create the visualization
	
	
CSV files	
Effective_Rate_2022_Dollars.csv	created by "Data_prep_and_compile.ipynb"
	
State_Actual.csv	created by "Data_prep_and_compile.ipynb"
	
all_living_wage.csv	needed for living vs min comparison (is there a notebook for the creation of this?)
	
Minimum Wage Data_2022.csv	created by "Update_Minimum_Wage_data.ipynb"
