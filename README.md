COVID-19 Global Data Analysis Project  
This project explores global trends in COVID-19 cases, deaths, and vaccination rates using data from Our World in Data. The analysis focuses on key metrics across selected countries—Kenya, India, and the United States—to understand how the pandemic evolved, how healthcare access influenced outcomes, and how vaccination progress varied.

Project Objectives  
Import and clean COVID-19 global data  
Analyze time trends in cases, deaths, and vaccinations  
Compare key metrics across countries  
Visualize trends using charts and maps  
Communicate findings in a Jupyter Notebook or PDF report 

Project Workflow  
1 Data Collection  
Source: owid-covid-data.csv  
Dataset contains global COVID-19 data including cases, deaths, vaccinations, and population.    

2 Data Loading & Exploration  
Loaded with pandas  
Explored columns: date, location, total_cases, total_deaths, new_cases, total_vaccinations, etc.  

3 Data Cleaning  
Filtered for Kenya, India, and USA  
Converted date to datetime format  
Filled or handled missing values appropriately    
Calculated derived metrics like:  
death_rate = total_deaths / total_cases  
vaccination_rate = people_fully_vaccinated / population   

4 Exploratory Data Analysis (EDA)  
Plotted trends for:  
Total cases  
Daily new cases  
Total deaths  
Death rates    

5 Vaccination Analysis  
Visualized total and relative vaccination rates  
Compared vaccination rollouts among selected countries    

7 Reporting  
Final Jupyter Notebook includes:  
Code cells  
Visualizations  
Markdown narrative  
Key insights 

Key Visualizations  
Line plots for total cases, deaths, and vaccinations  
Death rate trends over time  
Vaccination rate as a percentage of the population  
