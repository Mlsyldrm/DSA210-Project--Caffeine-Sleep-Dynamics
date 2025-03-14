# DSA210-Project--Caffeine-Sleep-Dynamics

# Project Overview


For the next month, I'll be looking into how much caffeine I drink affects how well I sleep, especially how long I sleep in the deep stage of sleep.I'm going to track how many coffees I drink, how much caffeine I take in all together, when I drink it, how long I sleep, and how long I sleep in the deep stage. This should help me to find out what my best sleep habits are. I'll use data visualisation and statistical analysis to look for trends and test whether changing my caffeine intake can change my sleep patterns.The approach is simple: record my daily caffeine and sleep data, analyse the relationships between them, and test ideas about which factors have the most significant impact.In the end, I want this project to provide clear, data-driven insights into how I can improve my caffeine habits to improve my sleep quality.

# Objectives

**Understand Sleep Influencers**

I will explore the relationship between caffeine consumption (amount and timing), total sleep duration, and deep sleep quality to identify patterns and potential effects.

**Identify Key Factors**

I will determine which aspects of caffeine intake have the most significant impact on sleep quality and develop strategies to minimize negative effects.

**Data-Driven Optimization**

I will use insights from the analysis to adjust my caffeine habits in a way that promotes better sleep and overall well-being.  

I will apply data science skills to interpret findings, strengthening my ability to apply statistical methods in real-world scenarios.


# Motivation


This project combines two things I'm interested in: sleep science and data analysis.Here's why it matters:

## Personal Well-Being
Sleep is very important for overall health and how well I do every day.I want to understand how caffeine affects my sleep quality so I can make better choices and have more energy and focus.

## Scientific Approach
I want to use real data to see the impact of caffeine on my sleep. This project lets me analyse patterns and make decisions based on evidence.  

## Practical Application
It’s an opportunity to apply data analysis techniques in a real-world context, reinforcing my understanding of statistics, correlations, and visualization.  

## Long-Term Benefits  
The insights gained won’t just help me optimize my sleep—they’ll provide a framework for making data-driven decisions in other areas of health and lifestyle.


# Data Sets

The dataset for this project will be built over several months through daily tracking. Here’s what I’ll be recording:  

### Date  
The specific day of the record.  
### Caffeine Intake 
The number of coffees consumed and total caffeine intake (mg).  
### Caffeine Timing 
The exact times when caffeine was consumed throughout the day.  
### Total Sleep Duration 
The total number of hours slept.  
### Deep Sleep Duration 
The amount of deep sleep recorded (hours).  
### Time Between Last Caffeine Intake and Sleep 
The gap (in hours) between my last caffeine consumption and the time I went to sleep.  

I will log this data daily in an Excel file, ensuring consistency and accuracy in data collection. Any outliers caused by irregular circumstances, such as illness or extreme disruptions to my routine, will be flagged for review.

# Tools and Technologies

In order to analyse and visualise the data effectively, a range of tools and technologies will be employed. The following tools will be used for this project:

### Python 
For data processing, statistical analysis, and automation

### Pandas 
For the structuring, filtering, and manipulation of the dataset

### Matplotlib 
To generate visual representations such as line graphs, bar charts, and scatter plots .Seaborn will be employed for the purpose of generating advanced visualisations.SciPy will be used to perform hypothesis testing and statistical evaluations in order to determine key relationships.

The employment of these technologies will allow the systematic processing of data, the uncovering of meaningful patterns, and the drawing of insightful conclusions.


# Analysis Plan

The analysis plan is outlined as follows:

Data Collection
- The daily Excel records are to be imported into a Pandas DataFrame and preprocessed to handle missing values and ensure consistency in units.
- The dataset is to be structured to facilitate analysis and identification of trends.

Visualisation
- Various visualisations are to be created to explore relationships between caffeine intake and sleep quality, including:

- Scatter plot showing caffeine consumption vs. deep sleep duration.  
  - Heatmap displaying correlations between caffeine intake, sleep duration, and deep sleep.
 -Time series plot tracking sleep trends over time relative to caffeine intake.

**Hypothesis Testing:**
- Evaluation of key hypotheses such as:

- **H0:** Caffeine intake has no significant effect on sleep duration or deep sleep.
- **Hₐ:** Caffeine consumption, particularly timing and quantity, significantly impacts sleep quality.  
The regression analysis will determine the most influential factors.

Trend Analysis

The identification of patterns in sleep data over time will allow for the detection of fluctuations in deep sleep duration.The examination will establish whether caffeine intake late in the day has a stronger effect on sleep compared to morning consumption.

The analysis will investigate long-term changes in sleep efficiency and whether adjustments to caffeine habits lead to improvements.


# LİMİTATİONS

### Data Accuracy:
Sleep tracking relies on data from a smartwatch, which may not be as precise as clinical sleep studies. Small inaccuracies in deep sleep measurement could affect the analysis.

### Sample Size:
Since the project spans only a few months, the dataset may not be large enough to capture long-term patterns or account for seasonal variations in sleep behavior.

### External Factors:
Other lifestyle habits, such as stress levels, screen time before bed, and physical activity, may influence sleep but are not being tracked in this study. This could introduce unaccounted variables affecting the results.

### Self-Reported Data:
Caffeine intake and consumption times are manually recorded, which could lead to slight inaccuracies due to recall bias or unintentional omissions.
