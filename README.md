# 👋 Hi, I'm Molka Jebali

### Data Analytics & Computer Science Engineering Student

I am a second-year engineering student at **ESPRIT** and a Master's student in Big Data Analytics & E-Commerce at **IHEC Carthage**, with a Bachelor's degree in Business Intelligence (with distinction). I turn data into decisions, from data warehouses and dashboards to machine learning models and web applications deployed in production.

🔎 **Open to a PFE (end-of-studies) internship starting February 2027** in Data Analytics, Business Intelligence or Data Engineering.

---

## 🧰 Tech Stack

| Domain | Tools |
|---|---|
| **Data Analytics & BI** | Power BI (DAX), Apache Superset, SQL, Excel |
| **Data Engineering** | SSIS (ETL), Data Warehousing, SQL Server, Hadoop / MapReduce |
| **Machine Learning & AI** | Python, XGBoost, CatBoost, SVM, PCA, NLP, LLM & RAG |
| **Databases** | PostgreSQL, MySQL, SQLite, MongoDB |
| **Development** | Java, TypeScript, Next.js, Angular, Spring Boot, REST APIs, PHP, Flutter |
| **DevOps & Methods** | Linux (Ubuntu), Nginx, PM2, Git & GitHub, Agile / Scrum |

---

## 🚀 Featured Projects

### 📊 Staffing & Performance Platform: *Biware Consulting* (Bachelor's final-year project, team of two)
An end-to-end decision-support solution for staffing management.
- **Data Warehouse**: dimensional model (1 fact table, 4 dimensions) built in 3 layers (staging, DWH, data mart) with **SSIS** pipelines deployed on SQL Server and scheduled automatically.
- **Power BI**: **3 dashboards** and **22 DAX measures** (completion rate, planned vs actual hours, late tasks), embedded in the web app.
- **Machine Learning**: compared **6 regression models** to predict task effort; **XGBoost** performed best (MAE 2.14 h, R² 0.54).
- **Full-stack app**: Angular + Spring Boot with JWT security, manager/collaborator workspaces and a chatbot connected to the prediction model.
- *Source data was enriched with Python-generated synthetic records.*

**Stack:** SSIS · SQL Server · Power BI · Python · XGBoost · Angular · Spring Boot

### 🩺 AI Health Companion (RAG + LLM)
A multilingual health assistant designed to reduce LLM hallucinations.
- **RAG** over **100+ curated medical documents** (WHO, Institut Pasteur de Tunis, Vidal), generation with **Llama 3.3 70B** via Groq.
- **NLP pipeline**: emergency detection, 4-class emotion analysis, entity extraction; supports **French, English and Arabic (including Tunisian Derja)**.
- Voice input (Whisper), spoken answers, prescription reading with a vision model.
- MySQL conversation history, JWT authentication and an analytics dashboard.
- *Only synthetic user data was used (no real patient data).*

**Stack:** Python · LLM / RAG · NLP · MySQL · JWT · React

### 🔬 White Blood Cell Classification (SVM)
- **105 handcrafted features** (texture: histogram, GLCM/Haralick, LBP; shape: area, circularity, Hu moments) on 362 images and 4 imbalanced classes.
- RBF SVM tuned with **GridSearchCV**; best configuration (texture + shape): **accuracy 0.616, F1 0.574**.
- Key insight: texture features far outperform shape, and classes under ~50 images could not be learned, which shows the importance of data volume.

**Stack:** Python · scikit-learn · feature engineering

### ❤️ Stability of CatBoost with and without PCA
- Heart Disease dataset (1,025 patients, 13 features): **100 random train/test splits** with and without PCA (95% variance kept).
- Score distributions compared with **Kernel Density Estimation**: mean F1 0.9975 vs 0.9963, std 0.0062 vs 0.0077, so PCA brings no real gain here.
- *Possible improvement: re-run after removing duplicate records, which this version of the dataset contains.*

**Stack:** Python · CatBoost · PCA · KDE

### 🛍️ ZS-Beauty E-commerce Platform: *Bouabid Bee Growth internship*
- Designed, built and deployed **solo in 6 weeks**: Next.js (App Router), TypeScript, Tailwind CSS, Prisma.
- **25 use cases and 13 entities**: catalog, persistent cart, promo codes, reviews, order tracking and an admin back-office with sales KPIs and data export.
- Secured with Zod validation and atomic transactions; deployed on an **Ubuntu VPS** with Nginx, PM2 and HTTPS.

**Stack:** Next.js · TypeScript · Prisma · Nginx · Linux

### More projects
- **Hadoop MapReduce**: Python mapper/reducer jobs with Hadoop Streaming on a Cloudera VM.
- **Banking Dashboard (Power BI)**: interactive dashboard for performance tracking and risk analysis.
- **E-commerce app (PHP/MySQL)**: authentication, product management, responsive design.
- **Flutter apps**: task manager with CRUD operations and a personal portfolio app.

---

## 🎓 Education
- **ESPRIT**: Engineering Cycle, Data Analytics & Computer Science (2025 – present)
- **IHEC Carthage**: Professional Master's in Big Data Analytics & E-Commerce (2025 – present)
- **IHEC Carthage**: Bachelor's in Business Intelligence, with distinction (2022 – 2025)

## 🌍 Languages
Arabic (native) · French (fluent) · English (fluent)

## 📫 Let's connect
- 📧 molka.jbeli25@gmail.com
- 💼 [LinkedIn](https://www.linkedin.com/in/jebali-molka)
- 📱 +216 26 562 760

*Let's turn data into impact.* ✨
