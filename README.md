# ☎️ Call Center Analysis Dashboard

An interactive Power BI dashboard analyzing call center performance across channels, sentiment, regions, and call reasons — built to help operations teams monitor SLA response times, spot sentiment trends, and identify high-volume call drivers.


> 📌 **Note:** GitHub can't render `.pbix` files directly since they're binary — use the screenshot above for a quick look, the PDF for a full-page preview, or download the `.pbix` to explore it live in Power BI Desktop.



## 🔍 Overview

This project transforms raw call center log data into a two-page interactive report — a **Dashboard** page for visual trend analysis and a **Grid Overview** page for row-level call detail. It's designed for call center managers who need to track volume, sentiment, SLA response performance, and top call reasons at a glance.

## 🎯 Key Features

**Page 1 — Dashboard**
- **Filters** — Channel, City, and a custom Date range (10/1/2020–10/31/2020)
- **KPI Summary Cards** — Total Calls, Call Duration (Min/Hrs), Avg Call Duration, and Response Time %
- **Total Calls by Day** — Bar chart showing call volume across each day of the week
- **Total Calls by Sentiment** — Bar chart ranking calls from Negative to Very Positive
- **Total Calls by Channel** — Donut chart comparing Call-Center, Chatbot, Web, and Email volume
- **Calls by Call-Centre City** — Bar chart ranking city-level call volume
- **Total Calls by State** — Geo map showing call distribution across the U.S.
- **Reasons for Calls** — Treemap breaking down call drivers (Billing Question, Payments, Service Outage)

**Page 2 — Grid Overview**
- Same KPI cards and filters as the Dashboard page
- **Detail Grid** — Row-level call log with Id, Customer Name, Channel, Reason, State, City, Response Time (SLA status), Call Duration, and Sentiment

## 📈 Key Insights

- **32.94K** total calls handled, with **824.22K** minutes (**13.74K hours**) of total call duration
- Average call duration sits at **25.02 minutes**, with a **75.26%** response time performance
- **Friday** and **Thursday** see the highest call volume (**5.6K** and **5.5K**), while weekday/weekend volume otherwise stays flat around **4.3–4.4K**
- **Negative** sentiment is the most common call outcome (**11.1K** calls), followed by **Neutral** (**8.8K**) — positive sentiment calls are a minority
- **Call-Center** is the leading channel (**11K** calls), followed closely by **Chatbot** (**8K**), **Web** (**7K**), and **Email** (**7K**)
- **Los Angeles** drives the most call volume by city (**13.7K**), more than double **Baltimore** (**11.0K**)
- **Billing Questions** are by far the top call reason (**23K**), dwarfing **Payments** and **Service Outage** (**5K** each)

## 🛠️ Tools & Skills Used

- **Power BI** — Multi-page report design, DAX measures, interactive visuals
- **Power Query** — Data cleaning and transformation
- **DAX** — Call duration, average duration, and SLA response rate measures
- **Data Visualization** — KPI cards, bar charts, donut charts, treemaps, geo maps, and detail grids

## 📁 Repository Contents

`Call Center Dashboard.pbix` Power BI source file — download to open in Power BI Desktop (not previewable on GitHub) |
`Call Center dashboard.pdf` Static PDF export of the dashboard for quick preview |
`README.md` Project documentation |

## 🚀 How to Use

1. Clone or download this repository
2. Download `Call Center Dashboard.pbix` and open it in **Power BI Desktop**
3. Use the **Channel**, **City**, and **Date** filters to explore call trends
4. No Power BI installed? Just view `Call Center dashboard.pdf` or the screenshot above for a quick, no-install preview

## 📬 Connect

If you're a support operations team or customer service agency looking for data-driven insights into call volume, sentiment, and SLA performance, feel free to reach out — I build custom dashboards like this one to turn your call data into clear, actionable decisions.
