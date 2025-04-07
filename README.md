# Olist E-commerce, Logistics & Customer Experience Case Study

Welcome to the Olist Case Study repository. This project explores customer behavior, logistics performance, and regional opportunities using the Olist dataset. Olist, Brazil’s largest online department store across marketplaces, simplifies sales for merchants by offering one centralized platform and logistics network.

Through an in-depth data analysis, we aim to uncover insights that inform regional strategies, delivery optimization, and customer satisfaction enhancement. This report is structured around three key business questions.

---

## 🛍️ Project Overview

The dataset integrates order, customer, review, seller, and logistics information, along with geolocation data. This multi-dimensional view allows us to assess customer satisfaction, sales performance, freight efficiency, and market penetration across Brazil.

---

## 📌 Business Question 1:  
**How do customer density and revenue distribution across states correlate with average customer review scores, and what strategies can Olist implement to enhance performance in key regions?**

**Visualization:**  
[Customer Density vs. Review Scores – Tableau Sheet](https://public.tableau.com/views/Week10_Olistcase/Sheet62)

### 🗺️ Key Insights:
- **High Revenue States:** São Paulo (SP - 41.9%), Rio de Janeiro (RJ - 12.9%), and Minas Gerais (MG - 11.7%) are top contributors.
- **Review Scores:** Not always aligned with revenue. E.g., RJ has low average review scores (~3.8), highlighting potential service issues.
- **Low Revenue, High Review States:** Amapá (AP), Rondônia (RO) offer opportunities for expansion due to positive customer sentiment.
- **Problem Areas:** Roraima (RR), Alagoas (AL) show both low revenue and satisfaction, likely due to logistical or product limitations.

### 📈 Implications:
- **Optimize High-Revenue States:** Enhance delivery reliability, improve product quality, and offer loyalty programs in states like RJ.
- **Leverage High-Satisfaction States:** Use positive reviews in states like AP and RO to scale marketing and seller engagement.
- **Address Low-Performance Regions:** Collaborate with local logistics and expand seller base in underperforming areas like RR and AL.

---

## 🚚 Business Question 2:  
**What are the top 5 states reporting late deliveries and how do they correlate with average item prices?**

### 🔍 Key Insights:
- **Longest Delays:** Amazonas (AM), Acre (AC) face significant logistical challenges due to geography.
- **Shortest Delays:** Bahia (BA), Alagoas (AL) show efficient delivery performance.
- **Highest Item Prices:** Found in AL and AC — high price sensitivity can be tapped for premium offerings.
- **Correlation:** Areas with high prices and low delays (like AL) are ideal for marketing reliability and value. BA offers mid-range affordability and fast delivery.

### 📈 Implications:
- **Enhance Logistics in Remote Areas:** Invest in delivery partnerships or micro-warehouses in AM and AC.
- **Tailored Product Strategy:** Sell mid-range products in low-price regions, and promote premium goods in high-price, low-delay areas.
- **Dynamic Messaging:** For high-delay regions, focus on trust and reliability; for low-delay regions, highlight premium and speed.

---

## 📦 Business Question 3:  
**How can Olist optimize delivery logistics by analyzing delivery times and freight costs across different regions in Brazil?**

### 🚚 Key Insights:
- **Efficient Regions:** SP and RJ average 8.3-day delivery times and low freight costs (~R$18.45).
- **Inefficient Regions:** AM faces 26-day delivery times with high costs (~R$27.27).
- **Weak Correlation (0.21):** Freight costs aren't only driven by delivery times — other factors like distance and infrastructure matter more.
- **Order Volume Disparity:** SP and RJ handle 62% of orders; Northern states only 15%, yet face the highest logistical barriers.

### 📈 Implementation Strategy:
- **Regional Warehousing:** Build distribution centers in remote areas like AM to cut delivery times by up to 30% and reduce costs.
- **Smart Routing:** Use AI/ML routing tools to optimize paths and reduce delays by 10–15%.
- **Dynamic Pricing:** Align freight pricing with local delivery challenges while maintaining competitive margins.
- **Clear Customer Communication:** Set realistic delivery expectations and offer loyalty points for delays to build trust.

---

## ✅ Conclusions

Olist’s logistics and customer experience vary significantly across Brazil. While states like São Paulo and Rio de Janeiro dominate in volume and efficiency, they also show room for improvement in customer satisfaction. Remote regions such as Amazonas and Acre face high logistical barriers but offer untapped potential.

### 🧭 Strategic Recommendations:
- **Invest in Infrastructure:** Target warehousing and last-mile delivery systems in remote regions.
- **Optimize Delivery Paths:** Implement routing algorithms and predictive logistics tools.
- **Segment Marketing:** Develop distinct messaging for high-delay vs. low-delay regions.
- **Build Loyalty:** Use customer incentives and review transparency to build trust across markets.

Every package tells a story — and Olist’s logistics journey is one of both challenges and opportunities. With strategic investment and data-driven decisions, Olist can deliver not only goods, but exceptional value to every corner of Brazil.

---

## 📁 Repository Structure

```bash
├── README.md                      # Project overview
├── data/                          # Raw and processed datasets
├── dashboards/                    # Tableau links, screenshots, or exports
├── notebooks/                     # Data cleaning and analysis scripts
├── reports/                       # Presentation materials or slide decks
