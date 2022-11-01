# Data_Visualization
Go here to see a basic dashboard of the project: [Check it out!](https://marcostorrework.github.io/)

## About the Project

This dashboard targets students who are contemplating which major to pursue in their academic journeys. By conveying a full-picture of all the majors available to them in terms of university demographics and also long term impacts, students will be empowered in their decision-making processes. The project's general goal is to convey major categories and individual majors in terms of demographics, popularity, employability (represented by type, and also full versus
part-time employment), and future economic success effectively.

## Project Structure


### Preparation

* [Scoping the Project](https://github.com/analiseb/Data_Visualization/blob/main/Project%20Scoping%20%26%20Goals.pdf)
* [Use Stories](https://github.com/analiseb/Data_Visualization/blob/main/User%20Stories.pdf)
* [Design Specification & User Feedback](https://github.com/analiseb/Data_Visualization/blob/main/Design%20Specifications%20%26%20User%20Feedback.pdf)

### Jupyter Notebooks

* [Data Cleaning & Exploratory Data Analysis](https://github.com/analiseb/Data_Visualization/blob/main/01_cleaning_and_EDA.ipynb)
* [Altair Visualizations](https://github.com/analiseb/Data_Visualization/blob/main/02_altair_visualizations.ipynb)

### Results

* [Final Presentation Slides (powerpoint)](https://github.com/analiseb/Data_Visualization/blob/main/Final%20Presentation%20Slides.pptx)
* [Final Presentation Slides (PDF)](https://github.com/analiseb/Data_Visualization/blob/main/Final%20Presentation%20Slides.pdf)
* [Final Report](https://github.com/analiseb/Data_Visualization/blob/main/Final%20Report.pdf)


## The Dataset

Our chosen dataset is sourced from the FiveThirtyEight database and contains information relevant to college majors for recent university graduates. Taken from the American Community Survey 2010-2012 public use microdata series and contains information on basic earnings and labor force information. Most features are numerical
values of employment status by major, additionally containing features such as sex and type of job.

| Variable Name | Description| Data type |
| :-- | :-- | :-- |
| Major | Major description| Descriptive
| Major_category| Category of major from Carnevale et al| Categorical
| Total| Total number of people with major| Numerical (count)
| Men| Number of men in major| Numerical (count)
| Women| Number of women in major| Numerical (count)
| Employed| Number employed (ESR == 1 or 2)| Numerical (count)
| Unemployed| Number unemployed (ESR == 3)| Numerical (count)
| Full_time_year_round | Employed at least 50 weeks (WKW == 1) and at least 35 hours (WKHP >= 35)|Numerical (count)
| Median_income| Median earnings of full-time, year-round workers| Numerical (real)
| College_jobs| Number with job requiring a college degree| Numerical (count)
| Non_college_jobs| Number with job not requiring a college degree| Numerical (count)
| Low_wage_jobs| Number in low-wage service jobs| Numerical (count)


