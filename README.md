# Covid-19-Dashboard


--------------------------------------------

# PROBLEM STATEMENT

COVID-19 was one of the greatest pandemics in history that ravaged the whole world and kept it at a standstill. Everyone was looking for good metrics. Questions like

How many people have contracted the virus?

How many death cases do we have in my country?

Has anyone recovered?

![image](https://user-images.githubusercontent.com/59745353/174591781-ea6f1b67-ab9f-417c-8e28-b1f223831ba1.png)

This has been one of the biggest questions in the mind of people as at 2020, even till now.

The World Health Organization made a shocking statement, that COVID-19 is here to stay, that sound scary, but it's real.

-----------------------------------------------------------------

# DATA SOURCING

This data was gotten from the Centre For Systems Science and Engineering (CSSE) at Johns Hopkins University. I forked the data from the github repo. The link will be pasted below. Then I scraped the confirmed, recovered and death global cases from the repo to microsoft excel.
![image](https://user-images.githubusercontent.com/59745353/174593054-37ea3b88-de46-42d0-976e-7cd95127b283.png)


------------------------------------------------------------

# DATA TRANSFORMATION

I performed data transformation with Power Query in Microsoft Excel, it was fun progress. I merged the confirmed, recovered and death cases together, and made their individual columns. The 872+ columns were transferred to rows for easy analysis. Then I combined all the 3 queries into a single query called the Consolidated Data.

------------------------------------------------

# DATA ANALYSIS AND VISUALIZATION

Microsoft excel has a high analytical features for analyzing and bringing out data-driven insights from a  dataset. I analyzed the date column, then separated it into Year, Month and Days for full insights. The table were also sorted from ascending to descending other for easy analysis.


![image](https://user-images.githubusercontent.com/59745353/174594378-f38d79c6-df16-4e9b-913e-a052dd06ecc5.png)

I was able to separated the vital columns with pivot table for indepth analysis. Check the Analysis worksheet in the workbook to see it. I analyzed the top 10 countries with highest confirmed cases, the bottom 5 countries with lowest cases. The total number of death, recovered cases and confirmed cases, not excluding recovery rate.

I also used slicers to easily make the dashboard interactive.
------------------------------------------------------------------
# FINDING AND RECOMENDATIONS

This is a very interesting project, I was able to cull out insights easily.

1. We had fewer death cases than confirmed cases.

2. USA, INDIA, BRAZIL, FRANCE and UK are the countries with the top cases sadly.

3. We had more cases in 2021 than in 2020.

4. India championed the highest recovered cases, that's worthy of note.

5. US, Brazil, India, Mexico, and Russia had the highest date numbers sadly.

6. North Korea had the lowest confirmed case

7. We had the highest confirmed cases in May, and the lowest in January, maybe the weather could be a factor.

![image](https://user-images.githubusercontent.com/59745353/174591091-0df1bd68-3741-4e9e-ab41-e9571537c11b.png)

Thanks for staying till this point. Reviews will be appreciated.
--------------------------------------------------------------------------------
