Enis Norman
Bikes Sales Report Breakdown

Bike Buyers:
-Dataset showcasing information related to consumers who have/have not purchased a bike, their marital status, education, gender, occupation, income, daily commute, and so forth.

-Implemented data validation by removing all duplicates from the datasheet before moving forward. This, in turn, allowed for more accurate results and a much cleaner dataset.

Working sheet:
-Additional sheet separate from the main data table. I prefer to create a table from the given data in case any changes are permanently made or a mistake causes the data to change. This way, the initial data is untouched and can be referred to when needed.

-Altered raw data into a table as best practice. Used replace all features to change the following "M" and "S" to "Married" and "Single" respectively.
Changed "F" and "M" to "Female" and "Male" as well for better readability for members that are new to the data, and are unsure what the abbreviations may stand for.

-Changed all numerical values in the "Income" field to Currency, excluding two decimal places and including a thousand-place comma.

-Implemented the following IF function to create age brackets that would make for easier manipulation of data and to group the various ages:

=IF([@Age]>54,”Elder”,IF(@Age]>=31,”Middle Age”, IF([@Age])))

Pivot Table:

-Created Pivot tables to showcase average income by gender, average income by occupation, daily commute, whether or not the user purchased a bicycle, and their age bracket. These were also displayed alongside bar and line graph visuals to further assist with the analysis of the demographic of who is purchasing bikes, who may benefit from the purchase of a bike, and who can comfortably afford a bike.


Dashboard:

-Mockup concept of a dashboard that could be presented and shared amongst team members. This includes the visuals created in the pivot table worksheet, alongside a new pie chart showing the percentage of people who have purchased bikes and their age brackets.
Slicers have been included as well to allow users with access freedom to select from different data factors that could ultimately assist with further business decision making such as, who to market to, who is buying the product, how much they make, if they have children, if they are married, and which region they are located in.
By connecting the slicers to their respective pivot tables, we can see the changes made with each filtered selection in real time.
