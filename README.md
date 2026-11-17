# Hi, I'm Eren Aybulus 👋

**I build ML models and then try hard to prove they don't work.** When they survive, I ship them. When they don't, I write up why.

Most of my projects are in credit risk, fraud and markets, and most of them end with an honest answer rather than a flattering one. I think "the signal isn't there" is a real result, and I'd rather report it than tune until it shows up.

[![Email](https://img.shields.io/badge/Email-Say_hi-D14836?style=flat&logo=gmail&logoColor=white)](mailto:eren.aybulus@mail.utoronto.ca)
![Open to work](https://img.shields.io/badge/Open_to-Data_%2F_ML_roles-2ea44f?style=flat)

---

## 🔬 Selected work

### [Credit Card Fraud Detection: 5 ways to handle class imbalance](https://github.com/SqualidRat560/credit-card-fraud-detection)
284,807 transactions, only 0.17% of them fraud. I trained the same XGBoost model five ways and compared them on one shared test set.
**Result:** class weighting matched SMOTE's PR-AUC (0.882) with no synthetic data. Undersampling looked like it won on recall, but it cost **212 false alarms for every extra fraud caught.**
`Python` `XGBoost` `SHAP` `imbalanced-learn`

<img src="https://raw.githubusercontent.com/SqualidRat560/credit-card-fraud-detection/master/outputs/pr_curves_all.png" width="520" alt="PR curves for five imbalance techniques">

### [Do public statements move markets? (an honest null result)](https://github.com/SqualidRat560/INVEST-)
I matched 8,331 statements from the Fed Chair, the Treasury Secretary and the President to hourly moves in gold, silver, SPY and QQQ. It comes with a live dashboard and an LLM chat assistant grounded in the project's own database.
**Result:** there was no robust correlation (r = −0.004). The one "significant" subset collapsed under a robustness check, and the sentiment signal lost to a naive baseline. The repo shows all of it.
`Python` `FinBERT` `Whisper` `FastAPI` `LLM`

<img src="https://raw.githubusercontent.com/SqualidRat560/INVEST-/main/results/scatter_sentiment_vs_change.png" width="520" alt="Sentiment vs price change scatter">

### [Regional Credit Risk Mapping](https://github.com/SqualidRat560/Regional-Credit-Risk-Mapping)
Does a borrower's state add predictive signal on top of income, DTI and grade? I built a LendingClub choropleth, an XGBoost baseline vs a model with geography, and SHAP, with explicit guards against target leakage.
`Python` `XGBoost` `GeoPandas` `SHAP`

---

## 🧩 Also built

- **[Carbon Coach](https://github.com/SqualidRat560/Carbon_Coach)**: a FastAPI backend that logs trips and meals, calculates CO2 against a daily target, and suggests specific swaps.
- **[Health Coach](https://github.com/SqualidRat560/Health_Coach)**: a hackathon project for early-warning health monitoring. Risk tiers come from declining signals, and Claude explains them. I built the Flask API.

---

## 🛠️ Tools I use

[![Skills](https://skillicons.dev/icons?i=python,sklearn,pytorch,sqlite,fastapi,flask,git&theme=light)](https://skillicons.dev)

Also: XGBoost · SHAP · pandas · GeoPandas · HuggingFace (FinBERT, Whisper) · Jupyter · Claude API

---

## 🌱 Right now

- Looking for: data science / ML analyst roles. I'm happiest with problems where getting the evaluation right matters more than getting the accuracy number up.

---

📫 The fastest way to reach me is **[email](mailto:eren.aybulus@mail.utoronto.ca)**. I reply within a day.
