This project conduct an analysis about Stack Overflow survey dataset to better understanding developer world. Further details can be found from this [blog post](https://vanducng.dev/2020/12/20/Stackoverflow-survey-insights/).

# Installation
To get project up and running, ensure below packages are installed:
* Python 3.x
* plotly==4.14.1
* pandas==1.1.5
* numpy==1.19.4
* jupyter==1.0.0


# Project motivation
Im interested in Stackoverflow data from 2020 to answer the following questions:
1. What are the top priorities of working as a developer professional?
1. What are the top paying coding languages?
1. Understand the correlation between salary with developer type, year of experience?

# File descriptions
There is one iPython notebook available here to showcase work related to the above questions. The Data folder contains the survey data used by this analysis.

# Result
1. Overall, developer prefers to continue working on their technology stack (languages & framework) from more than half of respondents (51.3%). Similar percentage of responses 41.4%-43.9%-44.5%, the three following important factors are company culture, flexible schedule and professional development oppotunities. The least important factors are the financial performance of the organization (11.9%), the specific team they would be working on (11.8%), and the diversity of the organization (6.9%).
2. People working with perl are getting the highest pay at $77.7K which is interesting. Scala is the second highest pay with $76.5K, this language is built for object-oriented & functional programming and widely used in big data processing. Next is Rust with yearly salary of $73.7K which is also the most favorite language in 2020. Go continues to be in the top 5 ($72.2K) with the raise of DevOps in recent years.
3. Overall, as denoted by linear regression line, people tend to have higher salary with more years of experience. Engineering manager and senior executive got highest slary and mostly worked longer compared to the rest (more than 13 years). There are some differences at specific developer roles when we observed that SREs, DevOps and Data Engineer demand signficant high salary compared to other developer roles at the same yearn of experience. Academic researcher, mobile developers tends to get a remarkably lower salary.

# Licensing, Authors, Acknowledgement
Credits must be given to Stack Overflow for the data. Download link [here](https://insights.stackoverflow.com/survey).