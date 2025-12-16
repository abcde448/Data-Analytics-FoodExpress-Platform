#  Data Analytics : FoodExpress Platform

##  Project Overview
This project presents a comprehensive statistical and exploratory data analysis of **FoodExpress**, a food delivery platform.  
The objective is to extract actionable business insights using **Python, statistical hypothesis testing, and data visualization**, focusing on customer behavior, delivery performance, revenue impact, and operational efficiency.

The project follows an **industry-level analytical workflow**, combining data cleaning, feature engineering, visualization, and advanced statistical tests.

---

##  Business Objectives
- Understand customer ordering behavior and preferences
- Analyze delivery performance across cities and time periods
- Evaluate revenue drivers and discount impacts
- Test business assumptions using statistical hypothesis testing
- Provide data-driven recommendations for operations and marketing teams

---

##  Dataset Description
The dataset contains **1000 food delivery orders** with the following key attributes:
- Order details (date, time, value, cuisine)
- Customer segmentation (New, Regular, VIP)
- Delivery metrics (time, distance, city)
- Payment methods
- Ratings and discounts

---

##  Data Cleaning & Feature Engineering
- Handled missing values using median imputation
- Removed extreme outliers (e.g., invalid delivery times)
- Converted data types for accurate analysis
- Reshaped payment data using `melt()`
- Created new features:
  - `NetRevenue`
  - `DiscountPercent`
  - `DayType (Weekday / Weekend)`
  - Customer history proxy features

---

##  Exploratory Data Analysis & Visualization
- Cuisine-wise order distribution
- Delivery time distribution (Histogram with mean & median)
- Customer segment proportion (Pie chart)
- Order value vs delivery time relationship (Scatterplot)
- City-wise delivery consistency (Boxplot)
- Daily order trends by cuisine (Multi-line chart)

All plots were created using **Matplotlib + Seaborn** and saved in high resolution for reporting and presentation.

---

##  Statistical Hypothesis Testing
The project applies real-world business hypothesis testing, including:

###  T-Tests
- Independent T-Test: VIP vs Regular customer ratings
- One-Sample T-Test: Delivery time target evaluation
- Paired T-Test: Weekday vs Weekend delivery performance

###  Chi-Square Tests
- Independence test: Payment method vs customer segment
- Goodness of fit: Cuisine distribution expectation

###  ANOVA
- One-way ANOVA: Delivery time differences across cities

###  Correlation Analysis
- Order value vs delivery time
- Delivery time vs customer rating
- Restaurant rating predictors

---

##  Key Insights
- Delivery performance is largely independent of order value
- VIP customers show higher average ratings but not statistically significant
- Certain cities show higher delivery time variability
- Discount-heavy regions tend to generate negative net revenue
- Promotional campaign evaluation was limited due to lack of paired data

---

##  Methodological Limitations
- Some paired statistical tests were not feasible due to lack of repeated entities
- Dataset size limits generalization
- Certain assumptions required proxy features

These limitations are **explicitly documented**, reflecting real-world data constraints.

---

##  Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- SciPy, Statsmodels
- Google Colab

---

##  Final Outcome
This project demonstrates a **full end-to-end data analysis pipeline**, emphasizing:
- Statistical thinking
- Business interpretation
- Clear communication of insights
- Professional reporting standards

---

##  Author
📬 Md. Rabbi Hasan | Data Scientist 📧arafatrabbi668@gmail.com | LinkedIn https://www.linkedin.com/in/md-rabbi-hasan-3249652b1 Passionate about turning raw data into real-world insights through clear, compelling storytelling.
