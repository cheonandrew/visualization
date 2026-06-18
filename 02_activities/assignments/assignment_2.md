# Data Visualization

## Assignment 2: Good and Bad Data Visualization

### Requirements:

- Data visualizations are important tools for communication and convincing; we need to be able to evaluate the ways that data are presented in visual form to be critical consumers of information 
- To test your evaluation skills, locate two public data visualizations online, one good and one bad  
    - You can find data visualizations at https://public.tableau.com/app/discover or https://datavizproject.com/, or anywhere else you like! 
- For each visualization (good and bad):  
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) why you classified that visualization the way you did.

    
      ```
    I selected two visualizations, both related to global datacenter distribution.
    **Bad visualization**: https://www.voronoiapp.com/_next/image?url=https%3A%2F%2Fcdn.voronoiapp.com%2Fpublic%2Fimages%2Fdb6f9cf1-e5ff-4bef-80f3-49910262f273.webp&w=3840&q=85
    For the purposes of this assignment, I have classified this visualization of "Number of Data Centers by Country" as "bad". 
    
    1. Aesthetic - is the visualization pleasing to look at?
    - The visualization is sleek and easy to look at. The title is direct and clear (`"The world has 11,800 data centers"`), the plot uses easily-discriminable colors to cluster countries by continent, the legibility of text against background is maximized by high-contrast color selections, there is minimal use of unnecessary color variations which helps minimize visual load, there are clear labels for metrics presented (`# of data centers`), font sizes are sufficiently scaled, and inclusion of mini flag icons supports immediate identification of each country code.
    2. Substantive - does the visualization accurately and honestly present data?
    - The visualization technically presents data accurately: the surface area occupied by each country is scaled to its proportion of data centers. Perhaps unintuitively, "Rest of the World" contains countries included in existing continent representations; the cut-off is at the 25th country overall.
    3. Perceptual - can we understand the message?
    - This is where I believe the visualization is lacking most. The positioning and partitioning of the pie chart is unintuitive. There is no clear driving logic to the placement of each proportion, which introduces an unnecessary degree of cognitive load especially when attempting to make comparisons across countries. The picture is clear at the continent level, but not at the country level. The high-level takeaway is that USA has the largest proportion of data centers worldwide, but the lack of hierarchical sorting makes it unclear at-a-glance which countries are next on that list.


    **Good visualization**: https://www.visualcapitalist.com/wp-content/uploads/2025/11/Countries-with-the-most-data-centers-2025.webp 
    From the same source, I have classified this visualization of "The World's Data Centers" as "good". 

    1. Aesthetic - is the visualization pleasing to look at?
    - The visualization is sleek and immediately interpretable. A two-tiered pie chart is used to present the proportion of data centers per continent (inner tier) and per country (outer tier), with the list of countries hierarchically sorted down to a threshold of ~50. The title is specific and clear (`"The World's Data Centers as of November 2025"`), the plot uses easily-discriminable color gradients, the country names are listed in full (no ambiguous abbreviations) with contrasting font color for `number of data centers` to improve legibility, the font sizes are appropriately scaled, and there is overall far less visual load that obstructs the interpretation of this dataset. 
    2. Substantive - does the visualization accurately and honestly present data?
    - The visualization presents data accurately and objectively. There is no alternate-scaling or skew logic used to present each proportion dishonestly. 
    3. Perceptual - can we understand the message?
    - This visualization addresses all the shortcomings of the previous visualization. Each continent is hierarchically-sorted, and each country within each continent is subsequently hierarchically-sorted as well. It is immediately clear which countries have the highest number of data centers per continent, and comparisons across countries are also more immediately visible.


      ```
    - How could this data visualization have been improved?  
      ```
    1. As previously stated, logical organization of proportions or hierarchical sorting would improve the figure's interpretability. 
    2. To extend beyond this simple visualization, which could be misleading without correlated variables relevant to datacenter implementation, there is an opportunity to use color to represent correlated variables such as: datacenter size, data capacity, surface area, population density, electricity demand, tech sector GDP fraction, etc.
      
      ```
- Word count should not exceed (as a maximum) 500 words for each visualization (i.e. 
300 words for your good example and 500 for your bad example)

### Why am I doing this assignment?:

- This assignment ensures active participation in the course, and assesses the learning outcomes
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story

### Rubric:

| Component               | Scoring   | Requirement                                                 |
|-------------------------|-----------|-------------------------------------------------------------|
| Data viz classification and justification | Complete/Incomplete | - Data viz are clearly classified as good or bad<br />- At least three reasons for each classification are provided<br />- Reasoning is supported by course content or scholarly sources |
| Suggested improvements  | Complete/Incomplete | - At least two suggestions for improvement<br />- Suggestions are supported by course content or scholarly sources |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 -  2026-06-09`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (assignment_2.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-2`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
