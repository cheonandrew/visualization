*** Figure 2 ***
* Source Data:
https://data.ontario.ca/dataset/covid-19-vaccine-data-in-ontario/resource/274b819c-5d69-4539-a4db-f2950794138c 

> What software did you use to create your data visualization?
* Excel.

> Who is your intended audience? 
* General public-health audience interested in COVID-19 ICU cases/trends, particularly Ontarians.

> What information or message are you trying to convey with your visualization? 
* This visualization shows the monthly proportions of reported COVID-19 ICU patients by vaccination status. It shows what percentage of ICU patients each month were unvaccinated, partially vaccinated, or fully vaccinated over time (from August 10, 2021 to June 23, 2022).

> What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
* For this plot, I used a 100% stacked column chart to depict proportions within each month. I used a pivot table to group the data by month to make the chart more interpretable than daily values. I used the same font formatting as the Python figure, including a main title, labelled axes, a boxed legend, and larger text to improve readability.

> How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
* Excel is mostly manual, so it is less reproducible than Python. To improve reproducibility, I used a standard workflow: create a month column to group, build a PivotTable, summarize the three ICU vaccination-status columns by month, and create a 100% stacked column chart. The exact formatting may be harder to reproduce, but the same data summary can be recreated from the original CSV.

> How did you ensure that your data visualization is accessible?  
* I used a simple chart type, high-contrast colors, large readable text, clear labels, and a legend. I also used percentages so the relative composition of each month is easy to compare.

> Who are the individuals and communities who might be impacted by your visualization?  
* The visualization could affect how the public/patients/healthcare workers/policy-makers/vaccinated/unvaccinated people understand COVID-19 ICU cases. 

> How did you choose which features of your chosen dataset to include or exclude from your visualization? 
* I included only the ICU variables for unvaccinated, partially vaccinated, and fully vaccinated patients. I excluded the non-ICU hospitalization variables because this visualization focuses specifically on ICU burden. I grouped the data by month to make the pattern simpler and easier to compare.

> What ‘underwater labour’ contributed to your final data visualization product?
* The 'underwater labour' included converting `.csv` to `.xlsx`, checking the column names, creating the month variable, building the PivotTable, choosing the chart type, formatting the chart, checking that the values were summarized correctly, and writing an interpretation that does not overstate the data.