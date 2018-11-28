# An Analysis of Sociocultural and Temporal Trends in UC Admissions Data

## Authors

Aurum Kathuria, Manan Khattar, Chudi Nnorukam, Melissa Wong, Alice Wu

## Introduction

As freshmen and sophomores currently enrolled in the University of California, Berkeley, all five of us have fresh memories of the trials and tribulations associated with the college admissions process. Once we found out that the UC Infocenter had released comprehensive admissions data for freshmen and transfer students to the UC System going back over twenty years, we decided to explore this dataset for ourselves, wanting to both satisfy our own curiosity about the factors that may have affected our admission to UC Berkeley and also pull out interesting/surprising trends in the data that could be useful for high schoolers like our former selves in understanding exactly where they stand in the admissions process.

## Methodology 

We used the UC admissions (freshmen, transfer, and GPA) datasets available [here][https://www.universityofcalifornia.edu/infocenter/admissions-source-school], and California County Wealth Data available [here][https://datausa.io/profile/geo/california/#economy], as our source data. We conducted all our analysis using Numpy, Pandas, and Matplotlib on Jupyter Notebooks. 

## Exploratory Data Analysis

To start off with understanding the datasets, we posed the following 8 questions: 

1. How many high schools are in each of the datasets? How many years do each of the datasets cover?
2. How many high schools are included in all three of the datasets? How many high schools are included in only 2 of the datasets? How many high schools are included in only one of the datasets?
3. What California counties are most represented in the data? What non-California states are most represented in the data? What other countries are most represented in the data? How does this differ across UC campuses?
4. What high schools have the highest number of freshmen admitted? What high schools schools have the highest number of transfer students admitted? How does this differ across UC campuses?
5. What high schools have the highest freshman admit rate? What schools have the highest freshmen transfer rate? How would would you even calculate these things? :o How does this differ across UC campuses?
6. Of the high schools that have students admitted, which high school has the highest ratio of admitted GPA to enrolled GPA? Of the high schools that have students enrolled, which high school has the highest ratio of enrolled GPA to admitted GPA? Is there a significant (linear) correlation between high school GPA and acceptance into a particular UC campus?
7. What is the relationship between admit rate and admit GPA? (Answer through a visualization) How is this different between the relationship between enrollment rate and enrollment GPA? How does this differ across each UC Campus?
8. How different is the admit rate between different ethnicities? How does this relate to the enrollment rate between different ethnicities? How does this vary between freshmen and transfer students? How does this vary across different campuses?



