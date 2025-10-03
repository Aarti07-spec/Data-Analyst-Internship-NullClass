# Data-Analyst-Internship-NullClass

DataAnalysts-internship-NULLCLASS
📊 Google Play Store Analytics – Internship Project
📘 Overview
This project is part of my internship tasks, building on the Google Play Store dataset. The goal was to implement advanced analytics and visualization features through Python (Pandas, Plotly) and Jupyter Notebook.

Each task applies specific business rules, filters, translations, and time-based display conditions for dashboards.

📂 Repository Structure
📁 Google-PlayStore-Analytics
┣ 📄 Task1_Grouped_Bar_Chart.ipynb
┣ 📄 Task2_Choropleth_Map.ipynb
┣ 📄 Task3_Dual_Axis_Chart.ipynb
┣ 📄 Task4_Time_Series_Line_Chart.ipynb
┣ 📄 Task5_Bubble_Chart.ipynb
┣ 📄 Task6_Stacked_Area_Chart.ipynb
┣ 📄 README.md
┣ 📄Raw data csv files
┗ 📂 screenshots/

Dataset Source
Dataset is provided by company
you can download it from here: Google play store dataset:https://github.com/Aarti07-spec/DA-internship-NULLCLASS/blob/main/Play%20Store%20Data.csv
Users Review: https://github.com/Aarti07-spec/DA-internship-NULLCLASS/blob/main/User%20Reviews.csv

✅ Tasks Implemented
Task 1 – Grouped Bar Chart
Compare average rating and total reviews for top 10 app categories (by installs).

Filters:

Exclude categories with rating < 4.0.

Exclude apps with size < 10 MB.

Last updated month = January.

Graph visible only between 3 PM – 5 PM IST.

Task 2 – Choropleth Map
Interactive Choropleth map showing global installs by category.

Filters:

Only top 5 app categories.

Highlight categories with installs > 1M.

Exclude categories starting with “A,” “C,” “G,” or “S.”

Graph visible only between 6 PM – 8 PM IST.

Task 3 – Dual-Axis Chart
Compare average installs vs. revenue for free vs. paid apps.

Filters:

Installs > 10,000.

Revenue > $10,000.

Android version > 4.0.

Size > 15 MB.

Content rating = Everyone.

App name ≤ 30 characters.

Graph visible only between 1 PM – 2 PM IST.

Task 4 – Time Series Line Chart
Trend of total installs over time, segmented by category.

Highlight growth areas where installs > 20% month-over-month.

Filters:

App categories starting with E, C, or B.

Reviews > 500.

App name not starting with X, Y, Z and not containing “S”.

Translations:

Beauty → Hindi

Business → Tamil

Dating → German

Graph visible only between 6 PM – 9 PM IST.

Task 5 – Bubble Chart
Bubble chart:

X-axis: App Size (MB).

Y-axis: Average Rating.

Bubble Size = Installs.

Filters:

Rating > 3.5.

Reviews > 500.

Installs > 50k.

Categories: Game, Beauty, Business, Comics, Communication, Dating, Entertainment, Social, Event.

App name should not contain “S”.

Sentiment Subjectivity > 0.5.

Highlights:

Game category = Pink bubbles.

Translations:

Beauty → Hindi

Business → Tamil

Dating → German

Graph visible only between 5 PM – 7 PM IST.

Task 6 – Stacked Area Chart
Stacked area chart: cumulative installs over time (per category).

Filters:

Rating ≥ 4.2.

App name without numbers.

Categories starting with T or P.

Reviews > 1,000.

Size between 20 MB – 80 MB.

Translations:

Travel & Local → French

Productivity → Spanish

Photography → Japanese

Highlight: Increase color intensity when installs > 25% MoM.

Graph visible only between 4 PM – 6 PM IST.

🛠️ Tools & Technologies
Python (Pandas, Numpy, Regex for data cleaning)

Plotly Express (interactive charts)

Jupyter Notebook

Timezone Handling with pytz

📸 Screenshots
Output Charts:
https://github.com/Aarti07-spec/DA-internship-NULLCLASS/tree/main/Charts

🚀 How to Run Locally

Clone the repo:

git clone https://github.com/your-username/Google-PlayStore-Analytics.git cd Google-PlayStore-Analytics

Install dependencies:

pip install pandas numpy plotly pytz

Launch Jupyter Notebook:

jupyter notebook

Open any task notebook and run.

📊 Results
Successfully implemented 6 advanced analytical tasks.

Each chart respects filters, translations, and time-based display rules.

Interactive dashboards ready for reporting & insights.

✨ Submission: This repo is my final internship project submission.
