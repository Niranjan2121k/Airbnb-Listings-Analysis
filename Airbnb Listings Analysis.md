# 🏡 Airbnb Listings Analysis

## 📘 Overview

This data analysis project explores the Airbnb listings landscape in **Paris, France**, using public data sourced from Inside Airbnb. The goal was to understand how prices vary across neighborhoods, how listing capacity affects pricing, and how the platform evolved over time — particularly around the COVID-19 pandemic.

---

## 🎯 Objectives

- Identify the most and least expensive neighborhoods in Paris for Airbnb listings.
- Explore the relationship between accommodation capacity and average price.
- Analyze how the number of new Airbnb hosts and average prices changed over time.
- Generate actionable insights for travelers, hosts, and city planners.

---

## 🧾 Dataset Description

- **Source**: Inside Airbnb – Paris Listings
- **Data Scope**: Listings available across various Parisian neighborhoods.
- **Key Variables**:
  - `host_since`: The year the host began on Airbnb.
  - `neighbourhood`: The district of the listing in Paris.
  - `price`: Price per night in Euros.
  - `accommodates`: Number of guests the listing can host.

---

## 📊 Visual Analysis & Insights

### 1. Average Listing Price by Neighborhood

**Visualization**: Horizontal bar chart comparing average nightly price by district.

**Key Insight**:
- Listings in **Elysee**, **Louvre**, and **Passy** command the highest prices, ranging from **€180 to €215** per night.
- In contrast, neighborhoods like **Menilmontant**, **Buttes-Chaumont**, and **Reuilly** have lower average prices around **€75–€100**.

![output_23_0](https://github.com/user-attachments/assets/f059b221-cde1-41cf-a622-ab03066257e7)

**Conclusion**:
- Central, prestigious districts close to tourist landmarks and shopping areas are priced significantly higher.
- Budget-conscious travelers may find better deals in the outer districts.
---

### 2. Average Price by Accommodation Size in Elysee

**Visualization**: Horizontal bar chart showing average price per accommodation capacity (1–14 guests).

**Key Insight**:
- Prices scale significantly with capacity.
- A 1-guest listing costs around **€130**, whereas a listing for 14 guests costs nearly **€950**.
- Listings for 5–8 guests show a price sweet spot in the **€300–€450** range.

![output_25_0](https://github.com/user-attachments/assets/d2075a88-c68b-41d6-bcfe-39e5d91113bf)

**Conclusion**:
- Larger accommodations are positioned as premium or luxury stays.
- This suggests strong demand from group travelers or families looking to stay in upscale districts like Elysee.

---

### 3. New Hosts and Price Trends Over Time

**Visualization**: Dual-axis line chart showing new hosts (blue) and average prices (red) from **2008 to 2021**.

**Key Insights**:
- **2009 to 2015**: Explosive growth in new hosts, reflecting Airbnb’s expansion and rising popularity.
- **2016–2019**: Growth plateaus, possibly due to market saturation or increased regulation.
- **2020–2021**: Dramatic drop in both new hosts and prices due to **COVID-19 travel restrictions**.

![output_26_0](https://github.com/user-attachments/assets/cd0e2079-a4ce-4bd3-a9b1-2a4ce0944b01)

**Conclusion**:
- Airbnb growth in Paris followed a startup-like boom curve, with external shocks like the pandemic causing clear disruptions.
- Despite lower host counts, prices remained relatively resilient post-2020, indicating steady demand recovery.

---

## 💡 Key Takeaways

- **Location Drives Price**: Central Paris districts like Elysee and Louvre are premium hotspots for short-term rentals.
- **Accommodation Size Influences Cost**: Prices increase with capacity, with group accommodations priced disproportionately higher.
- **Airbnb Grew Rapidly**: New host numbers surged post-2009, peaked around 2015, and declined significantly during the pandemic.
- **COVID-19 Impacted Supply**: Fewer new hosts joined post-2020, but pricing only dropped modestly, signaling Airbnb’s continued relevance.

---

## 🧰 Tools Used

- **Python** (Pandas, Seaborn, Matplotlib) – for data cleaning and visualization
- **Jupyter Notebook** – for exploratory analysis
- **GitHub** – for documentation and version control
- **Markdown** – for storytelling and reporting

---

## 🌍 Real-World Applications

- **For Travelers**: Identify budget-friendly neighborhoods or luxury areas based on group size and budget.
- **For Hosts**: Use pricing trends to competitively price listings by neighborhood and capacity.
- **For City Planners**: Understand the saturation and pricing impact of short-term rentals over time.

---

## 📌 Future Work

- Expand analysis to other European cities for comparison.
- Analyze guest reviews to uncover qualitative insights.
- Create an interactive dashboard with filters for price, location, and date range.
- Use time series forecasting to predict future prices or host counts.


Contains:
- Detailed visualizations
- Insight-driven Markdown reporting
- Cleaned dataset and original Jupyter Notebook

---

*If you'd like to reuse or adapt this analysis, feel free to fork the repository or connect with me for collaboration opportunities.*
