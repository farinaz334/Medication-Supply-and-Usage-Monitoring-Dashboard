#Medication Supply and Usage Monitoring Dashboard

This dashboard was created to answer key questions around drug inventory and usage within a hospital setting. The goal was to make the data easy to explore, visually clear, and genuinely useful for decision-makers who need to manage stock, spot risks, and improve operational efficiency.

##Questions addressed in the analysis:

-Which departments consume the most drugs?
-What is the highest inventory level, and which drug does it belong to?
-Which drugs have been imported and consumed but are missing from the warehouse?
-Which drugs are likely to be consumed during a specific period?
-Which drugs have expired but are still in use?
-How much of the warehouse capacity is being used?
-What is the inventory snapshot for drugs at risk (expired or close to expiry)?
-Which drugs occupy the most physical storage space? (Using Pareto analysis)
-Where are the biggest gaps between expected and actual inventory?

##Process:

-Extracted and cleaned multiple Excel sheets containing raw hospital data (in Farsi).
-Standardized formats and converted date systems (Shamsi to Gregorian).
-Built a structured data model with several fact tables and resolved relationship issues (including fixing one-to-one joins and filter flow problems).
-Created calculated columns and DAX measures to support dynamic analysis (such as drug status flags and discrepancy detection).
-Designed the report with a clean layout and added interactivity through slicers, tooltips, and Top N filtering.


##Key insights:

This report uncovered how medication flows across departments and where issues are happening. We saw that a small number of drugs take up a large part of the inventory space, but some of them are underused or consumed irregularly.
We also found expired or nearly expired drugs still being used across several departments, something that should be addressed immediately. A few departments are responsible for the majority of drug usage, which creates an opportunity to better focus inventory efforts.
One of the more concerning findings was the high discrepancy rate for imported drugs. These are typically more valuable and harder to replace, so any mismatch between what was imported and what’s currently in stock needs urgent attention. This suggests that better warehouse tracking tools or policies might be needed.
We also compared estimated vs. actual consumption for a three-month period and found patterns of over- and under-forecasting. Finally, the dashboard shows that the hospital is currently using far less warehouse capacity than is available, meaning there's room to optimize space and stock levels.

###Note:
This project was based on real hospital data from Iran. All data was originally in Farsi. I translated it and built the dashboard in a way that would be understandable for English-speaking users.
