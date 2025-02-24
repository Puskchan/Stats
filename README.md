# Statistical Examination of Airbnb Listings Data ✨📊🏡

## Abstract 🎯📈🔍
This repository presents an advanced statistical examination of Airbnb listings, employing rigorous **data preprocessing, exploratory data analysis (EDA), inferential statistical testing, and regression modeling** to discern patterns in pricing, availability, and host behaviors across different geographical regions.

---

## Dataset Composition 📂🗂️📊
### Airbnb Dataset Characteristics 🌍🏠📌
This dataset comprises a comprehensive set of variables, categorized as follows:
- **Listing Attributes:** `NAME`, `neighbourhood`, `lat`, `long`
- **Host Identification:** `host id`, `host name`, `host_identity_verified`
- **Financial Metrics:** `price`, `service fee`
- **Booking and Availability Data:** `minimum nights`, `number of reviews`, `availability 365`
- **Review Metrics:** `reviews per month`, `review rate number`
- **Ancillary Information:** `house_rules`, `license`

---

## Methodological Approach to Data Processing 🛠️📊🔬
- **Handling Missing Data:**
  - Categorical Variables: Imputed using mode substitution or logical placeholders.
  - Numerical Variables: Addressed via mean/median imputation or exclusion where appropriate.
- **Feature Engineering Strategies:**
  - Extracted host verification status as a predictor variable.
  - Transformed pricing and service fee features into numerical representations for analytical consistency.
- **Detection and Treatment of Outliers:**
  - Identified extreme price values using interquartile range and standard deviation thresholds.
  - Removed implausible values in `minimum nights` to maintain data integrity.

---

## Exploratory Data Analysis (EDA) 🔎📉📊
- **Univariate Distributions:**
  - Evaluated the probability distributions of price, service fees, and review counts.
  - Examined the frequency distribution of host verification status.
- **Bivariate Correlation Analysis:**
  - Investigated relationships between price, availability, and review frequency.
  - Assessed the effect of host verification status on pricing structure.
- **Spatial Analytics:**
  - Mapped geographic concentration of listings.
  - Identified price clustering within high-demand urban districts.

---

## Inferential Statistical Analysis 📈📊🔬
- **Descriptive Statistics:** Computed central tendency (mean, variance, standard deviation) for price and availability.
- **Correlation vs. Causation:**
  - Applied Pearson and Spearman correlation coefficients to evaluate inter-variable associations.
- **Regression Modeling:**
  - Constructed a **Simple Linear Regression** model to predict pricing trends.
  - Assessed model efficacy using R-Squared and F-statistic significance testing.
- **Hypothesis Testing Framework:**
  - Conducted **ANOVA** to determine pricing variability across different neighborhoods.
  - Implemented **t-tests** to compare listing prices between verified and unverified hosts.

---

## Principal Findings 🎯📊📌
- **Host Verification and Pricing:** Listings managed by verified hosts command a marginally higher average price.
- **Geographical Influence:** Significant regional price disparities exist, with premium neighborhoods exhibiting elevated pricing structures.
- **Price-Availability Dynamics:** Inverse correlation observed—high-priced listings tend to have lower annual availability.
- **Review Count vs. Price:** Higher review volume does not unequivocally correlate with lower pricing, indicating complex interplay among variables.

---

## Implications and Future Research Directions 🚀🔍📚
- **Strategic Implications:** The findings furnish actionable insights for hosts optimizing pricing strategies to enhance revenue.
- **Prospective Research:**
  - Employ advanced machine learning regression methodologies (Polynomial, Ridge, Lasso) for improved predictive performance.
  - Conduct sentiment analysis on customer reviews to extract latent indicators of guest satisfaction and its impact on pricing models.

---

## Reproducibility Instructions ⚙️💻📜
1. Clone the repository:
   ```bash
   git clone https://github.com/Puskchan/Stats.git
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Execute the Jupyter Notebook:
   ```bash
   jupyter notebook Stats_Analysis.ipynb
   ```

---

