# 📊 UIDAI Data Hackathon 2026

## Analysis of Aadhaar Enrolment and Update Patterns in India

**Subtitle:**
Insights from Enrolment, Demographic Update and Biometric Update Data

**Prepared by:**
**Khan Ismat Nazneen Afroz**

**Event:** UIDAI Data Hackathon 2026

---

## 📌 Project Overview

The Aadhaar ecosystem forms the backbone of India’s digital identity infrastructure. While Aadhaar enrolment has largely reached saturation, **update patterns vary significantly across age groups, regions and time periods**.

This project performs a **comprehensive exploratory data analysis (EDA)** on Aadhaar enrolment, demographic updates and biometric updates to uncover:

* Age-wise enrolment behavior
* Regional disparities in update activity
* Temporal trends and lifecycle patterns
* Policy-relevant and administrative insights

The analysis is fully **data-driven, reproducible, and visualization-centric**, making it suitable for governance, policy planning and operational decision-making.

---

## 🎯 Objectives

* Analyze Aadhaar enrolment distribution across age groups and states
* Examine demographic and biometric update behavior
* Identify high-update regions and age transition patterns
* Study time-based trends in enrolment and updates
* Generate actionable insights for UIDAI and policymakers

---

## 🧠 Analytical Approach

The project follows a structured exploratory workflow:

* Univariate analysis (distribution & trends)
* Bivariate analysis (relationships between variables)
* Multivariate analysis (age × state × time patterns)
* Feature engineering for lifecycle insights
* Visual analytics for clear communication

---

## 🗂️ Datasets Used

### 1️⃣ Aadhaar Enrolment Dataset

**Description:** Aggregated enrolment data across India
**Key Columns:**

* `date`
* `state`, `district`, `pincode`
* `age_0_5`, `age_5_17`, `age_18_greater`

**Purpose:**

* Study age-wise enrolment distribution
* Analyze geographic and temporal enrolment patterns

---

### 2️⃣ Aadhaar Demographic Update Dataset

**Description:** Aggregated demographic update data
**Key Columns:**

* `date`
* `state`, `district`, `pincode`
* `demo_age_5_17`, `demo_age_17_plus`

**Purpose:**

* Understand frequency of demographic changes
* Identify high-update regions

---

### 3️⃣ Aadhaar Biometric Update Dataset

**Description:** Aggregated biometric update data
**Key Columns:**

* `date`
* `state`, `district`, `pincode`
* `bio_age_5_17`, `bio_age_17_plus`

**Purpose:**

* Analyze biometric revalidation patterns
* Study updates during age transitions

---

## 🛠️ Tools & Technologies

* **Python**
* **Pandas & NumPy**
* **Matplotlib & Seaborn**
* **Jupyter Notebook**

---

## 🧹 Data Pre-processing & Cleaning

Extensive data cleaning was performed to ensure analytical accuracy:

* Standardization of state names (case, spelling, symbols)
* Removal of invalid and numeric noise entries
* Resolution of duplicate and inconsistent state labels
* Filtering out cities/localities mistakenly recorded as states
* Conversion of date fields into proper datetime format

Final datasets contain **36 valid states and union territories** with **zero missing values**.

---

## 🧪 Feature Engineering

Key derived metrics include:

* **Total Enrolments / Updates**
* **Child Dependency Ratios** (child vs adult activity)
* **Enrollment Composition Ratios**
* **Lifecycle Activity Indicators**

These features enable deeper lifecycle and policy-level insights.

---

## 📈 Exploratory Data Analysis

### 🔹 Univariate Analysis

* Age-wise Aadhaar enrolment distribution
* Time trends for enrolment, demographic updates, and biometric updates

**Key Insight:**

* Aadhaar enrolment is dominated by the **0–5 age group**
* Demographic updates are highest in the **17+ age group**
* Biometric updates spike significantly after age transitions

---

### 🔹 Bivariate Analysis

* Age group vs enrolment volume
* State-wise enrolment vs demographic updates
* Time vs update frequency

**Key Insight:**

* States with high enrolment also show high update activity
* Update frequency shows periodic spikes linked to policy drives and migration

---

### 🔹 Multivariate Analysis

* Age × State × Time heatmaps
* Enrolment vs demographic vs biometric update composition
* Regional update intensity comparisons

**Key Insight:**

* Biometric updates form the **largest share of Aadhaar lifecycle activity**
* Aadhaar has largely reached enrolment saturation nationwide

---

## 🌍 Impact of the Analysis

### 🏛️ Administrative & Governance Impact

* Identifies high-demand states (e.g., Bihar, Andhra Pradesh, Chhattisgarh)
* Supports targeted resource allocation and staffing
* Enables workload forecasting for Aadhaar centers

### 📜 Policy & Strategic Impact

* Validates biometric revalidation policies for age transitions
* Highlights inclusion gaps in child enrolment
* Shifts focus from enrolment drives to lifecycle management

### 👥 Social Impact

* Improves citizen access to welfare and digital services
* Supports migrant populations with accurate identity updates
* Strengthens trust in India’s digital identity ecosystem

### ⚙️ Operational Impact

* Enables predictive infrastructure planning
* Supports state-specific operational models
* Reduces congestion and service downtime

---

## 📌 Key Takeaways

* Aadhaar is now a **maintenance-intensive system**, not an enrolment-centric one
* Biometric updates dominate lifecycle activity
* Population-dense states require continuous infrastructure investment
* Data-driven insights can significantly improve governance efficiency

---

## 📎 Repository Structure (Suggested)

```
📦 uidai-data-hackathon-2026
 ┣ 📂 data
 ┣ 📂 notebooks
 ┣ 📂 visuals
 ┣ 📜 README.md
 ┗ 📜 requirements.txt
```

---

## 🙌 Acknowledgements

* **UIDAI** for providing the dataset
* **UIDAI Data Hackathon 2026** for the opportunity

---
