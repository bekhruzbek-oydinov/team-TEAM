### Project Plan : AI Project 1

---

## 1. Course Name

**Course Name:** Artificial Intelligence (AI)

---

## 2. Team Information

**Team Name:** TEAM

**Team Members (Name / Student ID / Role):**

* **Leader:** Oydinov Bexruz | Student ID: 202390243 | Group: E40B | Role: Team Leader & Data Scientist | Phone: +998-94-794-01-94
* **Member 1 (Co-Leader):** Murtazoyev Xondamir | Student ID: 202390241 | Group: E40B | Role: Data Analyst (Cleaning & Visualizing Data)
* **Member 2:** Abdumurodov Mashrab | Student ID: 202390257 | Group: E40B | Role: AI Prompt Engineer (Documentation & Model Evaluation)
* **Member 3:** Sayfulloyev Muhammad | Student ID: 202390201 | Group: E40B | Role: Researcher (Finding Dataset For The Project)
---

## 3. Project Title

**Project Title:** Apartment Price Prediction and Market Analysis in Tashkent Using Multiple Linear Regression

---

## 4. Dataset Information

**Dataset Title:** Real Estate Prices in Tashkent, Uzbekistan

**Source Website:** Kaggle - Real Estate Prices in Tashkent (Scraped from Uybor.uz)

**Description of the Dataset:**

The dataset contains real estate listings in Tashkent, Uzbekistan scraped from the local property platform uybor.uz. It includes essential structural and geographic attributes of residential units, such as district location (`district`), approximate street address (`address`), total area in square meters (`size`), number of rooms (`rooms`), unit floor (`level`), total building floors (`max_levels`), and listing price in USD (`price`).

**Why this Dataset was Selected:**

* It satisfies the project requirement of being a web-sourced dataset specifically related to Uzbekistan.
* Real estate valuation provides an intuitive, high-impact domain where linear relationships between physical variables (e.g., size, room count) and market price can be cleanly modeled and interpreted.
* The mix of numerical metrics and categorical variables (districts) allows practical application of feature engineering and multiple linear regression.

**Size of Dataset:** 7,421 rows, 9 columns

---

## 5. Project Objectives

**Problem to Solve:**

Real estate pricing in Tashkent often experiences wide variance and subjective valuation. The goal of this project is to build an interpretable Multiple Linear Regression model capable of predicting property prices in Tashkent based on physical attributes and geographical district data, helping buyers and sellers estimate fair market values.

**Key Questions to Answer:**

* How significantly does living area ($m^2$) correlate with price across different Tashkent districts?
* Which districts command the highest premium per square meter (e.g., Mirzo Ulugbek, Yakkasaray vs. outlying districts)?
* How much explanatory power ($R^2$ score) can a linear combination of physical features and district indicators capture in the local housing market?
* Can the model reliably identify overvalued or undervalued listings based on residual errors?

**Expected Insights from the Dataset:**

* Identification of the primary price-driving factors in Tashkent apartments.
* Explicit coefficient weights demonstrating the exact dollar value added by an additional room or additional square meter.
* A comparative baseline for district premiums after controlling for apartment size and floor level.

---

## 6. Project Schedule & Milestones

| Milestone | Key Tasks & Deliverables | Target Date |
|---|---|---|
| **Milestone 1: Project Proposal** | Finalize topic selection, initialize GitHub repository, set up README proposal, submit repo link. | October 7, 2026 |
| **Milestone 2: Data Preprocessing & EDA** | Clean missing values, detect outliers, perform exploratory data analysis, generate correlation heatmaps. | October 10, 2026 |
| **Milestone 3: Model Building & Tuning** | One-hot encode categorical features, train Multiple Linear Regression baseline, evaluate MAE, RMSE, and $R^2$. | October 14, 2026 |
| **Milestone 4: Presentation Preparation** | Assemble slide deck (PPT), organize visual plots, rehearse team presentation. | October 17, 2026 |
| **Milestone 5: Project Presentation** | In-class team presentation during regular class/lab session. | October 19, 2026 |
| **Milestone 6: Final Deliverables Submission** | Complete comprehensive MS Word final report and finalize PPT submission. | October 21, 2026 |
