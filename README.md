# Giddy-s-Car-Inventory 

# Introduction 
This is a monthly sales report of a car inventory, this dataset was gotten from http://studyoffice.org/car-inventory.txt, it was in a Text CSV format so I had to import it to Excel and carried out some tranformation on the dataset. Notably functions performed on the dataset includes;

Import text files into Excel

Formulas to split cells =LEFT=MID=RIGHT

VLOOKUP formula

IF formula

CONCATONATE formula

CHARTS and VISUALIZATION

# Data Transformation
I carried out a few data tranformation by using my DAX funtion to include new columns and measures after carefully studying the dataset. Below are pictorial images that represent step by step on how the dataset was transformed.

This was how the dataset came.
![](view%201.PNG)

Then the MAKE column was extracted from the ID column using the LEFT formula
![](view%202.PNG)

After then the MAKE FULL NAME was extracted using the VLOOKUP formula
![](view%203.PNG)

Then the MODEL was also extracted
![](view%204.PNG)

The MODEL FULLNAME was also extracted usin the VLOOKUP formula
![](view%205.PNG)

Fastforward to the NEW CAR ID using the CONCATONATE FORMULA
![](view%209.PNG)

# Data Insight and VIsualization
The visuals derived from the formatted dataset was

![](Car%20Sales%20Report_page-0001%20(1).jpg)

## Insgights
After meticulously analysing and visualizing the dataset, here are the insights dervied.
1. Average Sales: The average sales for the month is $5,170k, this simply means the sum of sales over the total number of sales made in that month
2. Color: The visuals shows that Black cars are widely requested from buyers, this simply means Giddy Motors should focus more on stocking cars with black colors.
3. Warranty: The visuals shows that cars with warranty was more puchased compared to cars without warranty. Hence, Giddy Motors should ensure they stock cars with warranty as customers prefers that.
4. Model: The Focus model was the most sought after car, Hence, people in that environment prefers Focus, this might be as a result of a lot of factors like, peer pressure, societal influence, social class and the likes.
