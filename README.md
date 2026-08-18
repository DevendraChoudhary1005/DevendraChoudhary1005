<div align="center">

<img src="https://raw.githubusercontent.com/DevendraChoudhary1005/DevendraChoudhary1005/main/hero-banner.svg" width="100%"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=1A56DB&center=true&vCenter=true&width=650&lines=Hybrid+ML+%2B+LLM+Systems+Builder;Fake+News+Detection+%40+96.77%25+Accuracy;Cloud+Security+%26+Anomaly+Detection;Multi-Agent+RAG+Applications;Turning+Messy+Data+Into+Real+Decisions)](https://git.io/typing-svg)

<p>
<a href="https://www.linkedin.com/in/devendra-choudhary-dc101005"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:dchoudhary10102005@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://github.com/DevendraChoudhary1005"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"/></a>
</p>

<img src="https://komarev.com/ghpvc/?username=DevendraChoudhary1005&color=1a56db&style=for-the-badge&label=PROFILE+VIEWS"/>

</div>

<img src="https://capsule-render.vercel.app/api?type=venom&color=0:1A56DB,100:0D1117&height=100&section=header"/>

<br/>

## 🧭 Quick Nav

<div align="center">

[⚡ About](#-about-me) · [🚀 Flagship Builds](#-flagship-builds) · [🧰 Toolbox](#-toolbox) · [💼 Experience](#-experience) · [📊 GitHub Stats](#-github-activity) · [🏆 Trophies](#-trophy-case) · [📫 Connect](#-lets-build-something)

</div>

<br/>

## ⚡ About Me

```python
class Devendra:
    def __init__(self):
        self.role        = "CS Undergraduate — AI & ML Specialization"
        self.university  = "JECRC University, Jaipur"
        self.cgpa        = 8.68  # /10
        self.grad_year   = 2027
        self.focus       = ["Hybrid ML+LLM Systems", "NLP", "Anomaly Detection", "Agentic RAG"]
        self.philosophy  = "Ship it end-to-end — a model isn't done until someone can use it."

    def currently_building(self):
        return "AI that doesn't just predict — it explains, and knows when to ask for help."

me = Devendra()
```

<img align="right" width="300" src="https://github-readme-stats.vercel.app/api?username=DevendraChoudhary1005&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true&bg_color=0D1117&border_radius=10"/>

- 🔭 Currently building **ThreatVision** — an AI-powered cloud security monitoring platform
- 🧠 Obsessed with systems that combine **classical ML + LLMs** — fast *and* smart, not one or the other
- 📊 Ranked in a **Kaggle anomaly-detection competition** (CEIP-DS-JECRC) — imbalanced multivariate time-series, XGBoost, PR-AUC optimization
- 🌱 Always learning — currently deepening my grip on cloud-native security and agentic AI workflows
- ⚡ Fun fact: my fake-news detector automatically calls in a bigger LLM only when it's genuinely unsure — it knows its own limits

<br clear="right"/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1A56DB,100:0D1117&height=3&section=header"/>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&pause=1200&color=1A56DB&center=true&vCenter=true&width=550&lines=Here's+what+I've+actually+shipped+%F0%9F%91%87)](https://git.io/typing-svg)

</div>

## 🚀 Flagship Builds

<table>
<tr>
<td width="50%" valign="top">

### 🛡️ [CREDIBLE](https://github.com/DevendraChoudhary1005/Credible2.0)
**Hybrid Fake News Detection Platform**

A dual-engine system: a 5-model ML ensemble handles most predictions instantly, and automatically hands off to an LLM only when confidence is low.

```
Dataset     72,134 articles (WELFake)
Accuracy    96.77% (weighted voting ensemble)
Fallback    Groq · Llama 3.3 70B
Interface   Streamlit — live, interactive
```

**Models:** Logistic Regression · Random Forest · Naive Bayes · Gradient Boosting · Linear SVC

`Python` `scikit-learn` `Groq API` `Streamlit` `Plotly`

</td>
<td width="50%" valign="top">

### 🕵️ [ThreatVision](https://github.com/DevendraChoudhary1005/ThreatVision)
**AI-Powered Cloud Security Monitoring**

Analyzes system logs in real time to flag brute-force attempts, unauthorized access, and irregular activity — before it becomes a breach.

```
Detection   Isolation Forest + UBA
Scoring     Risk-level threat model
Signals     Login patterns · Geo-IP · Event frequency
Deployment  Docker · AWS
```

**Approach:** statistical anomaly detection over rigid rule-matching — catches what a static rulebook would miss.

`Python` `scikit-learn` `FastAPI` `Docker` `AWS`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🤖 [ClauseGuard](https://github.com/DevendraChoudhary1005/ClauseGuard)
**Multi-Agent RAG Document Assistant**

A full-stack agentic system for semantic search and Q&A over PDFs — citation-backed, not just plausible-sounding.

```
Agent       LangGraph ReAct · Groq Llama 3.1
Retrieval   PostgreSQL + pgvector (cosine similarity)
Ingestion   Docling → async pipeline → live status
```

`FastAPI` `LangGraph` `pgvector` `Docling` `Docker`

</td>
<td width="50%" valign="top">

### 📈 Kaggle — CEIP-DS-JECRC
**Imbalanced Time-Series Anomaly Detection**

Multivariate sensor data, ~1% real anomalies — accuracy is a trap here, so the real work was elsewhere.

```
Model       XGBoost
Metric      PR-AUC (not accuracy — on purpose)
Challenge   Severe class imbalance
```

**Key insight:** discrete log-encoded sensors needed custom binary indicator features — rolling averages alone hid the signal.

`Python` `XGBoost` `Feature Engineering`

</td>
</tr>
</table>

<details>
<summary>📚 <b>Foundational repos</b> (learning-in-public, click to expand)</summary>
<br/>

| Repo | What's inside |
|---|---|
| [Basics-Of-Python](https://github.com/DevendraChoudhary1005/Basics-Of-Python) | Practical Python fundamentals — scripting → data science basics |
| [Object-Oriented-Programming](https://github.com/DevendraChoudhary1005/Object-Oriented-Programming) | Encapsulation, Inheritance, Polymorphism, Abstraction — clean examples |
| [Functions](https://github.com/DevendraChoudhary1005/Functions) | Python functions, decorators, closures, higher-order functions |
| [File-and-Exception-Handling](https://github.com/DevendraChoudhary1005/File-and-Exception-Handling) | Secure file I/O, context managers, production-grade error handling |

</details>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1A56DB,100:0D1117&height=3&section=header"/>

## 🧰 Toolbox

<div align="center">

**ML & Deep Learning**
<br/>
<img src="https://skillicons.dev/icons?i=python,pytorch,sklearn,opencv" />

**NLP, AI & Agents**
<br/>
<img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black"/> <img src="https://img.shields.io/badge/Groq_API-F55036?style=flat-square&logo=groq&logoColor=white"/> <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white"/> <img src="https://img.shields.io/badge/NLTK-154F5B?style=flat-square&logo=python&logoColor=white"/>

**Data & Analysis**
<br/>
<img src="https://skillicons.dev/icons?i=pandas" /> <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white"/> <img src="https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white"/> <img src="https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black"/> <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white"/>

**Backend, Infra & Deployment**
<br/>
<img src="https://skillicons.dev/icons?i=fastapi,flask,docker,git,aws,postgres" />

**Tools**
<br/>
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white"/> <img src="https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white"/>

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1A56DB,100:0D1117&height=3&section=header"/>

## 💼 Experience

<table>
<tr><td>

**AI / Software Engineering Intern** — IntersElite · *Oct 2023 – Dec 2023 · Remote*

- 📈 Built a **Stock Analysis platform** using AutoTS & yFinance API on 2 years of OHLCV data — surfacing price trends and market signals for stakeholders
- 💬 Ran **sentiment analysis on Flipkart product reviews** (NLTK VADER) as an additional signal layer
- 🔁 Worked in agile sprints — requirement discussions, code review, and iterative delivery with regular stakeholder check-ins

</td></tr>
</table>

---

## 🎓 Education

**B.Tech, CSE — AI & ML Specialization**
JECRC University, Jaipur, India · Jul 2023 – Jun 2027 · **CGPA: 8.68 / 10**

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1A56DB,100:0D1117&height=3&section=header"/>

## 📅 Contribution Calendar

<div align="center">

<img src="https://ghchart.rshah.org/1A56DB/DevendraChoudhary1005" width="100%"/>

</div>

## 📊 GitHub Activity

<div align="center">

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=DevendraChoudhary1005&layout=compact&langs_count=8&theme=tokyonight&hide_border=true&bg_color=0D1117"/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=DevendraChoudhary1005&theme=tokyonight&hide_border=true&background=0D1117"/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=DevendraChoudhary1005&bg_color=0D1117&color=1A56DB&line=1A56DB&point=FFFFFF&area=true&hide_border=true"/>

</div>

## 🏆 Trophy Case

<div align="center">
<img src="https://github-profile-trophy.vercel.app/?username=DevendraChoudhary1005&theme=radical&no-frame=true&row=1&column=6&margin-w=8"/>
</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1A56DB,100:0D1117&height=3&section=header"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&pause=1200&color=1A56DB&center=true&vCenter=true&width=550&lines=Let's+build+something+worth+shipping+%E2%86%93)](https://git.io/typing-svg)

---

## 📫 Let's Build Something

<div align="center">

Open to **AI/ML Engineer**, **Data Analyst**, and **Software Engineering** roles & internships.
If you're working on something that combines real data with real impact — let's talk.

<a href="mailto:dchoudhary10102005@gmail.com"><img src="https://img.shields.io/badge/Email_Me-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/devendra-choudhary-dc101005"><img src="https://img.shields.io/badge/Connect_on_LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>

<br/><br/>

*"Building AI that doesn't just predict — it explains, and knows when to ask for help."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,100:1A56DB&height=100&section=footer"/>

</div>
