# Project Portfolio

## 1. EY Parthenon Private Equity Project: PEquity Matchmaker

**PEquity** is an AI-driven tool designed to help EY Parthenon analysts identify the most relevant private equity (PE) buyers for Spanish companies, accelerating deal origination in a competitive M&A landscape.

- **Purpose:** Streamlines target-buyer matching using machine learning and natural language processing.
- **Key Features:**
  - Predicts the top 5 PE firms most likely to acquire a given Spanish company, using sector, deal size and geography.
  - Relies on proprietary EY data covering PE firms, portfolios, and historical transactions.
  - Integrates a conversational interface using the Google Gemini 2.5 Pro LLM for interactive, natural language queries.
  - CatBoost ML engine drives similarity and behavioral matching.
  - Comprehensive analytics: display of buying patterns, sector bias, and ticket size/region focus.
  - Drilldown dashboards for detailed visual insights.
  - Upload functionality to add or enrich company data for matching.
  - Delivers significant time-savings through workflow automation.
- **Tech Stack:** Python 3.8, Streamlit, pandas, numpy, Langchain, Plotly, ChromaDB, CatBoost.
- **Future Additions:** Expansion to other geographies, CRM integrations, API development, and advanced modeling.
- **Impact:** Enables faster, smarter outreach and transforms traditionally manual PE deal origination.

---

## 2. Olympics Spark Hadoop Analysis

A comprehensive data engineering and analytics project leveraging Spark and Hadoop on Olympic datasets. The project delivers scalable big-data processing with actionable sports insights.

- **Data Scope:** Over 270,000 athlete and medal event records, spanning multiple Olympic Games.
- **Process:**
  - Data cleaning, schema unification, and outlier removal using PySpark.
  - Exploratory Data Analysis (EDA) revealing trends in medals, gender participation, athlete longevity, and sport dominance.
  - Integration of diverse datasets (athlete events and NOC regions) with distributed joins/filters.
  - Advanced feature engineering such as BMI classes, gender indexes, and country-level medal efficiency.
- **Visualization:** Key findings visualized with matplotlib and seaborn after Spark-to-Pandas aggregation.
- **Outcome:** Deep insights for sports statisticians and fans—tracking country performance, gender trends, and athlete achievements with scalable tech.

---

## 3. F1 GOAT (Greatest of All Time) Analysis

A data-driven exploration to determine Formula 1’s Greatest of All Time (GOAT) drivers using historic and modern F1 statistics.

- **Scope:** Detailed aggregation and comparison of race wins, poles, podiums, championships, and era-adjusted performance metrics across F1 history.
- **Techniques:**
  - Data cleaning and merging of multiple seasons, event results, and driver stats files.
  - Visualization and ranking using interactive dashboards and advanced analytics.
  - Accounting for context (era competitiveness, race counts, technical evolution) for fair comparisons.
- **Deliverables:** Nuanced quantitative and qualitative analysis to compare all-time F1 greats—informing fans, analysts, and historians.

---

## 4. Repsol Datathon ML Models

This project was submitted for the Repsol Datathon and focuses on energy sector analytics powered by advanced machine learning models. The project addresses forecasting and optimization challenges relevant to real-world oil & gas operations.

- **Highlights:**
  - Developed and evaluated multiple supervised learning models, including Random Forest, XGBoost, and CatBoost, for predictive analytics tasks.
  - Engineered input features from complex, multi-source operational data—handling difficult time-series challenges and domain-specific anomalies.
  - Applied ensemble techniques and automated model selection pipelines to achieve high accuracy and robustness.
  - Implemented processes for data cleaning, feature extraction, train-test workflow automation, and hyperparameter tuning.
  - Delivered actionable dashboards and visualizations for model diagnostics, feature importance, and operational recommendations.
- **Result:** 
  The solution consistently outperformed baseline benchmarks, demonstrating reliable predictions across unseen data scenarios. This project exemplifies best practices in applied data science: replicability, interpretability, and business-value-driven ML in the energy sector.

---

*For technical details and sample outputs, refer to the project files and documentation included in this repository.*
