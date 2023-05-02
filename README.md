### Analyze Animal Info in Austin Animcal Center
1.  CSV files
	- Intakes: Information about the intake cases in Austin Animal Center. Contain animal names, animal age, intake type, intake date&time, found location, etc.
	- Outcomes: Information about the intake cases in Austin Animal Center. Contain animal name, animal age, outcome type, outcome date&time, etc.
	- Stray Map: Informtaion about found location of animals.
	
2. Exploratory Data Analysis ([Additional Analysis Using Tableau](https://public.tableau.com/app/profile/jungsoo.lee/viz/AnimalIntakeAnalysis/AnimalTypeIntakeTypeIntakeCondition))
	- Intakes_EDA: Explored Intakes data. Derived several insights such as intake type of aged animals, rate of returned animals, seasonality of adoption. 
	- Outcomes_EDA: Explored Outcome data. Derived several insights such as outcome type of aged animals, rate of returned animals, seasonality of outcome.
	- Intakes_Outcomes_Combined: Merged intake and outcome datasets together using animal IDs and dates from each table.
	- Stray Map: Visualized a map using geocoding.
	
3. Modeling and Evaluation
	- Outcome type Prediction
	- Clustering

* problem 1: due to the size of data, it takes too long to execute some codes
	-> potential solution: use cloud computing -> currently working on how to use AWS
  
  problem 2: data includes categorical features in which there are too many string values
	-> potential solution: group string values in each feature into fewer categories and make the values in categories nominal  

