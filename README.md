## 📌 Overview

Quick Service Restaurants process thousands of daily orders, leaving valuable cross-selling and supply-chain patterns hidden in Point-of-Sale (POS) logs. QSR Data Mining Intelligence is a lightweight, zero-dependency analytics interface built to bridge raw data mining outputs with day-to-day store operations[cite: 1, 2].

Instead of static reports, store managers get an actionable command center that connects daily sales velocity, warehouse depletion, and Apriori association rules directly to POS menu bundling[cite: 1, 2].

Colab Code Link 🔗 https://colab.research.google.com/drive/1joJ_yeRAlc0MbD3B7S3PCKDjB26px3ay?usp=sharing

## ✨ Core Modules and Capabilities

| Module | Business Problem Solved | Key Functionality |
| :--- | :--- | :--- |
| 📊 Executive KPI Cards | Instant health check of store unit economics | Tracks Total Revenue YTD ($1,245,670), Avg Order Value ($14.32), Total Transactions (86,984), and Avg Basket Size (2.4 Items) with period-over-period trend indicators |
| 📈 Restaurant Sales Analysis | Spotting revenue dips and weekly momentum | Responsive custom SVG area and line chart tracking daily sales across multi-week windows with timeframe filtering (Last 30 Days, Last Quarter, Year to Date) |
| 📦 Warehouse and Inventory | Preventing stockouts during peak hours | Visual depletion meters highlighting critical low-stock items (such as Chicken Breasts at 95 units) with one-click restock order triggers |
| 🛒 Market Basket Analysis | Discovering what customers buy together | Surfaces Apriori association rules (Antecedent to Consequent) ranked by Confidence (%) and Lift score |
| 🍟 Combo Meal Recommendations | Increasing Average Order Value (AOV) | Converts high-lift pairs into discounted bundle cards (The Classic Combo, Cheese and Chill) ready to push straight to the POS terminal[cite: 1, 2] |

## 🧠 How the Data Mining Logic Works

| Metric | Example Rule | Value | What It Means |
| :--- | :--- | :--- | :--- |
| 🎯 Confidence | Burger to Fries | 78% | Measures the likelihood that a customer buys Fries given they have already added a Burger to their tray |
| 🚀 Lift | Burger to Fries | 2.14 | Measures how much more frequently two items are bought together compared to random chance (any score above 1.0 signals a strong pairing for bundles)[cite: 1, 2] |

## 🛠️ Architecture and Tech Stack

| Layer | Technology | Role in Project |
| :--- | :--- | :--- |
| 🏗️ Structure | Semantic HTML5 | Modular card-based dashboard layout |
| 🎨 Styling | Modern CSS3 | 12-column CSS Grid, Flexbox, custom gradient accents, and Inter typography |
| 📉 Data Visualization | Custom SVG | Hand-crafted scalable vector graphics with linear gradient fills and interactive hover nodes |
| ⚡ Interactivity | Vanilla JavaScript | Handles timeframe toggles, restock workflows, POS sync actions, and toast notifications[cite: 2] |

## 🚀 Quick Start

| Step | Action | Command |
| :--- | :--- | :--- |
| 1️⃣ Clone | Download the repository locally | `git clone https://github.com/your-username/qsr-data-mining-dashboard.git` |
| 2️⃣ Navigate | Move into the project directory | `cd qsr-data-mining-dashboard` |
| 3️⃣ Launch | Open directly in any web browser | `open data_mining_insights_dashboard.html` |

## 📁 Repository Layout

| File | Description |
| :--- | :--- |
| 📄 `data_mining_insights_dashboard.html` | Complete UI, styles, SVG charts, and JS logic[cite: 2] |
| 📝 `README.md` | Project documentation |

## 🗺️ Roadmap

| Status | Planned Feature | Description |
| :--- | :--- | :--- |
| 🐍 Planned | Python Backend Integration | Connect a FastAPI or Flask service using mlxtend (apriori and association_rules) to dynamically compute rules from uploaded CSV transaction logs |
| 🔄 Planned | Dynamic Timeframe Filtering | Update SVG data points and KPI cards dynamically when switching between Last 30 Days, Last Quarter, and Year to Date |
| 🎛️ Planned | Custom Combo Builder | Allow managers to set custom discount percentages and auto-calculate projected margin impact before pushing to POS |

## 👨‍💻 Author

Rajvardhan Yadav
