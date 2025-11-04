# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  

Dataset chosen fot this assignment:
    URL- https://data.ontario.ca/dataset/private-career-colleges-pcc-key-performance-indicators/resource/799f29b1-1031-4e14-b3bf-01ee811e9129
    Title- Career college key performance indicators for the year 2022

- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?
       
        The first visualization is created by coding in Python (using Pandas, Matplotlib). The second visualization is produced using Microsoft excel.

    > Who is your intended audience? 
       
        1. Regulators and policymakers- such as Ontario's Ministry of Colleges and Universities- who monitor private colleges performance on Key Performance Indicators (KPIs) like graduation, employment, and satisfaction rates.
        2. Prospective students and the public-  to help them make informed decisions about which colleges or programs to attend, using transparent performance data.
        3. College administrators and stakeholders- to benchmark their institution's performance against other results and identify areas for improvement.

    > What information or message are you trying to convey with your visualization? 
       
        Python Chart- "Average KPI Values Across All Colleges":
            Purpose: To show the average performance of colleges across major KPIs (graduation, employment, satisfaction, and loan default).
            Message: Overall, colleges demonstrate high satisfaction and employment outcomes (around 80- 90%) and low OSAP default rates, indicating strong student success and employer approval.
        
        Excel Chart- "Count of Graduate Employment Rate in the Field of Study:
            Purpose: To show how many programs fall under each Program Type category.
            Message: There are variations in data representation across program areas, with certain types (like Business, Health Services, and Human Services).

    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
        
        Python visualization
            A bar chart was chosen to make differences between KPI averages visually clear and easy to rank. All bars are in the same color (blue) to emphasize value comparison rather than categorical distinction. Y-axis ranges from 0 to 1 to represent KPI percentages as comparable ratios. Axis titles and the chart title clearly communicate that values represent averages across colleges.

        Excel visualization
            A pie chart was chosen to clearly show how each Program Type contributes to the overall dataset. Each program type is represented with a distinct color to visually separate categories and make the chart easier to interpret. Labels and legends were formatted for clarity, using concise text and consistent font sizes to enhance readability. 

    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
        
        Python visualization: The entire notebook along with visualization is reproducible, because each step is documented, coded using Python (saved as python_code.ipynb) in a Jupyter notebook. Anyone can download the file, run the notebook and regenerate the exact same visualization.

        Excel visualization: This lacks full reproducibility because Excel don't track or provide a log with all the steps taken to generate a visualization from raw data. 

    > How did you ensure that your data visualization is accessible?  
        
        Both the visualizations-  had Clear labeling including all axes, titles, and legends such that viewers can understand what each value and category represents without prior context. A simple and high-contrast color palette (e.g., blue tones) was used to ensure readability for users. Fonts and label sizes were chosen to remain legible even when charts are viewed in smaller formats or projected. Missing or blank categories were displayed to maintain honesty in data reporting and help users interpret results accurately.
    
    > Who are the individuals and communities who might be impacted by your visualization?  
        
        Prospective students, college administratives, lecturers, professors, government policy makers, employers.

    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
        
        Bar Chart in Python- Average KPI Values Across All Colleges (2022)
        Included features for KPI categories: Employer Satisfaction, Graduate Employment Rate, Graduate Satisfaction, Graduation Rate, Graduate Employment Rate in Field, and OSAP Default Rate.
        These are the key performance indicators (KPIs) used by Ontario colleges to evaluate institutional success.  The mean of each KPI across all colleges in 2022, providing a high-level comparison of institutional performance metrics.

        Excluded features: Program-level or college-level data were excluded to keep the focus on system-wide averages rather than individual institutions or disciplines. Percentages/average rates were preferred since they allow for easier cross-comparison between different KPIs.

        Pie Chart in excel-Graduate Employment Rate by Program Type
        Included features for Program Type because this categorical variable was chosen to show how graduate employment rates in the field of study (e.g., Business, Health Services, Industrial Trade). Graduate Employment Rate (count): This metric reflects how many graduates in each program type found employment in their field, a key measure of program effectiveness.
        Excluded features: Other KPIs (e.g., satisfaction rates, OSAP default rates) weren't included because the focus of this visualization was to compare employment outcomes across program types, not overall institutional performance.

    > What 'underwater labour' contributed to your final data visualization product?
        
        In Python, I focused on data cleaning, preparation, filtering, and selection- removing missing or inconsistent values, organizing the dataset, and selecting only the relevant features needed for analysis. This groundwork allowed me to generate accurate and meaningful insights for the bar chart visualization.

        In Excel, my work centered on data transformation, visualization design, and testing. I reformatted and aggregated data to create summaries suitable for charting, experimented with different visual formats (such as pie charts), and refined elements like colors, labels, and legends to make the results visually clear and engaging.

        Together, these steps formed the essential "underwater labour"- the foundational, behind-the-scenes work that made the final visualizations accurate, readable, and effective.

- This assignment is intentionally open-ended - you are free to create static or dynamic data visualizations, maps, or whatever form of data visualization you think best communicates your information to your audience of choice! 
- Total word count should not exceed **(as a maximum) 1000 words** 
 
### Why am I doing this assignment?:  
- This ongoing assignment ensures active participation in the course, and assesses the learning outcomes: 
* Create and customize data visualizations from start to finish in Python
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story  
- This would be a great project to include in your GitHub Portfolio – put in the effort to make it something worthy of showing prospective employers!

### Rubric:

| Component         | Scoring  | Requirement                                                                 |
|-------------------|----------|-----------------------------------------------------------------------------|
| Data Visualizations | Complete/Incomplete | - Data visualizations are distinct from each other<br>- Data visualizations are clearly identified<br>- Different sources/rationales (text with two images of data, if visualizations are labeled)<br>- High-quality visuals (high resolution and clear data)<br>- Data visualizations follow best practices of accessibility |
| Written Explanations | Complete/Incomplete | - All questions from assignment description are answered for each visualization<br>- Explanations are supported by course content or scholarly sources, where needed |
| Code              | Complete/Incomplete | - All code is included as an appendix with your final submissions<br>- Code is clearly commented and reproducible |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 11/02/2025`
* The branch name for your repo should be: `assignment-3`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_3.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-3`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
