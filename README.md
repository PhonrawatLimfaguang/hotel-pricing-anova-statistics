# 🏨 Hotel Pricing Analysis (ANOVA & Chi-Square)
> **Statistical Analysis of Beach Pool Villa Prices across Agoda, Traveloka, and Trip.com**

This repository contains a statistical research project for the **DE282 Statistics for Data Engineering** course. The study focuses on analyzing price disparities of luxury villas in Thailand across three major Online Travel Agencies (OTAs).

<img width="745" height="120" alt="image" src="https://github.com/user-attachments/assets/a8e26873-856f-47a9-9a46-c7a19a9b0a4a" />
<img width="872" height="382" alt="image" src="https://github.com/user-attachments/assets/6f1a855f-cefd-4b3e-8c1c-08fea6205d38" />
<img width="827" height="584" alt="image" src="https://github.com/user-attachments/assets/72ec48cd-a8a2-4323-8f2b-09284b45b31d" />
<img width="629" height="338" alt="image" src="https://github.com/user-attachments/assets/c62644e1-0744-49e4-af34-fa543e84c936" />
<img width="848" height="625" alt="image" src="https://github.com/user-attachments/assets/9e3d275c-a35b-4916-886f-e7d2e349b644" />



---

## 📁 Project Structure
To maintain Data Engineering standards, the project is organized as follows:

* 📁 **data/**: Contains processed datasets (Excel/CSV).
* 📁 **notebooks/**: Jupyter Notebooks for data cleaning and statistical testing.
* 📁 **report/**: Comprehensive academic report in PDF format.

---

## 📊 Key Statistical Insights
We analyzed 42 luxury beach pool villas in Thailand to determine if the booking platform significantly affects the price.

### 1️⃣ Descriptive Statistics
| Platform | Count | Sum (THB) | Average Price (THB) | Variance |
| :--- | :---: | :---: | :---: | :---: |
| **Agoda** | 42 | 641,256 | ฿15,268.00 | 418,153,221.5 |
| **Traveloka** | 42 | 680,640 | ฿16,205.71 | 350,183,359.2 |
| **Trip.com** | 42 | 865,525 | **฿20,607.74** | **1,478,995,480.0** |

### 2️⃣ Hypothesis Testing (ANOVA)
* **Null Hypothesis ($H_0$):** There is no significant difference in average prices across the three platforms.
* **Alternative Hypothesis ($H_1$):** At least one platform has a significantly different average price.
* **Result:** The **p-value < 0.05**, therefore we **Reject $H_0$**. 

> **Conclusion:** The choice of platform has a statistically significant impact on the booking cost. Trip.com tends to have the highest variance and average price among the three.



---

## 🛠️ Tech Stack & Methodology
* **Language:** Python 3.x
* **Core Libraries:** `Pandas`, `NumPy`, `SciPy.stats`, `Matplotlib`, `Seaborn`
* **Statistical Methods:** * **One-way ANOVA:** To compare means across 3 groups.
    * **Chi-Square Test:** To analyze price distribution frequency.
    * **Normality Testing:** Using Q-Q Plots and Histograms to verify data distribution.

---

## 🚀 Installation & Usage
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/PhonrawatLimfaguang/hotel-pricing-anova-statistics.git](https://github.com/PhonrawatLimfaguang/hotel-pricing-anova-statistics.git)
    ```
2.  **Run Analysis:** Open the notebook in `notebooks/` using Google Colab or Jupyter to see the Python implementation.

---
* **Team Members:** Pannathorn S., Phonlawit W.

*Developed at Srinakharinwirot University (SWU) - Faculty of Engineering*
