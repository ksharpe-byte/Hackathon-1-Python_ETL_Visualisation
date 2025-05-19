# ![Kabira's Logo](<Purple and Blue Futuristic Data Analyst LinkedIn Banner.png>)

# Hackathon 1 - Python, ETL and Visualisation

Hackathon 1 is an indivdual formative assesment focused on Python, ETL and Data Visualisation. Various skills will be exercised throughout the project such as data extraction, transformation, loading and data visualisation using Python tools. 

## Dataset Content

This dataset holds anonymised healthcare information regarding individual demographics, location-based variables and medical insurance costs. It aims to offer insights into how the variables contribute to variations in medical costs. 

## Hypothesis and how to validate?

Individuals with a higher BMI, family size and higher in age will have incur greater medical insurance charges, as a stronger correlation will be displayed for those variables.

## Project Plan

### Objectives

* To explore the relationship between personal attributes and geographic factors with healthcare insurance.
* To Extract, Transform and Load the data to ensure it's ready to be analysed.
* To develop visualisations that highlight key insights such as correlations.

### Methodology

* Initial data collection will be done by downloading a dataset, extracting it from a zip file and loading it as a csv file in VS code.
* The loaded dataset will be cleaned in VS code to ensure it is analysis ready & will produce accurate insights. Python code will be used in the Pandas and NumPy libraries. 
* The cleaned dataset will be analysed using Python code in Pandas DataFrames and visualised using Python code in Matplotlib, Seaborn and Plotly. 

Establishing and defining clear objectives guarantee's the analysis stays focused and guides the process. ETL process is followed to ensure all raw data is tranformed into a clean, accurate, complete and usable state. Data visualisation is a great way to translate complex results into clear and intuitive insights. Accurate and comprehensive data visualisation is imperitive when communication key findings to non-technical stakeholders. 

## The rationale to map the business requirements to the Data visualisations

The business needs to understand what factors are having the greatest impact on insurance charges.  

* Identify high-cost customers/patients - A box plot was created to identify any outliers, to identify if a larger number of individuals have high medical charges.
* Understand the distribution of charges - A histogram was used to visualise the distribution of medical insurance charges, providing a clear assessment of the prevalence and impact of higher costs.
* Understand BMI's effect of charges - Scatter plots were used to analyse the relationships between age, BMI, and number of children, assessing their impact on medical insurance charges.

## Analysis techniques used

Descriptive analysis tools were used to summarise and gain a better understanding of the dataset. 
* Exploratory Data Analysis - This was used to understand the data structure and the distributions. However, EDA may not identify all relations which is why I used feature engineering to dig deeper.
* Standard Deviation for Outlier Detection - This was used identify any outliers and asses if there were any extreme medical charges within the dataset.
* Correlations - This was used to assess the relationships between different factors, to identify which ones have the greatest impact on charges.

## Ethical considerations

* Data Privacy - Ensure all data is handled correctly and stored securely as the dataset contains sensitive personal information. I remained compliant with GDPR(EU) throughout. Moreover, all data is anonymised, as the data and findings are accessible on a public platform.
* Unbiased Feature Selection - Features selected for engineering were unbiased and didn't exclude any individuals withn the dataset.
* Pricing model suggestion have been communicated to improve accessibility and equity for all groups.

## Unfixed Bugs

* No unfixed bugs are present.
* Further reading and practice was required to enable me to accurately visualise my findings. A few rounds of troubleshooting was undergone to ensure the clearest visualisations were created. 

## Development Roadmap

* Initial data cleaning posed challenges as I was unsure on the best sequence of steps for the cleaning process. I overcame this challenge by revisitng past learning materials, and compiling a thorough checklist on the steps that needed to be completed.

## Main Data Analysis Libraries

* Python - To create code for Pandas, feature engineering & transformation, data visualisation and reporting.
* Pandas - Data manipulation and analysis, such as loading data, cleaning data and exploring data.
* Matplotlib - To illustrate the distribution of charges amongst all individuals within the data set. 
* Seaborn - To illustrate the distributon of charges amongst individuals with children.
* Plotly - To provide interactive visulations of my findings.

## Credits

* I used Microsoft CoPilot for some code creation and clarification of terminology.
* I used 2x "Data Coach Sessions" walkthoughs to compile myself a checklist of all of the steps needed to start a project and begin data analysis.
* Plotly Topic 3: Plots Part 2 from Code Institutes LMS was used to assit in creating Plotly visualisations.
* Seaborn Topic 3: Seaborn Plots Part 1 from Code Institutes LMS was used to assist in creating a Seaborn visualisation. 
* [Plotly Open Source Graphing Library for Python](https://plotly.com/python/), was used when deciding the appropriate graphs for visualisation.
* Kaggle was used to download the Healthcare Insurance dataset for analysis.
* [GitHub template](https://github.com/Code-Institute-Solutions/da-README-template) by Code Institute was used to outline the structre of my project.
* [Markdown cheat sheet](https://www.markdownguide.org/cheat-sheet/) was used to assist in correctly writing in Markdown language. 

## Media

* The image for the home page was created and downloaded from [Canva](https://www.canva.com/en_gb/)

## Acknowledgements

* Thank you to the Code Institute team who have provided excellent learning, tutorials and support preparing me for my first project - specifically Emma Lamont, John Rearden, Mark Briscoe, Niel McEwen.
* Thank you to my bootcamp cohort for the support and clarity given throughout the project.