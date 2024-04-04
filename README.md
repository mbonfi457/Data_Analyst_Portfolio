# Matthew's Data Project Portfolio
## About Me
I am a chemical lab technician with a strong chemistry and math (M.S. Chemistry) background. After completing my Master's program in computational chemistry, I developed an interest in Python and machine learning. I enrolled in multiple data science bootcamps for both Python and R to start my self-teaching journey:

* [Data Science and Machine Learning Bootcamp with R](https://www.udemy.com/course/data-science-and-machine-learning-bootcamp-with-r/)
* [Python for Data Science and Machine Learning Bootcamp](https://www.udemy.com/course/python-for-data-science-and-machine-learning-bootcamp/)
* [The Complete Python Bootcamp from Zero to Hero](https://www.udemy.com/course/complete-python-bootcamp/)

These courses served as the groundwork for my evolving interest in the field!

Fast forward and I'm almost through my second semester in the Master of Science in Data Analytics program at Georgia Tech 🐝📚🔬 (OMSA) and am planning on completing the "C-track", or Computational Data Analytics, which focuses on Big Data and Machine Learning! My goal is to become a data analyst or data scientist in tech 🌐, physical sciences ⚛, or business 📈, specifically applying predictive modeling.

In this repository, you can find some examples of my data analysis projects in Python, SQL, PowerBI, and R. For more information about my background, please check out my [LinkedIn profile here](https://www.linkedin.com/in/matthew-bonfield-m-s-443843179/). I also have some "odds and ends" projects in some of my other repos. They're FAR from polished but take a look if you feel so inclined.

A fun fact about me is I build my own wristwatches ⌚ Check out my watch page on [Instagram](https://www.instagram.com/protontimepieces/) 

## Projects
### [Toxics Release Inventory Data, 2010 - 2021](https://github.com/mbonfi457/TRI_data/blob/main/TRI_analysis.R) (PowerBI, R)
<img src="https://github.com/mbonfi457/Data_Analyst_Portfolio/blob/main/Screenshot%202023-11-28%20081243.png" alt="drawing" width="750"/>
I pulled TRI data from [data.gov](https://catalog.data.gov/dataset/toxics-release-inventory-tri) and read it into RStudio. The catch here was that each year has it's own csv file, so the data has to be combined. This is the first PowerBI dashboard I've ever made since I've never needed in my past academic work. You can order by "Number of Releases" and "Releases by State." The fraction of carcinogenic releases is also shown, as well as the top industry sectors and top chemicals (or chemical types) released. The time range (in years) can be changed to select a smaller number of years to view. As someone who works in the chemical industry, I find it interesting to see which types of chemicals are most commonly released in the US, and which companies are the biggest releasers.

I've added a brief exploratory data analysis using R, which can be found in my TRI data repo. The dataset has been modified in PowerBI after the fact to keep only the more relevant variables including but not limited to company name, carcinogenicity, chemical, state.

*Note that the EPA refers to "chemical releases" as different ways that toxic chemicals from industrial facilties enter the air, water, and land. Releases include spilling, leaking, pumping, pouring, emitting, emptying, discharging, injecting, escaping, leaching, dumping, or disposing into the environment, are can be either intentional or unintentional.*


### [New York Motor Vehicle Collisions analysis, 2012 - 2023](https://github.com/mbonfi457/NY_car_crashes) (R, R Markdown)
This exploratory data analysis of motor vehicle collision reports from [the City of New York](https://catalog.data.gov/dataset/motor-vehicle-collisions-crashes/resource/b5a431d2-4832-43a6-9334-86b62bdb033f) probes various distributions in search of trends and distributions hidden in these MV-104AN police reports, and I include some ideas as to why some of these trends may exist in the data. Location data was also plotted on a Carto OpenStreetMap with the ```leaflet``` package, and the ```sf``` package was used to generate an ```sf object``` needed for plotting. This was my first time plotting location data on a real map so it was pretty exciting for me to learn.
I performed this analysis in RStudio a compiled it into a report in R Markdown.

<p float="left">
  <img src="https://github.com/mbonfi457/Data_Analyst_Portfolio/blob/main/Screenshot%202023-12-13%20113926.png" width="350" />
  <img src="https://github.com/mbonfi457/NY_car_crashes/blob/main/death_animated.gif" width="600" height="350" /> 
</p>

I also had fun playing around with the ```gganimate``` package by making this animated gif, which plots the number of collision-related deaths in each borough over time.
I believe that plotting these accidents and related deaths could be useful for determining the best locations for emergency service stations or patrols to be staffed. Minimizing the arrival time of EMS and police may reduce the chances of a victim succumbing to injuries.

### [Mega Millions Lotto Numbers, 2002-2023 (Python, Jupyter, Time-series forecasting)](https://github.com/mbonfi457/lotto_numbers)
This is an older analysis I had performed when data science was merely a hobby interest. You'll find here a simple analysis of winning number distributions that span over two decades. I also tried my hand at applying the ```FB Prophet``` model, a triple-exponential forecasting algorithm in the ```prophet``` package. Splitting the data into training and testing sets, I was able to generate predictions of future drawings for each lotto number. I learned that you cannot reliably predict randomly drawn numbers with any significant accuracy, but this trial served as a good hands-on exercise for applying a machine-learning algorithm.

<img src="https://github.com/mbonfi457/Data_Analyst_Portfolio/blob/main/Screenshot%202023-12-13%20171135.png" width="600" />
<img src="https://github.com/mbonfi457/Data_Analyst_Portfolio/blob/main/Screenshot%202023-12-13%20171134.png" width="600" /> 

