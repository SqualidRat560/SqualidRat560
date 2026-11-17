<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=190&section=header&text=Eren%20Aybulus&fontSize=52&fontColor=ffffff&fontAlignY=36&desc=Data%20%26%20ML%20%E2%80%94%20fraud%2C%20credit%20risk%2C%20markets&descAlignY=58&descSize=18&animation=fadeIn" width="100%" alt="Eren Aybulus — Data & ML"/>

<p align="center">
  <a href="https://github.com/SqualidRat560">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3200&pause=900&color=2C9CB0&center=true&vCenter=true&width=640&lines=I+build+ML+models%2C+then+try+to+break+them.;Honest+baselines+%3E+flattering+metrics.;%22The+signal+isn't+there%22+is+a+real+result." alt="Typing intro"/>
  </a>
</p>

<p align="center">
  <a href="mailto:eren.aybulus@mail.utoronto.ca"><img src="https://img.shields.io/badge/Email-Say_hi-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <img src="https://img.shields.io/badge/Open_to-Data_%2F_ML_roles-2ea44f?style=for-the-badge" alt="Open to Data / ML roles"/>
  <img src="https://komarev.com/ghpvc/?username=SqualidRat560&style=for-the-badge&color=2c5364&label=Profile+views" alt="Profile views"/>
</p>

---

### 👋 About me

**I build ML models and then try hard to prove they don't work.** When they survive, I ship them. When they don't, I write up why.

Most of my projects are in credit risk, fraud and markets, and most of them end with an honest answer rather than a flattering one. I think "the signal isn't there" is a real result, and I'd rather report it than tune until it shows up.

---

### 🔬 Selected work

<table>
<tr>
<td width="50%" valign="top">

#### [💳 Credit Card Fraud Detection](https://github.com/SqualidRat560/credit-card-fraud-detection)
I trained the same XGBoost model **five ways** on 284,807 transactions, only 0.17% of them fraud.

**Result:** class weighting matched SMOTE's PR-AUC (**0.882**) with no synthetic data. Undersampling looked like it won on recall, but it cost **212 false alarms for every extra fraud caught.**

![XGBoost](https://img.shields.io/badge/XGBoost-189FDD?style=flat-square)
![SHAP](https://img.shields.io/badge/SHAP-FF0051?style=flat-square)
![PR-AUC](https://img.shields.io/badge/PR--AUC-0.882-2ea44f?style=flat-square)

</td>
<td width="50%" valign="top">

<a href="https://github.com/SqualidRat560/credit-card-fraud-detection"><img src="https://raw.githubusercontent.com/SqualidRat560/credit-card-fraud-detection/master/outputs/pr_curves_all.png" width="100%" alt="PR curves for five imbalance techniques"/></a>

</td>
</tr>
<tr>
<td width="50%" valign="top">

<a href="https://github.com/SqualidRat560/INVEST-"><img src="https://raw.githubusercontent.com/SqualidRat560/INVEST-/main/results/scatter_sentiment_vs_change.png" width="100%" alt="Sentiment vs price change"/></a>

</td>
<td width="50%" valign="top">

#### [📈 Do public statements move markets?](https://github.com/SqualidRat560/INVEST-)
I matched **8,331 statements** from the Fed Chair, the Treasury Secretary and the President to hourly moves in gold, silver, SPY and QQQ. It comes with a live dashboard and an LLM assistant.

**Result:** there was no robust correlation (r = −0.004). The one "significant" subset collapsed under a robustness check. That's an honest null result, and the repo shows all of it.

![FinBERT](https://img.shields.io/badge/FinBERT-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Whisper](https://img.shields.io/badge/Whisper-412991?style=flat-square)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

</td>
</tr>
<tr>
<td colspan="2" valign="top">

#### [🗺️ Regional Credit Risk Mapping](https://github.com/SqualidRat560/Regional-Credit-Risk-Mapping)
Does a borrower's state add predictive signal on top of income, DTI and grade? I built a LendingClub choropleth, an XGBoost baseline vs a model with geography, and SHAP, with explicit guards against target leakage.

![XGBoost](https://img.shields.io/badge/XGBoost-189FDD?style=flat-square)
![GeoPandas](https://img.shields.io/badge/GeoPandas-139C5A?style=flat-square)
![SHAP](https://img.shields.io/badge/SHAP-FF0051?style=flat-square)

</td>
</tr>
</table>

#### 🧩 Also built
- **[Carbon Coach](https://github.com/SqualidRat560/Carbon_Coach)**: a FastAPI backend that logs trips and meals, calculates CO2 against a daily target, and suggests specific swaps.
- **[Health Coach](https://github.com/SqualidRat560/Health_Coach)**: a hackathon project for early-warning health monitoring. Risk tiers come from declining signals, and Claude explains them. I built the Flask API.

---

### 🛠️ Tools I use

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,sklearn,pytorch,sqlite,fastapi,flask,git,github,vscode&perline=9" alt="Skills"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/XGBoost-189FDD?style=for-the-badge" alt="XGBoost"/>
  <img src="https://img.shields.io/badge/SHAP-FF0051?style=for-the-badge" alt="SHAP"/>
  <img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="pandas"/>
  <img src="https://img.shields.io/badge/GeoPandas-139C5A?style=for-the-badge" alt="GeoPandas"/>
  <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face"/>
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter"/>
  <img src="https://img.shields.io/badge/Claude_API-D97757?style=for-the-badge&logo=anthropic&logoColor=white" alt="Claude API"/>
</p>

---

### 📊 Activity

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=SqualidRat560&layout=compact&langs_count=6&theme=transparent&title_color=2c9cb0&text_color=c9d1d9&hide_border=true">
    <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=SqualidRat560&layout=compact&langs_count=6&theme=transparent&title_color=2c5364&text_color=24292f&hide_border=true" alt="Top languages"/>
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=SqualidRat560&theme=transparent&hide_border=true&ring=2c9cb0&fire=2c9cb0&currStreakLabel=2c9cb0&stroke=30363d&background=00000000&sideNums=c9d1d9&sideLabels=8b949e&dates=8b949e&currStreakNum=c9d1d9">
    <img height="165" src="https://streak-stats.demolab.com?user=SqualidRat560&theme=transparent&hide_border=true&ring=2c5364&fire=2c9cb0&currStreakLabel=2c5364&background=00000000&sideNums=24292f&sideLabels=57606a&dates=57606a&currStreakNum=24292f" alt="GitHub streak"/>
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=SqualidRat560&bg_color=00000000&color=c9d1d9&line=2c9cb0&point=ffffff&area=true&area_color=2c9cb0&hide_border=true&custom_title=Contributions%20over%20the%20last%2031%20days">
    <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=SqualidRat560&bg_color=ffffff&color=24292f&line=2c5364&point=2c9cb0&area=true&area_color=2c9cb0&hide_border=true&custom_title=Contributions%20over%20the%20last%2031%20days" alt="Activity graph"/>
  </picture>
</p>

---

### 🌱 Right now

- 🎯 **Looking for:** data science / ML analyst roles. I'm happiest with problems where getting the evaluation right matters more than getting the accuracy number up.
- 📫 **Reach me:** the fastest way is [email](mailto:eren.aybulus@mail.utoronto.ca). I reply within a day.

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=110&section=footer" width="100%" alt=""/>
