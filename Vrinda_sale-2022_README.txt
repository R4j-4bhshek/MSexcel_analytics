data cleaning
	1.check the correctness of data by going through each column.
	2.check for NULLs and duplicates.
		2.1. Manually look for nulls and duplicates, and misspells in data using table filter feature.
 
Data Processing
	1.Deriving column Age group from Age.=If (column_target>=50,"senior",if (column_target>=30,"adult","teenager")).
		format: =If (condition, if_true_value, else_value)
	2.deriving month form date column.
		format: text(target_column, "MMM")
			MM/M: month in numbers(1-12)
			MMM: month in the characters(eg: Jan,Feb)
			MMMM:month in the characters with full spelling(eg: January)
Data Analysis

	1.pivot table creation:
	2. create pivot of order id and amount as values and month as rows:
	3. create chart of order vs sales and tick secondary axis.
		-> shows sales month wise
		-> show which month has the highest sales(bar chart).
		-> which month got the maximum order(line graph(orange)).

	4. simlilarly there are several wuestion answered for the business representative .
