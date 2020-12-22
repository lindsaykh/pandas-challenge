Heroes of Pymoli

Summary: This jupyter notebook summarizes data for the fantasy game Heroes of Pymoli. The notebook opens the .csv file, which contains the screen names,
	age, and gender for each purchase of optional items within the game. The notebook, using Pandas, analyzes the number of purchases and total revenue, 
	breaks down purchase data by age and gender, and identifies top spenders, the most popular items, and the most profitable items. A summary of three 
	three trends observed by the analysis are included at the end.

Requirements: The notebook analyzes the file purchase_data.csv in the Resources folder within the same directory as the notebook. The file contains columns 
		that include screen name (SN), age, and gender, associated with individual purchases (with purchase item ID number, title, and cost in columns
		as well).

Directions: Once the notebook (HeroesofPymoli.pynb) is opened, after running the results of each analysis will be displayed as output. Analysis details are 
	given below and in the notebook.


### Player Count

* Total Number of Players

### Purchasing Analysis (Total)

* Number of Unique Items
* Average Purchase Price
* Total Number of Purchases
* Total Revenue

### Gender Demographics

* Percentage and Count of Male Players
* Percentage and Count of Female Players
* Percentage and Count of Other / Non-Disclosed

### Purchasing Analysis (Gender)

* The below each broken by gender
  * Purchase Count
  * Average Purchase Price
  * Total Purchase Value
  * Average Purchase Total per Person by Gender

### Age Demographics

* The below each broken into bins of 4 years (i.e. &lt;10, 10-14, 15-19, etc.)
  * Purchase Count
  * Average Purchase Price
  * Total Purchase Value
  * Average Purchase Total per Person by Age Group

### Top Spenders

* Identify the the top 5 spenders in the game by total purchase value, then list (in a table):
  * SN
  * Purchase Count
  * Average Purchase Price
  * Total Purchase Value

### Most Popular Items

* Identify the 5 most popular items by purchase count, then list (in a table):
  * Item ID
  * Item Name
  * Purchase Count
  * Item Price
  * Total Purchase Value

### Most Profitable Items

* Identify the 5 most profitable items by total purchase value, then list (in a table):
  * Item ID
  * Item Name
  * Purchase Count
  * Item Price
  * Total Purchase Value


