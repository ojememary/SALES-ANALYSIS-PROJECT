# TECH-PH SALES ANALYSIS

## Table Of Content

- [Project Overview](#project-overview)
- [Recommendation](#recommendation)

## Project Overview

### Excited to Share My New Sales Dashboard!

I am thrilled to unveil our freshly created Sales Dashboard, designed to provide real-time insights and drive data-driven decisions. 

Dynamic Visualizations: Instantly track performance with our intuitive charts and graphs.

Key Metrics at a Glance: Sales targets, revenue, growth trends, and more!
Customizable Views: Tailor the dashboard to meet your specific needs.
Interactive Features: Dive deeper into the data with interactive elements.
Illustrative Pictures: Clear visuals to enhance understanding and engagement.

### Data Source

Sales Data: The primary dataset used for this analysis is the "sales_data.xlsl" file,containing information about each transaction made by the company

### Tools
- Microsoft Excel


### Data Cleaning and Preparation
In the initial data preparation task,I performed the following;

1.Data Extracting and Transformation.

2.Data Cleaning and Handling data type.

### Exploratory Data Analysis(EDA)

10 OBJECTIVES
1. What is the total sales?
2. If they want to introduce a new product, what average price range would you suggest?
3. How many units of products did they sell?
4. Is the business growing? If yes, what is the growth rate?
5. Which rep should be fired?
6. Which rep should be appointed a manager in each of the branches?
7. Which rep should be appointed as the general manager?
8. Which product should they import more?
9. Which branch generated the highest sales revenue?
10. Which day of the week do they have more revenue generated?

### Data Analysis
Some DAX formulars I used.

=DIVIDE([cy],[py],1)-1

=IF(CALCULATE([total revenue],SAMEPERIODLASTYEAR(Sheet1__2[Date]))=BLANK(),0,
CALCULATE([total revenue],SAMEPERIODLASTYEAR(Sheet1__2[Date])))

=TOTALYTD([total revenue],Sheet1__2[Date])


### Results and Findings

FINDINGS

General Performance
• The total sales for the 2-year duration under study is $19,628.
• The total number of laptops sold is 2,121.
• The number of staff is 11.
• The number of laptop brands is 5 (HP, Apple, Lenovo, Dell, Compaq).
• The number of branches is 3 (Woji, GRA and Town).
• The business is experiencing an annual growth rate of 12%.
• Total sales in 2014 is $9,258.
• The total sales in 2015 is $10,369.

Product

• In terms of laptop brands, HP generated the highest sale with a total revenue of $9,578.
• HP growth rate increased, sold more in Woji branch, a total of 722 units were sold, and the entire 11 staff participated in the sales generated, with Tolu having the highest sales of $1,934. We also discovered that Tolu only sold HP in 2015.

Branch

• Woji branch generated the highest sales revenue of $11,139.
• Number of staff in Woji branch is 6, they have more sales on Fridays, there is a significant growth in sales in Woji, and a total of 1,199 units were sold in the branch.

Employees

• Emeka generated the highest sales revenue of $3,109. We recommend that he should be appointed the General Manager.
• In Woji branch, we recommend Tolu as the branch manager.
• In GRA branch, we recommend Chioma as brand manager.
• In Town branch, we recommend Uche as the branch manager.
• We recommend that Tonye should be fired because Tonye generated the lowest sales revenue, and Tonye is in Woji branch where we have the top 3 performing staff.

Weekly Performance

• Overall, highest sales were generated on Monday, with a total of $3,515.

### Recommendation

• Branch:

The business has 6 staff in Woji branch and 2 in Town branch, and the total sales Woji ($11,139), and Town ($2,487). The number of staff is one of the reasons why Town has low sales. This trend is also seen in GRA branch. I therefore recommend that more staff be sent to Town. And across all branches, the minimum number of staff should be 5.

• Number of work days: Across all branches, we discovered that the number of days affects the performance of the staff and the branch. We recommend that it be mandatory that all staff work at least 5 days a week, with possible shifts.

• Town branch: The two staff in Town branch (Uche and Tunde), should go for training with the leaders in Woji or GRA branch. Staff rotation will also help to revive the branch.


