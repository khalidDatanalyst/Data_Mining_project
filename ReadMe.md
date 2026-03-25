---

# **Investigating the Nexus: CO2 Emissions, Climate Change, and Global Life Expectancy**

## ** Project Overview**
As the global climate crisis intensifies, understanding the relationship between industrial output and human longevity is critical. This project explores the multi-dimensional impact of **CO2 emissions** on **Life Expectancy** across various global economies. By leveraging data mining and statistical analysis techniques, I aimed to determine whether high carbon footprints—often a byproduct of industrial development—correlate with improved healthcare outcomes or if environmental degradation poses a net threat to human life.

## **📊 Dataset & Data Wrangling**
The analysis utilizes longitudinal data sourced from **World Bank** and **Gapminder** covering the period from **1990 to 2023**.
* **Data Cleaning:** Handled missing values through mean imputation, standardized units, and merged multiple indicators into a unified dataframe.
* **Key Features:**
    * `CO2_Emissions`: Metric tons per capita.
    * `Life_Expectancy`: Average years of life at birth.
    * `Region/Continent`: For categorical comparative analysis.

## ** Research Methodology**
I approached this project using a structured Data Science workflow:
1.  **Exploratory Data Analysis EDA:** Identified global distribution patterns and outliers in emission levels.
2.  **Trend Analysis:** Visualized the trajectory of carbon output versus health improvements over the last two decades.
3.  **Correlation Analysis:** Applied **Pearson Correlation** to quantify the strength of the relationship between emissions and longevity.
4.  **Comparative Study:** Segmented analysis between "High-Income Industrialized Nations" and "Low-Income Developing Nations" to observe the "Environmental Kuznets Curve" phenomenon.

## **🛠️ Tech Stack**
* **Language:** Python 3.13
* **Environment:** Jupyter Notebook
* **Primary Libraries:** * `Pandas` & `NumPy` (Data Manipulation)
    * `Matplotlib` & `Seaborn` & plotly (Statistical Visualization)
    * `Scipy.stats` (Statistical Testing)

## **📈 Key Insights & Visualizations**

### **1. The Global co2 Emission per capita**
> *!co2 emission per capita plot(reports/newplot2.png)*
> **Observation:** Global CO2 emissions show a steady increase, with significant variance between the Global North and Global South.

### **2. Correlation Analysis: Air polution with time**
> *reports/newplot5.png*
> **Insight:** There is a Positive correlation. This suggests that while industrialization historically drives life expectancy up through wealth, the rate of improvement slows down as emissions reach critical levels.

### **3. Regional Health-Environment vs Green House Gasess**
> *reports/newplot3.png*
> **Insight:** Countries with the highest Green House Gasess do not necessarily exhibit the highest life expectancy, indicating a "point of diminishing returns" for environmental costs.

## ** Conclusion**
The study concludes that while CO2 emissions are a proxy for the industrial activity that funds healthcare, the environmental externalities of climate change present a long-term risk to global health stability. Achieving "Green Growth"—increasing life expectancy while decoupling it from carbon emissions—is the primary challenge for the coming decade.

## ** How to Use This Repository**
1. **Clone:** `git clone https://github.com/https://https://github.com/khalidDatanalyst/khalidDatanalyst//Data_Mining_Project.git`
2. **Setup:** Install dependencies via `pip install -r requirements.txt`.
3. **Execute:** Run the `analysis_notebook.ipynb` to reproduce the findings and visualizations.

## **🤝 Connect with Me**
* **LinkedIn:** https://www.linkedin.com/in/analyst-khalid-89456a3a9/
* **Github.com:** https://github.com/khalidDatanalyst/khalidDatanalyst
* **Email:** khalid.123bessmn.go@gmail.com

---