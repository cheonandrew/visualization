*** Figure 1 ***
* Source Data:
https://data.ontario.ca/dataset/covid-19-vaccine-data-in-ontario/resource/274b819c-5d69-4539-a4db-f2950794138c 

> What software did you use to create your data visualization?
* Python ( `pandas` and `matplotlib`).

> Who is your intended audience? 
* General public-health audience interested in COVID-19 ICU cases/trends, particularly Ontarians.

> What information or message are you trying to convey with your visualization? 
* The visualization conveys the reported number of COVID-19 ICU cases in Ontario by vaccination status over time (from August 10, 2021 to June 23, 2022).

* The message this figure conveys is that full vaccination status seemed protective early in the pandemic: early during this period (when the groups being compared were roughly the same size), a greater proportion of ICU patients were unvaccinated individuals, but as the pandemic peaked between January to February 2022, the number of ICU cases for both unvaccinated and vaccinated patients spiked sharply. Partial vaccination status showed the lowest counts throughout.

> What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
* I used a line chart to represent values over time. I used Arial 16-pt font to improve readability, and I set the Title/Axes labels bold to increase visual weight of major information. I increased the line width to make trends more visible. I chose Matplotlib's `Dark2` colormap and picked each individual plotline color for its high-contrast and easy distinguishability across 3 data series. I also boxed the legend to separate the group labels from the plot data. 

> How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
* This visualization is reproducible because the input parameters and processing are deterministic. Python imports the original `.csv` file and converts the date column, selects ICU variables, applies consistent formatting choices, and plots/saves the data (no randomness involved). Anyone with the same dataset and code can recreate the same visualization, and I used free standard open-source packages.

> How did you ensure that your data visualization is accessible?  
* I used large Arial text, bold axis labels, thick lines, boxed legend, high-contrast colormap, and avoided unnecessary complicated math. The plot directly shows the reported ICU counts, a simple raw feature.

> Who are the individuals and communities who might be impacted by your visualization?  
* The visualization could affect how the public/patients/healthcare workers/policy-makers/vaccinated/unvaccinated people understand COVID-19 ICU cases. 

> How did you choose which features of your chosen dataset to include or exclude from your visualization? 
* I included the full date range, but only the three ICU variables. I did not include non-ICU hospitalization variables because this visualization focuses specifically on illustrating the most severe reported hospital outcome in the dataset.

> What ‘underwater labour’ contributed to your final data visualization product?
* The underwater labour included finding the dataset, downloading the `.csv`, checking column names, importing to Python, converting the date column, selecting ICU variables, testing the plot and adjusting formatting until it was easily legible, and making sure the wording doesn't overclaim anything about the data.