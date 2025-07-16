# Uber-Trip-Analysis-Dashboard

### 🚖 **Uber Trip Analysis Dashboard**

---

#### **1. Project Title / Headline**

**Uber Trip Analysis: City-wise Trip Metrics & Booking Insights**

An interactive Power BI dashboard to analyze Uber trip data focusing on booking patterns, trip distance, payment types, vehicle usage, and city-level insights.

---

#### **2. Short Description / Purpose**

The Uber Trip Analysis Dashboard is a powerful analytical tool built in Power BI to visualize and compare trip data across various cities. It helps users identify booking trends, vehicle preferences, and time-based booking patterns to optimize operational strategies.

---

#### **3. Tech Stack**

The dashboard was built using the following tools and technologies:

* 🧩 **Power BI Desktop** – Main data visualization tool for dashboard development
* 🛠️ **Power Query** – For data transformation and cleaning (e.g., date formatting, data reshaping)
* 🧠 **DAX (Data Analysis Expressions)** – For dynamic measures such as total bookings, revenue, trip time, and distances
* 🔗 **Data Modeling** – Built relationships between trips, vehicles, payment methods, and timestamps for smooth filtering
* 💾 **File Format** – `.pbix` for development; exported to `.png` for sharing and documentation

---

#### **4. Data Source**

**Source:** Synthetic Uber trip data for June 2024 (sample dataset).

This dataset contains Uber trip details including:

* Pickup date and time
* Vehicle type
* Number of passengers
* Trip distance
* Booking value
* Payment type
* Pickup/drop-off locations
* Aggregated metrics like total bookings and average trip time/distance

---

#### **5. Features / Highlights**

**📌 Best structure to explain the dashboard:**

* **Business Problem:**
  Urban ride services generate massive data. However, insights around time-based demand, city zones, payment methods, and trip patterns remain underutilized by ride-share companies and city planners.

* **Goal of the Dashboard:**
  To uncover key trip insights that help in understanding peak hours, preferred vehicle types, payment preferences, and revenue contributors.

* **Walkthrough of Key Visuals:**

  * **Overview Analysis Page:** Shows summary KPIs like Total Bookings (103.7K), Total Revenue (\$1.6M), Avg Booking Value (\$15), Avg Distance (3 miles), and Avg Time (16 min). Includes breakdowns by payment types, trip times (day/night), and vehicle types.
  * **Time Analysis Page:** Displays total bookings by pickup time, day of the week, and hour-wise heatmaps. Shows when demand peaks during the day.
  * **Details Page:** Provides a tabular view of each trip with filters for city and date. Useful for detailed inspection and audits.

* **Business Impact & Insights:**

  * Identified **UberX** as the most used vehicle type (38K+ bookings).
  * **Uber Pay** is the dominant payment method (67%+ usage).
  * **Sunday** had the highest booking revenue (\~\$19.2K).
  * Most frequent pickup: **Penn Station/Madison Sq West**
    Most frequent drop-off: **Upper East Side North**
  * Longest trip covered: **144.1 miles** (Lower East Side → Crown Heights North)

---

Let me know if you'd like a downloadable PDF version of this write-up or if you want this formatted for LinkedIn, presentation, or a resume portfolio.
