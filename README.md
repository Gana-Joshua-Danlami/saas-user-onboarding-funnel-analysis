# SaaS User Onboarding Funnel Analysis

This project analyzes user drop-off and time delay patterns during the onboarding process of a SaaS product. We explore where users abandon the signup funnel and how long they take between steps, segmented by plan type (Free, Paid, Trial).

## Business Question

**Where do users drop off during onboarding, and how can we improve the experience to boost activation?**

By identifying friction points and time delays, product teams can optimize onboarding, reduce churn, and drive better user activation.

## Tools Used

- **Python (Google Colab)** : data cleaning and transformation with Pandas
- **SQLite**: lightweight SQL analysis inside Python
- **Tableau Public** : final dashboard and data storytelling

## 📊 Key Insights

- The biggest drop-off happens between **"Connect Payment Method"** and **"Invite Team Member"**.
- **Trial users** have slightly higher early-stage completion, but drop more sharply by the end.
- The **time delay between steps** also increases as users progress, suggesting growing friction or a drop in urgency.
- The final step ("Complete Setup Tutorial") has the lowest completion rate across all plan types.

## 📁 Files in This Repo

| File / Folder | Description |
|---------------|-------------|
| `data/saas_onboarding_funnel_dataset.csv` | Raw user-level dataset |
| `data/funnel_summary.csv` | Step-by-step funnel breakdown |
| `data/time_delay_summary.csv` | Avg time between steps (by plan and step) |
| `saas_onboarding_analysis.ipynb` | Full Google Colab analysis notebook |

## 📈 Tableau Dashboard

🔗 [Click here to view the dashboard](https://public.tableau.com/views/SaaSOnboardingFunnelAnalysis/SaaSOnboardingFunnelAnalysis)

## How to Reuse This Project

1. Clone this repo or download the dataset.
2. Open `saas_onboarding_analysis.ipynb` in Google Colab.
3. Replace the data with your own SaaS funnel data if desired.
4. Export final tables to Tableau for custom visualization.

## 📌 Credits

Built by Gana Joshua Danlami The Analyst.  
Inspired by real-world product analytics use cases.  
If you found this helpful, feel free to ⭐️ the repo or reach out! 
ganajoshuadanlami@gmail.com
