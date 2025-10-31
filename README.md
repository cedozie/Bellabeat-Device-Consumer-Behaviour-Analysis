# Bellabeat-Device-Consumer-Behaviour-Analysis
#### Author: Christopher Edozie Sunday
#### Language: R | RMarkdown | ggplot2 | dplyr | tidyr
#### Project Type: Data Analytics & Visualization
#### Stakeholders: Bellabeat Executive Team (CEO, CCO, Marketing Directors).
#### Keywords: Fitbit, Bellabeat, Smart Device, Data Visualization, R Programming
#### Status: Completed

### Project Overview
This project analyzes Fitbit smart device usage data to identitify wellness behaviour patterns among its users. The goal is to uncover trends that can **guide Bellabeat’s marketing strategies and engagement models ** for its products (focusing on  Bellabeat Time Smartwatch). This project is part of the Google Data Analytics Capstone context, extended for open-source demonstration and portfolio building.

### Business Task
Identify key behavioral trends from Fitbit smart device data analysis to provide actionable insights that can guide Bellabeat’s marketing strategies, enhance user personalization, and support sustainable business growth.

### Objectives
- Identify **activity and engagement patterns** across users.  
- Explore **heart rate and BMI segmentation** to reveal health and fitness levels.  
- Discover **time-based and lifestyle trends** that can drive marketing campaigns.  
- Provide **data storytelling** insights that connect user habits to product positioning.

### Project Structure

Bellabeat's_Device_Consumer_Behaviour_Analysis/
    ├── **data**/                    # Raw datasets                                                
    ├── **scripts**/                 # R scripts for cleaning, feature engineering, and plotting   
    ├── 01_data_cleaning.R                                                                         
    ├── 02_feature_engineering.R                                                                   
    ├── 03_visualization.R                                                                         
    ├── **results**/                 # Visual outputs and summary tables                           
    ├── figures                                                                                    
    ├── **reports**/                                                                               
    ├── Bellabeat_Report.Rmd                                                                       
    ├── Bellabeat_Report.html                                                                      
    ├── **README.md**/                                                                             
    ├──.gitignore/                                                                                 
                                                                                        
### Key Analyses
•	User Activity Trends: Daily and weekly activity frequency
•	Sleep Patterns: Sleep duration and efficiency correlations
•	Calories & Steps: Activity intensity vs. energy expenditure
•	Heart Rate Metrics: Resting vs. active heart rate trends
•	Demographics: Probabilistic age and gender distributions

### Data Features Used
| Variable          | Description                                                          |
|-------------------|----------------------------------------------------------------------|
| `date`            | Daily tracking date                                                  |
| `daily_avg_steps` | User’s average daily step count                                      |
| `calories`        | Daily calories burned                                                |
| `sleep_hours`     | Sleep duration per day                                               |
| `heartrate`       | Heart rate (bpm)                                                     |
| `activity_level`  | Categorized into “Highly Active”, “Moderately Active”, or “Sedentary”|
| `bmi_category`    | Classified as “Underweight”, “Normal”, “Overweight”, or “Obese”      |
| `heart_rate_level`| Labeled as “Resting”, “Normal”, “Fat Burn”, or “Cardio”              |

### Key Visualizations
### 1️. Weekly Active Users Patterns by Day
<img src="weekly_active_users_patterns_by_day.png" width="700">
> **Insight:** Activity fluctuates weekly, it peaks mostly on weekends — campaigns should target low-activity periods (midweek when activity dips) with motivational prompts.

### 2. Average Daily Steps by Weekdays
<img src="images/activity_trends.png" width="700">
> **Insight:** Users show fluctuations in activity patterns over weekdays, often peaking on weekends — campaigns should Promote Bellabeat Time features (e.g., step reminders) during low-activity periods to re-engage users

### 3. Steps, Sleep, and Energy Burn Balance
<img src="images/activity_trends.png" width="700">
> **Insight:** User clusters reveal **distinct personas** — target high performers with performance analytics, and low performers with habit-building programs.

### 4. Calories Burned vs Steps Taken
<img src="images/activity_trends.png" width="700">
> **Insight:** Reveals linear relationship between steps taken and calories burned, physical activity directly translates to calorie expenditure — promote Bellabeat’s data accuracy in tracking fitness goals and encourage users to meet step targets.

### 5. Activity Levels by Gender and Age Group
<img src="images/activity_trends.png" width="700">
> **Insight:** Younger users generally walk more, while older groups show steadier habits — target younger users with “performance and tracking” campaigns,  older ones with “balance and wellness” messaging.

### 6. BMI Composition by Activity Level, Gender, and Age Group
<img src="images/activity_trends.png" width="700">
> **Insight:** Shows proportion of overweight users in sedentary groups — campaigns should promote heart-friendly activity challenges for overweight users.

### 7. Sleep Efficiency Distribution by Gender
<img src="images/activity_trends.png" width="700">
> **Insight:** Compares recovery quality across genders — a strong wellness differentiator — campaigns should frame Bellabeat Time as a personalized wellness and recovery assistant, focusing on holistic recovery and mindfulness.

### 8. Sleep Duration by Weekdays
<img src="images/activity_trends.png" width="700">
> **Insight:** Users generally have higher sleep hours during weekends — position Bellabeat Time as a sleep-aware assistant to help balance performance with rest.

### 9. Steps-HeartRate-Calorie-BMI Interaction Map
<img src="images/activity_trends.png" width="700">
> **Insight:** Shows distinct clusters of “performance-driven” vs. “wellness-oriented” users — campaigns should personalize smartwatch content for: (i) High intensity users - emphasizing more on performance tracking, and (ii) Low activity users - promoting habit formation and mindfulness 

### 10. Correlation Matrix of Fitbit Metrics
<img src="images/activity_trends.png" width="700">
> **Insight:** Reveal which Fitbit metrics are most strongly correlated, and the interdependencies of steps ↔ calories ↔ active minutes — campaigns should highlight the integrated nature of Bellabeat tracking — how improved activity affects sleep, calorie burn, and stress levels.

### Insights Summary
•	Weekday patterns show higher activity during mid-week with reduced engagement on weekends.
•	Sleep efficiency is positively correlated with consistent daily activity.
•	Users with moderate daily step goals demonstrate better long-term engagement.
•	Behavioural segmentation suggests opportunities for personalized recommendations via the Bellabeat app.

### Insight-driven Marketing Strategies
| Theme                       | Marketing Opportunity                                                |
|-----------------------------|----------------------------------------------------------------------|
| **Engagement Cycles**       | Launch in-app activity challenges during low-activity months.        |
| **Moderately Active Users** | Offer step milestone rewards and personalized coaching notifications.|
| **Heart Rate Awareness**    | Promote heart-health insights and cardio zone tracking.              |
| **Weight Management**       | Use BMI trends to target campaigns focused on fitness goals.         |
| **Sleep & Recovery**        | Emphasize wellness balance and stress recovery features.             |

### Analytical Tools & Packages
•	**R Programming:** Data cleaning, transformation, visualization, data wrangling, storytelling
•	**Packages:** `tidyverse`, `ggplot2`, `scales`, `RColorBrewer`, `lubridate`, `dplyr`, `knitr`, `viridis`, `corrplot`, `reshape2`, `janitor`, `cluster`, `janitor`, `skimr`, `patchwork`, `factoextra`,  `flextable`, `ggridges` 
•	**RMarkdown:** Reproducible reporting and HTML documentation
•	**Git & GitHub:** Version control and project collaboration

### How to Reproduce
1.	Clone this repository:
git clone https://github.com/cedozie / Bellabeat’s_Device_Consumer_Behaviour_Analysis.git
2.	Open the R project or RMarkdown file in RStudio.
3.	Install required packages:
install.packages(c("tidyverse", "lubridate", "ggplot2", "readr", "knitr"))
4.	Knit the .Rmd file to generate the HTML report.

### License
This project is licensed under the MIT License

### Acknowledgments
Data source: Fitbit Fitness Tracker Data (Kaggle)
Inspiration: Bellabeat Case Study – Google Data Analytics Capstone Project

### Author Details
**Christopher Edozie Sunday, Ph.D.**  
*Data Analyst | Scientific Researcher | R Programming & Visualization*  
📍 Canada  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/c-sunday/)  
> “Empowering data storytelling that drives smarter health tech marketing decisions.”  









