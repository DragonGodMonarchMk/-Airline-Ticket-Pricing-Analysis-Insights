# -Airline-Ticket-Pricing-Analysis-Insights
This project delivers an in-depth analysis of domestic airline flight booking data in India, aiming to **uncover patterns, trends, and actionable insights** that can directly influence airline pricing strategies, route planning, and revenue optimization. 
Airline Ticket Pricing Analysis & Insights — A comprehensive data analysis project exploring domestic airline ticket pricing in India. Leveraging over 300k booking records, this project uncovers patterns in pricing based on airline, route, departure/arrival time, travel class, and booking window. Includes data preprocessing, visualization, and actionable business recommendations for pricing strategy optimization, demand forecasting, and revenue management.


# ✈ Airline Ticket Pricing Analysis & Insights

## 📌 Project Overview
This project delivers an in-depth analysis of domestic airline flight booking data in India, aiming to **uncover patterns, trends, and actionable insights** that can directly influence airline pricing strategies, route planning, and revenue optimization.

The analysis is designed for **business decision-making**, moving beyond simple data visualization to generate **strategic recommendations** for airline revenue managers and analysts.

---

## 📊 Dataset Overview
- **Records:** 300,153 flight bookings
- **Source:** Major Indian online travel portal
- **Key Features:**
  - `airline` – Airline operating the flight
  - `source_city`, `destination_city` – Route information
  - `departure_time`, `arrival_time` – Categorized time slots
  - `stops` – Number of stops
  - `class` – Economy / Business
  - `days_left` – Days between booking and departure
  - `price` – Ticket price (₹)

---

## 📈 Key Analysis Topics
1. **Airline-Wise Demand & Pricing**
   - Market share by flight count
   - Average ticket pricing by airline & class
   - Competitive positioning (budget vs premium)

2. **Time-Based Pricing Trends**
   - Impact of departure and arrival time slots
   - Peak vs off-peak pricing strategies

3. **Route & City Pair Analysis**
   - Price variations by source/destination city
   - Most expensive routes

4. **Class-Wise Fare Insights**
   - Price gaps between Economy and Business
   - Revenue opportunities from premium upgrades

5. **Booking Window Effects**
   - Last-minute vs advance purchase price differences
   - Dynamic pricing opportunities

---

## 🔍 Tools & Technologies
- **Language:** Python
- **Libraries:** pandas, numpy, matplotlib, seaborn
- **Notebook:** Jupyter Notebook
- **Visualization:** Matplotlib & Seaborn plots for trend analysis

---

## 📌 Key Findings
- **Premium carriers** (e.g., Vistara, Air India) command significantly higher fares, especially in Business class.
- **Last-minute bookings** (≤ 2 days) are up to **80% more expensive** than early bookings.
- **Time-of-day impact:** Morning and evening flights attract higher prices; early morning and afternoon flights are cheaper.
- **Route-based pricing:** Metro-to-metro routes sustain premium fares; tourist and seasonal destinations show strong seasonal peaks.

---

## 🚀 Strategic Recommendations
- Maintain **premium pricing** for high-demand routes and time slots.
- Offer **flash discounts** on low-demand flights close to departure.
- Use **AI-driven demand forecasting** to optimize prices dynamically.
- Create **targeted marketing** for business travelers vs leisure travelers.
- Expand frequency on **profitable short-haul, high-demand routes**.

---

## 📂 Repository Structure

📁 Airline-Ticket-Pricing-Analysis
│── 📄 airline-ticket-pricing-analysis.ipynb # Main analysis notebook
│── 📄 airlines_flights_data.csv # Dataset
│── 📄 Airline_Ticket_Pricing_Analysis_Report.pdf # Detailed analysis report
│── 📄 README.md # Project documentation

yaml
Copy
Edit

---

## 📜 License
This project is for educational and analytical purposes only. Dataset is proprietary to the source travel portal and used here for demonstration.

---

## ✍ Author
**Manish**  
GitHub: [DragonGodMonarchMk](https://github.com/DragonGodMonarchMk)

---
