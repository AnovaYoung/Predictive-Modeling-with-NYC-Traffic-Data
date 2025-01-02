# NYC Traffic Data Analysis and Predictive Modeling

This project leverages NYC traffic data to perform comprehensive statistical analysis and predictive modeling. The goal is to identify patterns, assess contributing factors to traffic injuries and fatalities, and provide actionable recommendations for reducing auto-related incidents in New York City.

---

## **Table of Contents**
1. [Introduction](#introduction)
2. [Data Source](#data-source)
3. [Methodology](#methodology)
4. [Key Findings](#key-findings)
5. [Recommendations](#recommendations)
6. [How to Run](#how-to-run)
7. [Technologies Used](#technologies-used)

---

## **Introduction**

New York City, known for its dense population and bustling streets, faces significant challenges in traffic management and safety. Despite efforts like TrafficStat and Vision Zero, the rate of traffic injuries and fatalities remains concerning. This project analyzes data from 2018 to 2023 to uncover trends, model predictive factors, and recommend evidence-based solutions to improve traffic safety.

---

## **Data Source**

The data is sourced from the NYC Motor Vehicle Collision dataset available via NYC Open Data and Kaggle. It includes over 2 million entries spanning January 2014 to July 2023, with details on:
- Location
- Timing
- Types and numbers of vehicles involved
- Injuries and fatalities
- Contributing factors

For this analysis, data from 2018 to 2023 was used.

---

## **Methodology**

1. **Data Preparation**:
   - Cleaning missing and irrelevant values.
   - Aggregating contributing factors and vehicle types into categories.
   - Creating new variables for detailed injury and fatality analysis.

2. **Exploratory Data Analysis (EDA)**:
   - Examining trends by borough, time of day, seasonality, and vehicle types.
   - Identifying high-risk factors and behaviors.

3. **Modeling**:
   - Logistic Regression for predicting likelihood of injury or fatality.
   - Decision Trees for classification of high-risk scenarios.
   - Statistical tests to validate findings.

---

## **Key Findings**

1. **Injury and Fatality Trends**:
   - While collisions have decreased since 2019, injuries and fatalities have risen.
   - Pedestrians and motorcyclists remain the most vulnerable groups.

2. **High-Risk Factors**:
   - Leading causes include driver distraction, unsafe speed, and failure to yield.
   - Specific times (e.g., nighttime) and locations (e.g., Brooklyn) show higher incident rates.

3. **Vehicle Analysis**:
   - Sedans are most frequently involved, but motorcycles have the highest fatality rate per incident.

4. **Predictive Modeling**:
   - Logistic regression achieved an AUC of ~0.75 for injury prediction and ~0.72 for fatalities.

---

## **Recommendations**

1. **Policy Actions**:
   - Strengthen enforcement of traffic rules, especially regarding speed and yielding.
   - Increase penalties for distracted driving and aggressive behaviors.

2. **Infrastructure Enhancements**:
   - Expand pedestrian safety measures like crosswalk redesigns.
   - Implement dedicated motorcycle lanes.

3. **Public Awareness**:
   - Conduct targeted campaigns on defensive driving and pedestrian safety.

4. **Technology**:
   - Deploy adaptive traffic management systems and more speed cameras.

---

## **How to Run**

1. Clone this repository:
   ```bash
   git clone https://github.com/your-repo/nyc-traffic-analysis.git
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook for analysis:
   ```bash
   jupyter notebook Predictive_Modeling_with_NYC_Traffic_Data.ipynb
   ```

---

## **Technologies Used**

- **Python**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Statsmodels
- **Data**: NYC Open Data (TrafficStat)
- **Frameworks**: Jupyter Notebook, Logistic Regression, Decision Trees
- **Visualization**: Matplotlib, Seaborn

