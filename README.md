# 📊 Sales & Customer Analytics Dashboard

<div align="center">

![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white)
![Status](https://img.shields.io/badge/Status-Complete-success?style=for-the-badge)
![Data](https://img.shields.io/badge/Data-Superstore-blue?style=for-the-badge)

**Transforming Sales Data into Actionable Insights**

[View Dashboard](#-dashboard-preview) • [Features](#-key-features) • [Installation](#-getting-started) • [Documentation](#-documentation)

---

### 🎯 Quick Stats from 2023

| Metric | Value | Growth |
|--------|-------|--------|
| 💰 Total Sales | $733K | ↑ 20.4% |
| 📈 Total Profit | $93K | ↑ 12.5% |
| 👥 Customers | 693 | ↑ 8.6% |
| 📦 Orders | 1,687 | ↑ 28.3% |

</div>

---

## 📖 Table of Contents

- [Overview](#-overview)
- [Key Features](#-key-features)
- [Requirements](#-requirements)
- [Getting Started](#-getting-started)
- [Dashboard Guide](#-dashboard-guide)
- [Use Cases](#-use-cases)
- [Contributing](#-contributing)
- [License](#-license)

---

## 🌟 Overview

This project delivers **two comprehensive Tableau dashboards** designed to empower stakeholders with deep insights into sales performance and customer behavior. Built with a focus on storytelling and interactivity, these dashboards transform raw data into strategic intelligence.

### 🎯 Project Objectives

- **Analyze** year-over-year sales performance with precision
- **Understand** customer behavior patterns and loyalty metrics
- **Identify** trends, opportunities, and areas requiring attention
- **Enable** data-driven decision making across the organization

### 👥 Target Audience

- 🏢 **Sales Managers** - Track team performance and product trends
- 👔 **Executives** - Monitor high-level KPIs and strategic metrics
- 📢 **Marketing Teams** - Understand customer segments and behaviors
- 📊 **Business Analysts** - Deep-dive into granular data patterns

---

## 🖼️ Dashboard Preview

### Sales Dashboard | 2023
![Sales Dashboard](https://github.com/shahilsh/Data-Analyst-Task2/blob/main/images/Sales%20Dashboard.png)

*Track sales, profit, and quantity metrics with comprehensive trend analysis and subcategory insights*

### Customer Dashboard | 2023
![Customer Dashboard](https://github.com/shahilsh/Data-Analyst-Task2/blob/main/images/Customer%20Dashboard.png)

*Analyze customer distribution, top performers, and behavioral patterns*

---

## ✨ Key Features

### 🎛️ Sales Dashboard

#### 📊 KPI Overview
- **Total Sales, Profit & Quantity** with year-over-year comparison
- **Sparkline visualizations** showing monthly trends
- **Performance indicators** highlighting growth/decline percentages
- **Peak/Low markers** (🔵 highest, 🟠 lowest months)

#### 📈 Sales Trends Analysis
- Monthly comparison between current and previous year
- Visual identification of seasonal patterns
- Growth trajectory visualization

#### 🛍️ Product Subcategory Comparison
- Side-by-side sales performance across all subcategories
- Profit vs. loss indicators for strategic decision-making
- Year-over-year comparison bars

#### 📅 Weekly Trends
- **Dual-axis chart** for sales and profit correlation
- **Average benchmark lines** for performance context
- **Color-coded indicators** (above/below average)
- Identifies high-performing and underperforming weeks

---

### 👥 Customer Dashboard

#### 📊 KPI Overview
- **Total Customers** with growth metrics
- **Sales Per Customer** indicating customer value
- **Total Orders** showing engagement levels
- Monthly sparklines for trend visualization

#### 👤 Customer Distribution
- Visual breakdown by number of orders placed
- Identifies customer loyalty segments
- Reveals acquisition vs. retention patterns

#### 🏆 Top 10 Customers
Comprehensive table featuring:
- 🥇 Customer ranking by profitability
- 💰 2023 profit and sales figures
- 📦 Order count
- 📅 Last order date
- Strategic account identification

---

## 🎨 Design & Interactivity

### 🔄 Dynamic Features

| Feature | Description |
|---------|-------------|
| **Year Selector** | Navigate through historical data seamlessly |
| **Cross-Dashboard Navigation** | Switch between Sales and Customer views instantly |
| **Interactive Charts** | Click on any chart element to filter all visualizations |
| **Responsive Filtering** | Real-time updates across all dashboard components |

### 🎯 Data Filters

```
📍 PRODUCT FILTERS
├── Category (Multiple Selection)
└── Sub-Category (All/Specific)

🗺️ LOCATION FILTERS
├── Region (Multiple Selection)
├── State (All/Specific)
└── City (All/Specific)

📅 TEMPORAL FILTERS
└── Year Selection (2022, 2023, ...)
```

---

## 📋 Requirements

### Sales Dashboard Requirements

<details>
<summary><b>Click to expand detailed requirements</b></summary>

#### Dashboard Purpose
Present an overview of sales metrics and trends to analyze year-over-year performance and understand sales patterns.

#### Key Requirements

**1. KPI Overview**
- Display total sales, profits, and quantity
- Compare current year vs. previous year
- Show percentage change indicators

**2. Sales Trends**
- Present monthly data for both years
- Identify and highlight highest/lowest months
- Enable easy pattern recognition

**3. Product Subcategory Comparison**
- Compare all subcategories (current vs. previous year)
- Include sales and profit metrics
- Visual profit/loss indicators

**4. Weekly Trends**
- Weekly sales and profit data for current year
- Display average weekly values
- Highlight above/below average performance

</details>

### Customer Dashboard Requirements

<details>
<summary><b>Click to expand detailed requirements</b></summary>

#### Dashboard Purpose
Provide comprehensive overview of customer data, trends, and behaviors to improve customer satisfaction and marketing effectiveness.

#### Key Requirements

**1. KPI Overview**
- Total number of customers
- Total sales per customer
- Total number of orders
- Year-over-year comparison for all metrics

**2. Customer Trends**
- Monthly data for current and previous year
- Identify peak and low months
- Visual trend indicators

**3. Customer Distribution**
- Distribution based on number of orders
- Insights into customer loyalty
- Engagement pattern analysis

**4. Top 10 Customers**
- Ranked by profit generation
- Include: rank, orders, sales, profit, last order date
- Enable strategic account management

</details>

---

## 🚀 Getting Started

### Prerequisites

```bash
✅ Tableau Desktop Public Edition (Free)
✅ Dataset 
✅ Basic understanding of Tableau interface
```

### Installation Steps

1. **Download Tableau**
   ```
   Visit: https://www.tableau.com/products/public/download
   Install Tableau Desktop Public Edition
   ```

2. **Clone or Download Project**
   ```bash
   git clone https://github.com/shahilsh/Data-Analyst-Task2.git
   cd Data-Analyst-Task2
   ```

3. **Load Data Source**
   - Open Tableau Desktop
   - Connect to Data → Text file
   - Select `Datasets`

4. **Open Dashboard**
   - File → Open
   - Navigate to project folder
   - Open `Sales_&_Customer_Dashboards.twbx`

5. **Explore & Customize**
   - Use filters to explore different data segments
   - Switch between dashboards using navigation tabs
   - Interact with charts for dynamic filtering

---

## 📘 Dashboard Guide

### 🎯 Sales Dashboard - How to Use

#### Starting Your Analysis

1. **Select Time Period**
   - Use the year selector to choose your analysis period
   - Compare against the previous year automatically

2. **Review KPIs**
   - Check the three main KPI cards at the top
   - Green ▲ indicates positive growth
   - Note the sparklines showing monthly patterns

3. **Analyze Product Performance**
   - Review the subcategory comparison chart
   - 🔵 Blue bars = 2023 sales
   - ⚪ Gray bars = 2022 sales
   - 🟠 Orange/Red dots = Profit/Loss indicators

4. **Examine Weekly Patterns**
   - Top line = Sales trend
   - Bottom line = Profit trend
   - Dashed lines = Average benchmarks
   - Darker colors = Above average performance

#### 💡 Pro Tips

> **Tip 1**: Click on any subcategory bar to filter the entire dashboard to that product category
> 
> **Tip 2**: Hover over sparklines to see exact monthly values
> 
> **Tip 3**: Use the filter panel to focus on specific regions or states

---

### 👥 Customer Dashboard - How to Use

#### Starting Your Analysis

1. **Review Customer KPIs**
   - Total Customers: Growth in customer base
   - Sales Per Customer: Average customer value
   - Total Orders: Engagement frequency

2. **Understand Customer Segments**
   - Check the distribution chart
   - Identify loyalty levels (1 order vs. multiple orders)
   - Spot opportunities for customer development

3. **Focus on VIP Customers**
   - Review Top 10 customers table
   - Note last order dates for retention risk
   - Compare profit margins across top accounts

#### 💡 Pro Tips

> **Tip 1**: Sort the Top 10 table by clicking column headers
> 
> **Tip 2**: Use filters to analyze customer behavior by region
> 
> **Tip 3**: Compare customer trends month-over-month to identify seasonality

---

## 💼 Use Cases

### For Sales Managers

```
📊 Weekly Team Review
├── Monitor weekly sales vs. targets
├── Identify underperforming product lines
├── Adjust inventory based on trends
└── Celebrate wins (peak weeks/months)
```

### For Executives

```
📈 Monthly Board Meetings
├── Present YoY growth metrics
├── Highlight strategic opportunities
├── Address profit margin concerns
└── Report on customer acquisition
```

### For Marketing Teams

```
🎯 Campaign Planning
├── Identify high-value customer segments
├── Target customers with 1 order (acquisition)
├── Create VIP programs for top 10
└── Analyze geographic opportunities
```

### For Business Analysts

```
🔍 Deep-Dive Analysis
├── Filter by specific regions/products
├── Identify correlation patterns
├── Forecast future performance
└── Build predictive models
```

---

## 📊 Key Insights & Findings

### 🎯 Performance Highlights

- **20.4% Sales Growth**: Strong year-over-year revenue increase
- **28.3% Order Growth**: Highest growth rate indicates improved engagement
- **693 Active Customers**: 8.6% growth in customer base
- **$1,058 Average Customer Value**: 10.8% increase in spending per customer

### ⚠️ Areas of Concern

- **Profit Margin Pressure**: Profit growing slower than sales (12.5% vs 20.4%)
- **Product Mix Issues**: Tables subcategory showing losses
- **Weekly Volatility**: Inconsistent performance week-to-week
- **Customer Concentration**: Heavy reliance on top customers

### 💡 Strategic Recommendations

1. **Optimize Product Portfolio**: Reduce focus on loss-making subcategories
2. **Customer Development Program**: Move single-order customers to repeat status
3. **Operational Efficiency**: Investigate low-profit weeks for improvement
4. **VIP Retention Strategy**: Protect relationships with top 10 customers

---

## 🤝 Contributing

We welcome contributions to improve these dashboards!

### How to Contribute

1. **Fork the Repository**
   ```bash
   git clone https://github.com/shahilsh/Data-Analyst-Task2.git
   ```

2. **Create Feature Branch**
   ```bash
   git checkout -b feature/YourFeatureName
   ```

3. **Make Your Changes**
   - Improve calculations
   - Add new visualizations
   - Enhance documentation

4. **Submit Pull Request**
   - Describe your changes
   - Include screenshots if applicable
   - Reference any related issues

### Contribution Ideas

- 🎨 Alternative color schemes for accessibility
- 📱 Mobile-optimized dashboard versions
- 🌍 Multi-language support
- 🤖 Predictive analytics integration
- 📧 Email alert integration for KPI thresholds

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### MIT License Summary

```
✅ Commercial use
✅ Modification
✅ Distribution
✅ Private use

```

---

## 📞 Contact & Support

### Get Help

- 📧 **Email**: shahilshaw5953@gmail.com


### Resources

- [Tableau Public Gallery](https://public.tableau.com/app/discover)
- [Tableau Documentation](https://help.tableau.com/)
- [Community Forums](https://community.tableau.com/)
- [Training Videos](https://www.tableau.com/learn/training)

---

## 🙏 Acknowledgments

- **Data Source**: Superstore dataset (Tableau Sample Data)
- **Inspiration**: Tableau Dashboard Best Practices
- **Design Philosophy**: Edward Tufte's Data Visualization Principles
- **Community**: Tableau Public Community for feedback and inspiration

---

## 📈 Project Roadmap

### ✅ Phase 1: Core Dashboards (Complete)
- [x] Sales Dashboard with KPIs
- [x] Customer Dashboard with analytics
- [x] Interactive filtering system
- [x] Year-over-year comparisons

### 🚧 Phase 2: Enhanced Analytics (In Progress)
- [ ] Predictive sales forecasting
- [ ] Customer lifetime value calculations
- [ ] Cohort analysis
- [ ] Geographic heat maps

### 🔮 Phase 3: Advanced Features (Planned)
- [ ] Real-time data integration
- [ ] Automated email reports
- [ ] Mobile app version
- [ ] AI-powered insights

---

## ⭐ Star History

### 🎯 Ready to Transform Your Data?

**[Download Tableau](https://www.tableau.com/products/public/download)** • **[Clone Repository](https://github.com/shahilsh/Data-Analyst-Task2.git)**
---

Made with ❤️ and ☕ by [Shahil]

*Last Updated: November 2025*

</div>
