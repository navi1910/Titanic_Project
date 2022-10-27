# The Titanic Dataset
The sinking of the Titanic is one of the most infamous shipwrecks in history.
On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” 
RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t 
enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 
passengers and crew.
While there was some element of luck involved in surviving, it seems some groups 
of people were more likely to survive than others.

<img src="https://github.com/navi1910/Titanic_Project/blob/master/data_dictionary.png" width=50% height=50%>

## Project Objective
Complete Statistical analysis of Titanic dataset.

## Methods
- Statistical Analysis
- Data Visualization
- Inferential Statistics
- Feature Engineering

## Technologies Used
- Python
- Kaggle
- Pandas
- scipy.stats
- seaborn

## Procedure
- The data is imported as a Data Frame.
- The data is summarized using `describe`.
- Basic `info` is printed.
- Each variable is analyzed using visualizations.

### Probability and Correlation
The probability of survival with respect to different attributes is analyzed.

Heatmap of Correlation Table of `parch`, `SibSp` and `Survived`

<img src="https://github.com/navi1910/Titanic_Project/blob/master/corr.png" width=50% height=50%>

## Chi-square Tests 
- Null Hypothesis
There is no significance in survival difference among male and female passengers.
- Alternate Hypothesis
There is significant difference in survival among male and female passengers.

|Survived|0	 |1	 |All|
|--------|---|---|---|
|female	 |81 |233|314|
|male	   |468|109|577|
|All	   |549|342|891|

**p-value = 1.1973570627755645e-58
Reject null hypothesis, 
There is significant difference in survival among male and female passengers**

- Null Hypothesis
There is no significance in survival difference among passengers of different class.
-Alternate Hypothesis
There is significant difference in survival passengers among of different class.

|Survived|	0	|1	All		|
|1	|80	|136	|216|
|2	|97	|87	|184|
|3	|372	|119	|491|
|All	|549	|342	|891|

**p-value = 4.549251711298793e-23
Reject null hypothesis, 
There is significant difference in survival among passengers of different Ticket class**

## Highlights
Age Distribution among the Passengers.

<img src="https://github.com/navi1910/Titanic_Project/blob/master/age_dist.png" width=50% height=50%>

Countplot of Passengers who survived

<img src="https://github.com/navi1910/Titanic_Project/blob/master/survived_count.png" width=50% height=50%>

Boxplot for `Age`

<img src='https://github.com/navi1910/Titanic_Project/blob/master/Age_box.png' width=50% height=50%>

Countplot for Cabin

<img src='https://github.com/navi1910/Titanic_Project/blob/master/cabin_countplot.png' width=50% height=50%>

Countplot of Tickets according to class.

<img src="https://github.com/navi1910/Titanic_Project/blob/master/count_ticketclass.png" width=50% height=50%>

Distribution of Ticket Fare

<img src="https://github.com/navi1910/Titanic_Project/blob/master/Ticket_fare.png" width=50% height=50%>

Countplot for `Sex`

<img src='https://github.com/navi1910/Titanic_Project/blob/master/count_sex.png' width=50% height=50%>

Countplot for Siblings and Spouse

<img src='https://github.com/navi1910/Titanic_Project/blob/master/sib_spouse_count.png' width=50% height=50%>
