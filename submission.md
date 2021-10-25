
# Applied Data Analytics

### Task 1

* Files for this task: 
Wedge_task1

Loads all data into GBQ data set.

Wedge_task1: 
1) Loads files into a Pandas dataset
2) Add columns to files without them
3) Cleans null values for files with weird null values
4) change all data type
5) Place pandas in a dictionary with file name as the key.
6) Connect to GBQ
7) Import each file individually to GBQ to prevent errors.



### Task 2

* Files for this task: 
Wedge_task2

Loads all data into GBQ data set.

Wedge_task2: 
Description of what this file does.
1) Connects to GBQ
2) Make a table of all distinct owners
3) Take a sample from the all owners table
4) Create a table combining the sample owners and all their data
5) Make the step 4 table into a CSV
<!--  Repeat for each file  --> 
	

### Task 3

* Files for this task: 
Wedge_task3

Loads all data into GBQ data set.

Wedge_task3: 
1) Connects to GBQ
2) Query Sales by date by hour, store results in a pandas dataframe
3) Query sales by owner by year by month, store results in a pandas dataframe
4) Query sales by product description by year by month, store results in a pandas dataframe
5) Send all query results to SQL lite.
6) Close database 



## Query Comparison Results

Fill in the following table with the results from the 
queries contained in `gbq_assessment_query.sql`. You only
need to fill in relative difference on the rows where it applies. 
When calculating relative difference, use the formula 
` (your_results - my_results)/my_results)`. 



Query	My Results	Your Results	Diff	Relative Diff
Total Rows	85760139	85,760,139	0	0
January 2012 Rows	1070907	1,070,907	0	0
October 2012 Rows	1042287	1070907	28,620	0.02672501
Month with Fewest	Feb.	Feb.		
Num Rows in Month with Fewest	7578372	6556770	-1,021,602	-0.155808729
Month with Most 	May	May		
Num Rows in Month with Most	7578372	7578372	0	0
Null_TS	0	7123792	7,123,792	1
Null_DT	0	0	0	0
Null_Local	234839	238843	4,004	0.016764151
Null_CN	0	0	0	0
Num 5 on High Volume Cards	14987	14987	0	0
Num Rows for Number 5	460625	460630	5	1.08547E-05
Num Rows for 18736	12153	12153	0	0
Product with Most Rows	banana organic	banana organic		
Num Rows for that Product	908639	908639	0	0
Product with Fourth-Most Rows	avocado hass organic	avocado hass organic		
Num Rows for that Product	456771	456,771	0	0
Num Single Record Products	2741	2769	28	0.010111954
Year with Highest Portion of Owner Rows	2014	2014	0	0
Fraction of Rows from Owners in that Year	0.7591	0.7591	0	0
Year with Lowest Portion of Owner Rows	2011	2011	0	0
Fraction of Rows from Owners in that Year	0.7372	0.7372	0	0

## Reflections

I enjoyed this project. It was a lot of work and I didn't expect to get so many errors when uploading to google big query.

I am most excited that I have now truly worked with big data. 

The hardest part was know what was in each file. Cleaning big data is hard. 