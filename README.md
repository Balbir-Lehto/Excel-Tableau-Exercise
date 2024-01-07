# Excel-Tableau-Exercise

This is an initial assignment on using Excel to prepare data and create visualisations using both Excel and Tableau

![image](https://github.com/Balbir-Lehto/Excel-Tableau-Exercise/assets/153186301/8e9c7a9e-44ac-4aa3-a0b7-f19408bbf3b4)

Assignment 1 – Data Story
Scenario
The Data supplied consists of countries GDP per Capita for various years up to and including 2020, this data also contains the rank of the countries by GDP (Rank 1 being the one with the highest GDP). There Is also data on Absolute Smartphone users by country and year, the third set of data is life expectancy at birth for the countries by year (date the information was collated). 
The data in this instance is publicly available and not of a personal nature, therefore data values and parameters do not have to be hidden from the charts. The data has been used to show relationships if any between the data available.

First Task:  
POLICIES AND PROCEDURES:
The use and generation of data has been increasing rapidly with more and more nations increasing the numbers of their population with access to computers and smartphones. There is so much data being produce by people, appliances and others classed as IoT. All this data needs to be processed, managed and used fairly and ethically.
![image](https://github.com/Balbir-Lehto/Excel-Tableau-Exercise/assets/153186301/4d616a95-5a16-4135-b08a-5d81d491e06e)

Fig 1. Volume of data created, captured, copied and consumed worldwide from 2010 to 2020 with forecast upto 2025 

To do this we have laws, policies and procedures in the UK to govern the use of data. The UK government has set out 7 main principles in their data strategy GDPR-General Data Protection Regulation:
•	Lawfulness, fairness and transparency
Data should be processed lawfully, fairly and in a transparent manner in relation to individuals
•	Purpose limitation -Personal data must only be collected for specified, explicit, and legitimate purposes and not further processed in a manner that is incompatible with those purposes.
•	Data minimization -Personal data must be adequate, relevant, and limited to what is necessary in relation to the purposes for which they are processed.

•	Accuracy - Personal data must be accurate and kept up to date.
•	Storage limitation - Personal data must be kept in a form which permits identification of data subjects for no longer than is necessary for the purposes for which the personal data are processed.
•	Integrity and confidentiality (security) - Personal data must be accurate and kept up to date.
•	Accountability - The controller shall be responsible for, and be able to demonstrate compliance with, the above principles.
A guide to the data protection principles | ICO
In UK law the Data protection ACT controls how personal information can be used. The government and companies used by consumers hold a great deal of  very personal information on individuals. This data can, if used incorrectly, put certain social, ethnic, economic groups as risk of discrimination or unfair policy. 
Data protection: The Data Protection Act - GOV.UK (www.gov.uk)

The UK Government has also set out the Government Data Quality Framework: the government has access to very large sets of data on a myriad of issues. The Data Quality Framework is there to ensure Civil Servants can critically discern whether data is trustworthy, useful and for them to manage the data. This framework consists of five principles:
1.	Commit to data quality: Create a sense of accountability for data quality across your team or organization, and make sure that everyone understands the importance of data quality.
2.	Know your users and their needs: Understanding user needs is essential to ensuring that data is fit for purpose.
3.	Assess quality throughout the data lifecycle: Assessing quality throughout the data lifecycle helps ensure that data remains fit for purpose.
4.	Communicate data quality clearly and effectively: Clear communication about data quality helps ensure that everyone understands the quality of the data they are using.
5.	Anticipate changes affecting data quality: Anticipating changes affecting data quality helps ensure that data remains fit for purpose as circumstances change.
(The Government Data Quality Framework - GOV.UK (www.gov.uk))

The above policies and principles are the minimum standards required by the UK government, but other organisations and businesses may have more detailed and robust policies, checks and balances. The NHS for example has strict policies and procedures on how data is stored and especially transmitted across networks both electronically and physically by paper. 
As a Data Analyst, data security, accuracy, quality and storage must be handled with the utmost care and compliance to policies and procedures set out by UK law as well as any additional requirements by the company. Data Analysts may be handling very sensitive data that must be kept confidential and secure throughout the lifecycle of analysis. This is to both protect individuals (or organisations) that data may pertain to as well as remaining within the constraints of the laws on data handling and use.
 
Second Task: 
EXCEL GDP TASKS:
1. Setting Password to protect the Workbook:
After opening The Wealth of Nations Excel file, there is an option to password protect the file by clicking on the “File” tab in the Excel application:
![image](https://github.com/Balbir-Lehto/Excel-Tableau-Exercise/assets/153186301/b7bcd276-1cf2-4c49-afbe-4f323d873765)

2. Highlight column C and change the data to display in British pound symbol:
After Highlighting column C and using right click on the mouse Format Cells, the following popup allows change of number to Currency and show the Currency Symbol:
![image](https://github.com/Balbir-Lehto/Excel-Tableau-Exercise/assets/153186301/b5ec7cd5-930a-4f8d-978d-0f65336a44e9)

3. Turn the GDP sheet into a table:To turn the sheet into a table, place cursor anywhere in the data, press CTRL+T, this will create a table.
4. ![image](https://github.com/Balbir-Lehto/Excel-Tableau-Exercise/assets/153186301/de683379-65c2-4659-9928-874e5d76a209)

5 & 6. Create a Chart that will only display ‘Rank, Country and GDP – Per Capita (PPP): A New Rank column was created for the new 2019 only data, otherwise the graph showed the hidden rows from the top 20 of all years.
6. ![image](https://github.com/Balbir-Lehto/Excel-Tableau-Exercise/assets/153186301/8ed6c112-68c9-4d5a-a1b7-7465e2e2c371)

7 Move Chart to another Sheet: click anywhere in Chart area, this will enable you to see “chart design” Tab to the right of “File” “Home” etc. Click on Chart Design and click on the “Move Chart” option:
 ![image](https://github.com/Balbir-Lehto/Excel-Tableau-Exercise/assets/153186301/f84834b2-9e11-4098-812d-0a15af3c2a77)

8. Create a sort for the top 20 highest ranking countries: This filter was applied to Rank, which was a new Rank 
Column created that only showed Rank for the filtered/visible rows for 2019.

9  Bar Chart showing the top 20 highest ranking countries from 2019. The Chart and table were formatted using the Theme colours/effects options. There were two countries which jointly ranked 20th - Kuwait and Australia. Both countries have been included in the chart and filtered table.
![image](https://github.com/Balbir-Lehto/Excel-Tableau-Exercise/assets/153186301/fb20ef8f-c598-48c0-8f0a-ea9d76a2ba84)

Excel Macro: The excel Macro for ‘Copy’ was created using the developer options tab. The button was created using the shapes option. From the Developer tab the ‘Record macro’ option was used to record the table select and copy which was then stopped and assigned to the button ‘Copy’ that was created. The copied table was saved as instructed. The Print and Copy(sheet) Macros were created the same way. The print Macro takes the user to a print pop up to choose printer and the Copy(sheet) Macro copies the current sheet and renames it i.e. chart-chart(2)

![image](https://github.com/Balbir-Lehto/Excel-Tableau-Exercise/assets/153186301/5468d460-18ec-496f-bcbb-8796db37c586)
![image](https://github.com/Balbir-Lehto/Excel-Tableau-Exercise/assets/153186301/13d4be7a-a9b9-459d-8d4a-8e28f1553001)

![image](https://github.com/Balbir-Lehto/Excel-Tableau-Exercise/assets/153186301/1474b0ea-7940-4d26-b3aa-82d274805be4)

#TABLEAU:
1.	The data was imported into Tableau, for each category the Top 20 countries were only considered for visualisations. The excel files once imported were checked for data type accuracy and corrected (The year column, was number rather than date which had to be changed). 
![image](https://github.com/Balbir-Lehto/Excel-Tableau-Exercise/assets/153186301/6c0bad35-4180-44bd-80d1-93c9af04d658)

2.	The data was imported, and relationships were set. I set the relationship this way as I felt that the GDP was the largest factor affecting both life expectancy and ownership/use of smartphones. This arrangement makes no difference in the outcome of the visualisations. But I felt that it made more logical sense.
![image](https://github.com/Balbir-Lehto/Excel-Tableau-Exercise/assets/153186301/0f7db4c6-6235-4bed-9fe4-5d5f23d40b5c)

3.	In all three tables, GDP, Smartphones and Life expectancy; The Date of information field was originally set as a number, this was changed to a ‘Date’ data type. The other columns were already assigned the correct data types of whole number for rank, decimal for life expectancy and GDP and geographical for country.

4.	Build Charts:
Five charts were built using Tableau. The charts were all filtered for the top 20 by rank by different fields:
![image](https://github.com/Balbir-Lehto/Excel-Tableau-Exercise/assets/153186301/6d4f0b1d-da96-4ccd-a941-bf2de748afc3)

The first chart was filtered to only show the top 20 countries ranked by GDP per capita on a map. I thought that this would be good visual to be able to see patterns for clusters of countries, which may show economic dependency or common gain.
![image](https://github.com/Balbir-Lehto/Excel-Tableau-Exercise/assets/153186301/567612ff-2dc3-4af2-b7b3-8ab8c83640c2)

The second chart is a scatter chart with trend line of GDP per Capita vs life expectancy which is also filtered by GDP top 20 ranked countries. There is not a very strong correlation of GDP on life expectancy seen here. The Trend line is almost flat of the top 20 countries by GDP. There are only 12 represented here as the other 8 have no corresponding data for life expectancy from birth.
![image](https://github.com/Balbir-Lehto/Excel-Tableau-Exercise/assets/153186301/eea9cc05-91f2-41f5-8459-9cae02d28568)

The third chart above is the chart for GDP per Capita vs Smartphone users. This chart is problematic due to the data. There are big outliers like India and China with very large populations in this chart. At first glance there does not seem to be a correlation between GDP per capita and smartphone users. But this is discussed later in the reflective.
![image](https://github.com/Balbir-Lehto/Excel-Tableau-Exercise/assets/153186301/32600a9b-803a-44ad-b2be-449487272618)

5.	For the above visualization Life expectancy at birth vs smartphone users there were null values that were filtered out using the filter data option when clicking on ‘null’. Putting Smartphone users vs life expectancy felt redundant initially. But phones are a tool for education which can positively affect decisions through knowledge on health and how to improve circumstances. There was a clear trend seen in this chart that showed a positive correlation between the two.
![image](https://github.com/Balbir-Lehto/Excel-Tableau-Exercise/assets/153186301/1d005ac2-e8cb-43ba-a86b-611dd295e8cf)

The visualization above is a unfiltered snapshot of stacked column graphs of data on GDP, Life expectancy and Smartphone users by country. There are only 72 countries represented  here that have data for all three fields.
![image](https://github.com/Balbir-Lehto/Excel-Tableau-Exercise/assets/153186301/e98f6f90-5fb1-44bd-8a4d-9d74f9292aba)

The last chart is simply an illustration of the data limitations for the charts and dashboard. While there is a full set of data available for the GDP per Capita, there is much less data for life expectancy and an even smaller amount of data for smartphone users. Many countries are missing from the list which makes direct comparisons for a country across categories difficult.

As an illustration of what can be done on Tableau, a background image has been inserted into three of the charts as faded images. The images in my opinion detract from the graph as they are not from a coordinated or matched series. Finding images available online that were free and not copyrighted limited the images that I could use.  I used the Map Background Images tab within the dashboard view to get access to the image options. The image can be positioned using the data values; In the example below the GDP per Capita is one the x-axis and the start value for the image is 5000(left) and the end value is 65000(right). Similarly, the highest value for the Smartphone users Y axis is 1.6BN(TOP) and the X axis lowest value is 1M(bottom). These values were used in this instance, but any dashboard chart values can be used that are smaller than the data range, but this will result in a smaller or distorted image. But this could be visually useful in some cases. Latitude and longitude can also be used as X Y values here.

![image](https://github.com/Balbir-Lehto/Excel-Tableau-Exercise/assets/153186301/542f8256-c31a-4e3b-b8dc-b06d65f3648f)

6.	Below is the dashboard that was constructed using Tableau. The map of ‘Top 20 Country by GDP per Capita’ serves as a filter for all the other charts within the dashboard. The colour Blind Palette was not available on my version of Tableau in the Marks menu, I used a Colour Blindness friendly palette found online for a type of colour blindness (Tritanopia)
![image](https://github.com/Balbir-Lehto/Excel-Tableau-Exercise/assets/153186301/3785e5a6-e757-42af-a27a-bc0c0411e869)

The map chart acts as a filter by GDP for the whole dashboard.
[wealthofnationsv1 | Tableau Public](https://public.tableau.com/app/profile/balbir.lehto/viz/wealthofnationsv1/WealthofNations?publish=yes)https://public.tableau.com/app/profile/balbir.lehto/viz/wealthofnationsv1/WealthofNations?publish=yes

#Reflective
The assignment has been very useful in experiencing some of the pitfalls that can be met when Analysing data for a Stakeholder. The data itself I felt was problematic for several reasons. Firstly, the data was taken during the height of the Covid pandemic which would not give a realistic picture for future extrapolations. Maybe it would be useful as a snapshot. The data spanned over a few years, meaning it was not possible to make a year-by-year comparison, calculate a delta or percentage change as a more meaningful number than absolute values. The smartphone data was not users per capita therefore very high population countries such as India and China caused a large skew in the data and trend lines. 
Looking at the charts:
![image](https://github.com/Balbir-Lehto/Excel-Tableau-Exercise/assets/153186301/711d815a-ac2e-4060-9242-3519bc0a7301)

As you can see from the table above, in a few of the charts many data points are missing.
The assignment has taught me a great deal about the importance of understanding the data before visualization. I feel my understanding of Excel and tableau has improved greatly. In the GDP task, the requirement was to filter for 2019 and make a chart with the top 20 countries, Excel would still include the countries hidden by the filter, for this a new rank was needed to show the new top 20 within the year 2019. I would have requested a more complete data set, comparing a per-capita value with an absolute(aggregate) I felt would show unrealistic correlations in the data.




















