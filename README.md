# Marc Kiobola

Data scientist with a background in mechanical engineering, sales engineering, and real estate analytics. I build models and decision-support tools for problems in the built environment — pricing, forecasting, zoning, and operational analytics.

Previously: Sales Engineer at Airex, real estate data analyst at CoStar Group. Currently: Data Science diploma candidate at BrainStation.

> *"Data only matters when it changes a decision."*

---

## Projects

### CAN-SIMPLAN — AI Urban Planning Decision Support
**City of Mississauga · Cross-functional sprint: Data Science + Engineering + UX · Pilot v1.0**

An AI-assisted decision-support platform that helps municipal planners evaluate development proposals transparently, traceably, and defensibly. Built in response to Ontario's mandate to build 1.5 million new homes — planners are being pushed to decide faster, but existing AI tools have no audit trail.

**My role:** Scraped and structured 1,247 real Mississauga Development Applications records (Jan 2025). Engineered features across four scoring domains — Urban Form, Financial Feasibility, Displacement Risk, and Environmental Impact. Designed the scoring and evaluation logic consumed directly by the software engineering team to build the backend API and planner review dashboard.

**What shipped:** A full React 19 application with a proposal queue, cross-domain risk scoring, blocking flags (planners cannot skip flagged items), a permanent audit trail, and council-ready PDF export.

**Stack:** Python · pandas · Feature Engineering · Scoring Logic · EDA · Mississauga Open Data

---

### Wealthsimple Growth Strategy Analysis
**Consumer finance complaints analysis · Team sprint**

Analysed 104,000+ consumer finance complaints (~7GB, 2021–2025) to identify where traditional financial institutions consistently fail and where Wealthsimple has a structural opportunity to differentiate.

**What I found:** 40% of complaints cluster around transaction and security failures (fraud, unauthorized transactions). 17% around account management and access. These are not random complaints — they are structural gaps a digital-first player can design around. Traditional banks struggle most on resolution time, transparency, and customer support.

**Stack:** Python · pandas · Tableau · EDA · Strategic Analysis

---

### Bassline.io — Song Popularity Prediction

Ridge regression model predicting track popularity across 18,835 songs using engineered audio features — danceability, energy, and acousticness.

**Why Ridge:** The features are correlated — energy and acousticness have a correlation of −0.66. Standard linear regression inflates coefficients under multicollinearity. Ridge penalises large coefficients, producing stable, interpretable estimates. The goal was understanding which features matter and why, not maximising accuracy.

**What I found:** Train MSE 472.0 / Test MSE 474.6 — nearly identical, confirming minimal overfitting. Danceability is the strongest positive predictor (coef +2.04). Acousticness is negative (−1.78). But the predictive ceiling is low — and that is the finding. Song popularity is driven by factors audio features cannot see: artist following, playlist placement, label backing, and promotion. Knowing where your model stops working is as valuable as the model itself.

**Stack:** Python · pandas · scikit-learn · Ridge Regression · GridSearchCV · EDA · Correlation Analysis

---

## Skills

**Strong:** Python · pandas · scikit-learn · SQL · Data Visualization (Matplotlib, Tableau)
**Working knowledge:** NumPy · Jupyter · Git/GitHub
**Currently deepening:** ML model deployment · Production pipelines

---

## Background

My engineering and sales background taught me that data only matters when it changes a decision. At Airex I saw how poor forecasting affects quoting and operations. At CoStar I saw how real estate markets move on data quality and timing. That's the lens I bring to data science — less "what's interesting" and more "what's actionable."

My plan is to bring this back to the built environment — HVAC, mechanical contracting, and energy optimisation. It's an industry generating enormous amounts of operational data with almost no one analysing it systematically yet.

---

## Connect

- [LinkedIn](https://www.linkedin.com/in/marc-kiobola/)
- [Email](Marc.kiobola@gmail.com)
