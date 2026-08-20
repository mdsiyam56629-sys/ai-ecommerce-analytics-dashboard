# 🛒 AI E-Commerce Analytics Dashboard

An automated E-Commerce Data Analytics project built using **n8n, Python, JavaScript, Google Gemini AI, and HTML/CSS**.

The workflow takes raw e-commerce data, processes and analyzes it, generates business insights using AI, and produces an interactive analytics dashboard.

---

## 🚀 Project Overview

This project automates the complete data analytics pipeline:

Raw Excel Dataset
        ↓
Google Drive
        ↓
n8n Workflow
        ↓
Data Extraction
        ↓
Python Data Processing
        ↓
Business Analytics
        ↓
Google Gemini AI
        ↓
Interactive HTML Dashboard

---

## ✨ Features

- 📊 E-Commerce sales analysis
- 💰 Net sales and gross sales calculation
- 🛍️ Product performance analysis
- 📦 Order and quantity analysis
- 🔄 Return rate calculation
- ❌ Cancellation rate calculation
- 💳 Payment method analysis
- 🌐 Sales channel analysis
- 📈 Monthly sales trends
- 🏷️ Category-wise sales analysis
- 🏆 Top-performing products
- 🤖 AI-generated business analysis
- 🔎 Interactive dashboard filters
- 📋 Automated data processing using n8n

---

## 🤖 AI Business Analysis

Google Gemini AI analyzes the processed e-commerce data and generates:

- Executive Summary
- Key Findings
- Business Risks
- Opportunities
- Recommendations

This helps convert raw analytics into actionable business insights.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| n8n | Workflow automation |
| Python | Data processing and analysis |
| JavaScript | Dashboard logic |
| HTML/CSS | Dashboard UI |
| Google Gemini AI | AI-powered business analysis |
| Google Drive | Dataset/file storage |
| Excel | Source dataset |

---

## 🔄 n8n Workflow

The workflow contains multiple stages:

1. Webhook receives the request
2. Google Drive downloads the dataset
3. Excel data is extracted
4. Python processes the data
5. Analytics are generated
6. Gemini AI generates business insights
7. Data and AI output are merged
8. HTML dashboard is generated
9. Dashboard is returned through webhook
10. Generated files can be exported and stored

---

## 📊 Dashboard

The dashboard provides:

- KPI cards
- Monthly Sales Trend
- Order Status
- Top 5 Products
- Sales by Category
- Sales by Channel
- Top Performers
- AI Business Analysis

---

## 📁 Repository Structure

```text
ai-ecommerce-analytics-dashboard/
│
├── dashboard/
│   ├── Ecommerce_Analytics_Dashboard_PRO.html
│   └── README.md
│
├── workflow/
│   └── AI-E-Commerce-Data-Analyst-GitHub-SAFE.json
│
└── README.md
