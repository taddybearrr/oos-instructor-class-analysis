# 📊 On One Studios: Instructor and Class Performance Analysis

## Overview

This project analyzes attendance and revenue data from On One Studios — a community dance studio in the Bay Area — to evaluate class performance, instructor impact, and student engagement. Using data exported from the MINDBODY platform, the goal is to uncover actionable insights that improve class scheduling, student retention, and instructor development.

## 🔍 Objectives

- Identify patterns in class attendance and revenue across time
- Understand which instructors and class types drive the most engagement
- Explore client behavior by time of day and day of the week
- Provide data-driven recommendations to studio stakeholders

## 🧠 Business Questions

- What class types and instructors have the highest average attendance and revenue?
- Are there specific peak hours or days that drive more student engagement?
- Which instructors consistently bring in students, and which need support?
- How do seasonal patterns or time of day affect class performance?

## 🛠️ Tools Used

| Tool        | Purpose                          |
|-------------|----------------------------------|
| **Python (Pandas, Seaborn, Matplotlib)** | Data cleaning, wrangling, exploratory analysis |
| **SQL (Google BigQuery)**            | Filtering, cohort queries, retention analysis |
| **Tableau**                          | Dashboard creation and data visualization     |
| **Google Sheets** (light use)                | Cross-checking reports and data export validation |

## 🗂️ Data Sources

All data was extracted from the **MINDBODY** platform via the following reports:
- Attendance with Revenue
- Sales by Class
- Client Retention
- Instructor Schedules
- Class Signups

> Personally identifiable information, such as client names and instructor identities, has been anonymized in accordance with data privacy best practices.

## 📈 Key Insights

- **KPOP Dance Covers** consistently brings in the highest attendance and should be maintained as a tentpole class.
- **Beginner-level classes** show strong performance during weekday evenings (6 PM–9 PM).
- Certain instructors consistently outperform others in terms of both **revenue per class** and **client retention**.
- **Monday and Friday evenings** show lower engagement — potential areas to test different class types or promotions.

## 📊 Dashboard Preview

Check out the live Tableau dashboard:
🔗 [Instructor and Class Performance Dashboard](https://public.tableau.com/app/profile/tad.racca/viz/OnOneStudiosInstructorandClassPerformanceOverview/InstructorandClassPerformanceDashboard)

## 🧪 Machine Learning Experiments

As a stretch goal, logistic regression and random forest classification models were used to:
- Predict whether a class would meet a minimum attendance threshold.
- Identify features most influential in class performance (e.g., instructor, time of day, class name).

> These models were exploratory and not production-ready, but demonstrate applied knowledge of sklearn pipelines and feature importance analysis.

## 🛤️ Future Enhancements

- Improve retention analysis with refined cohort segmentation
- Build predictive models for forecasting seasonal attendance
- Integrate Looker Studio dashboards for stakeholder-facing reporting
- Extend instructor performance review metrics (e.g., client feedback, tenure)

## 🙋‍♂️ About Me

Hi! I'm **Tad Racca**, a marketing strategist turned data analyst passionate about merging creativity with analytics. I'm currently completing the **Google Advanced Data Analytics Professional Certificate** while building real-world projects like this one. 

If you have feedback, opportunities, or just want to chat — feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/tadracca/).

---

## 📁 Repository Structure

