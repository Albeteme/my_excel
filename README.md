# my_excel
Using the Excel table provided, modify and analyze the data of 4,000 past Kickstarter projects as you attempt to uncover some market trends.


Use conditional formatting to fill each cell in the state column with a different color, depending on whether the associated campaign was successful, failed, or canceled, or is currently live.

Create a new column O called Percent Funded that uses a formula to uncover how much money a campaign made to reach its initial goal.



Use conditional formatting to fill each cell in the Percent Funded column using a three-color scale. The scale should start at 0 and be a dark shade of red, transitioning to green at 100, and blue at 200.


Create a new column P called Average Donation that uses a formula to uncover how much each backer for the project paid on average.


Create two new columns, one called Category at Q and another called Sub-Category at R, which use formulas to split the Category and Sub-Category column into two parts.
![image](https://user-images.githubusercontent.com/75787486/122659791-5f806580-d149-11eb-900a-dc159d297290.png)

Create a new sheet with a pivot table that will analyze your initial worksheet to count how many campaigns were successful, failed, canceled, or are currently live per category.


Create a stacked column pivot chart that can be filtered by country based on the table you have created.
![image](https://user-images.githubusercontent.com/75787486/122659795-6dce8180-d149-11eb-8559-f6d267e60136.png)
Create a new sheet with a pivot table that will analyze your initial sheet to count how many campaigns were successful, failed, or canceled, or are currently live per sub-category.


Create a stacked column pivot chart that can be filtered by country and parent-category based on the table you have created.




The dates stored within the deadline and launched_at columns use Unix timestamps. Fortunately for us, there is a formula that can be used to convert these timestamps to a normal date.


Create a new column named Date Created Conversion that will use this formula to convert the data contained within launched_at into Excel's date format.


Create a new column named Date Ended Conversion that will use this formula to convert the data contained within deadline into Excel's date format.

![image](https://user-images.githubusercontent.com/75787486/122659798-7a52da00-d149-11eb-9968-1605116df762.png)

