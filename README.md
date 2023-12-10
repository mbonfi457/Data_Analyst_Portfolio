# Matthew's Data Analysis Portfolio
## About Me
I am a chemical lab technician with a strong chemistry (M.S. Chemistry) and solid math background. After completing my Master's thesis in computational chemistry, I developed an interest in Python and machine learning. I enrolled in multiple data science bootcamps for both Python and R to start my self-teaching journey:

* [Data Science and Machine Learning Bootcamp with R](https://www.udemy.com/course/data-science-and-machine-learning-bootcamp-with-r/)
* [Python for Data Science and Machine Learning Bootcamp](https://www.udemy.com/course/python-for-data-science-and-machine-learning-bootcamp/)
* [The Complete Python Bootcamp from Zero to Hero](https://www.udemy.com/course/complete-python-bootcamp/)

These courses served as the groundwork for my evolving interest in the field!

Fast forward and I've just completed my first semester in the Master of Science in Data Analytics program at Georgia Tech 🐝📚🔬 (OMSA) and am planning on completing the "C-track", or Computational Data Analytics, which focuses on Big Data and Machine Learning! My goal is to become a data analyst or data scientist in tech 🌐, physical sciences ⚛, or business 📈, specifically applying machine learning and AI 🤖.

In this repository, you can find some examples of my data analysis projects in Python, SQL, PowerBI, and R (my favorite). For more information about my background, please check out my [LinkedIn profile here](https://www.linkedin.com/in/matthew-bonfield-m-s-443843179/). I also have some "odds and ends" projects that involve Streamlit and NLP. They're FAR from polished but take it peak if it tickles your fancy.

A fun fact about me is I build my own wristwatches ⌚ Check out my watch page on [Instagram](https://www.instagram.com/protontimepieces/) 

## Projects
### Toxics Release Inventory Data, 2010 - 2021 (PowerBI, R)
<img src="https://github.com/mbonfi457/Data_Analyst_Portfolio/blob/main/Screenshot%202023-11-28%20081243.png" alt="drawing" width="750"/>
I pulled TRI data from [data.gov](https://catalog.data.gov/dataset/toxics-release-inventory-tri) and read it into R. The catch here was that each year has it's own csv file, so the data has to be combined. This is the first PowerBI dashboard I've ever made since I've never needed in my past academic work. You can order by "Number of Releases" and "Releases by State." The fraction of carcinogenic releases is also shown, as well as the top industry sectors and top chemicals (or chemical types) released. The time range (in years) can be changed to select a smaller number of years to view. As someone who works in the chemical industry, I find it interesting to see which types of chemicals are most commonly released in the US, and which companies are the biggest releasers.

I've added a brief exploratory data analysis using R [here](https://github.com/mbonfi457/TRI_data/blob/main/TRI_analysis.R). The dataset has been modified in PowerBI to keep only the more relevant variables including but not limited to company name, carcinogenicity, chemical, state.

*Note that the EPA refers to "chemical releases" as different ways that toxic chemicals from industrial facilties enter the air, water, and land. Releases include spilling, leaking, pumping, pouring, emitting, emptying, discharging, injecting, escaping, leaching, dumping, or disposing into the environment, are can be either intentional or unintentional.*


### New York Motor Vehicle Collisions analysis, 2012 - 2023 (R, R Markdown)
This exploratory data analysis of motor vehicle collision reports from [the City of New York](https://catalog.data.gov/dataset/motor-vehicle-collisions-crashes/resource/b5a431d2-4832-43a6-9334-86b62bdb033f) probes various distributions in search of trends and distributions hidden in these mandated MV-104AN police reports, and I include some ideas as to why some of these trends may exist in the data. I performed this analysis in RStudio a compiled it into a report in R Markdown, which can be found in the [NY_car_crashes repo](https://github.com/mbonfi457/NY_car_crashes).


