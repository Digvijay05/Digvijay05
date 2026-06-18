# DIGVIJAY JADAV

Ahmedabad, Gujarat, India
digvijayjadav.dev@gmail.com | +91-6351753750<br>
[LinkedIn](https://www.linkedin.com/in/digvijay-jadav) | [GitHub](https://www.github.com/Digvijay05) | [Codeforces](https://codeforces.com/profile/charmingbug)

---

## EDUCATION

**[Vishwakarma Government Engineering College](https://vgecg.ac.in/)**, Ahmedabad, Gujarat<br>
Bachelor of Engineering in Computer Science and Engineering (Data Science)
Expected Graduation: 2029

**[Jawahar Navodaya Vidyalaya](https://navodaya.gov.in/nvs/nvs-school/ARVALLI/en/about_us/About-JNV/)**, Arvalli, Gujarat<br>
Class XII (PCM) — 86.6% | 2024<br>
Class X — 84.6% | 2022

---

## TECHNICAL SKILLS

**Languages:** Python, JavaScript, TypeScript, SQL, Kotlin<br>
**Backend & Systems:** FastAPI, Django, Django REST Framework, Node.js, PostgreSQL (asyncpg), MongoDB (Motor), SQLAlchemy 2.0, Celery<br>
**Frontend:** React, React Native, Vite, TailwindCSS<br>
**AI & Machine Learning:** PyTorch, Scikit-learn, XGBoost, Optuna, Pandas, NumPy, Local LLMs (Ollama, Groq)<br>
**Automation & Data Engineering:** Selenium, BeautifulSoup, Regex, n8n, Structured JSON Pipelines<br>
**DevOps & Infrastructure:** Docker, Git, GitHub Actions, Linux, Nginx, Heroku, REST API Design

---

## LANGUAGES

- **English** — Professional Working Proficiency
- **Hindi** — Native/Bilingual Proficiency
- **Gujarati** — Native/Bilingual Proficiency
- **Japanese** — Basic Working Proficiency (able to read Hiragana, Katakana, and basic Kanji; capable of simple conversational communication)

---

## ENGINEERING PROJECTS

### [CIPHER](https://github.com/Digvijay05/cipher-intel) — Autonomous Honeypot & Threat Intelligence Platform
*Python, Kotlin, FastAPI, Android, Ollama, Groq, Docker*
*Evolved from the AI Honeypot API prototype originally developed during the GUVI Hackathon.*

- Architected a decentralized, dual-layer cybersecurity platform combining an Android edge client (Kotlin) with a scalable FastAPI cloud backend to autonomously intercept and engage SMS-based threat actors in real time.
- Engineered an LLM-driven interaction pipeline leveraging both local (Ollama) and cloud (Groq) large language models to dynamically generate persona-based conversations, successfully extracting structured threat telemetry including UPI IDs, phishing URLs, and phone numbers.
- Designed an asynchronous webhook reporting system to correlate offline SMS interceptions with cloud-based semantic analysis without blocking the main application event loop, producing structured intelligence reports per engagement session.

### [FleetFlow](https://github.com/Digvijay05/fleetflow) — Concurrent Logistics & Fleet Management Platform
*FastAPI, React, TypeScript, PostgreSQL (asyncpg), SQLAlchemy 2.0, Docker* — Odoo Hackathon (February 2026)

- Engineered a high-performance fleet management platform using FastAPI, React, and async PostgreSQL, implementing a complete trip lifecycle state machine for real-time shipment tracking and dispatch coordination.
- Eliminated dispatch race conditions by implementing optimistic concurrency control with row-level locking (`SELECT ... FOR UPDATE`), guaranteeing zero double-bookings under concurrent multi-user load.
- Hardened the API infrastructure with JWT-based authentication, role-based access control (RBAC) across four operational tiers (Admin, Manager, Dispatcher, Driver), and strict global rate limiting (60 req/min, 5 req/min on auth endpoints).

### [JadavJobs Platform](https://github.com/Digvijay05/jadavjobs-main) — Content Automation System
*Python, Django, Django REST Framework, Celery, PostgreSQL, Selenium, BeautifulSoup, Heroku*

- Engineered a unified platform encompassing a [content acquisition layer](https://github.com/Digvijay05/jobs_alert_web_scraper) (Selenium/BeautifulSoup) and a robust publishing backend (Django/DRF), automating the end-to-end lifecycle of job aggregations.
- Orchestrated web scraping workers to extract, transform, and serialize unstructured job data (qualifications, deadlines, vacancies) from external sources into deduplicated, API-ready posts.
- Integrated cross-platform push notifications (iOS APNs, Android FCM) utilizing Celery-based asynchronous task processing for reliable, high-volume alert dispatch.
- Implemented a GitHub Actions CI/CD pipeline featuring automated, PostgreSQL-backed integration testing to guarantee code reliability and seamless deployments.

### [OpenMotor-Optimizer](https://github.com/Digvijay05/OpenMotor-Optimizer) — GPU-Accelerated Solid Rocket Motor Optimization Framework
*Python, PyTorch, Optuna, Streamlit, SciPy* — VGEC Rocketry Team

- Developed a physics-guided optimization pipeline for solid rocket motor design, integrating directly with the open-source C++ OpenMotor simulation engine for internal ballistics validation across BATES, Finocyl, and Star grain profiles.
- Leveraged PyTorch GPU tensors to batch-evaluate millions of candidate grain geometries against physical constraints in milliseconds, filtering infeasible designs before routing survivors to CPU-bound ballistics simulations.
- Implemented three optimization strategies — Monte Carlo sampling (GPU-accelerated), Genetic Algorithm, and Bayesian optimization (Optuna TPE) — to navigate a 9-dimensional design space, automatically exporting optimal configurations in OpenMotor-compatible `.ric` format.

### [Techware Billsoft](https://github.com/Digvijay05/techware_billsoft) — ERP & Business Operations Platform
*Python, Tkinter, PostgreSQL*

- Developed a comprehensive point-of-sale and business management ERP system using Python and PostgreSQL, consolidating billing, inventory tracking, employee management, leave administration, salary computation, and attendance tracking into a unified desktop application.
- Automated critical business workflows including dynamic invoice generation with multiple print formats (A4/A5), structured data exports (Excel/Text), and payroll computation, eliminating manual data reconciliation across billing, HR, and inventory modules.

---

## RESEARCH EXPERIENCE

### [The Preprocessing Paradox](https://github.com/Digvijay05/PreprocessingDataThesis) — Machine Learning Systems Research
*Academic Thesis | Scikit-learn, XGBoost, Pandas, NumPy, Matplotlib*

- Authored a technical thesis investigating the dominance of data pipeline architecture over algorithm selection in supervised learning, using medical insurance cost prediction as the experimental domain.
- Processed a 100,000-record dataset with 54 features, systematically identifying and neutralizing data leakage (monthly_premium correlation), dimensionality inflation from one-hot encoding, and feature interaction effects.
- Improved Random Forest R² from 0.13 to 0.97 (reducing MAE to 3.2%) by engineering domain-informed ordinal encoding, interaction features, and robust scaling, demonstrating that identical algorithms produce drastically different results depending on preprocessing decisions, outperforming raw XGBoost ensembles.

---

## HACKATHONS & COMPETITIONS

| Event | Project | Role | Year |
|:---|:---|:---|:---|
| **Smart India Hackathon (SIH) 2025** | Civic Issue Reporting System | Backend Engineer | 2025 |
| **Odoo Hackathon (February)** | [FleetFlow](https://github.com/Digvijay05/fleetflow) — Fleet & Logistics Management Platform | Full-Stack Lead | 2026 |
| **Odoo Hackathon (June)** | [VendorBridge](https://github.com/Digvijay05/VendorBridge) — Enterprise Procurement Portal | Frontend Architect | 2026 |
| **ET AI Hackathon** | [ClassifierX](https://github.com/theAurelions/the_aurelion_KDSH_2026) — Long-context narrative consistency classifier | Backend & APIs Lead | 2026 |
| **PDPU Hackathon** | [AIWomenSafety](https://github.com/Digvijay05/AIWomenSafety) — Safety Application (FastAPI backend) | Backend Engineer | 2026 |
| **GUVI Hackathon** | [AI Honeypot API](https://github.com/Digvijay05/ai-women-safety-api) — Foundation prototype for [CIPHER](https://github.com/Digvijay05/cipher-intel) | Backend Engineer | 2026 |

---

## ENGINEERING ACTIVITIES

- **VGEC Rocketry Team** — Probation Member. Developed the OpenMotor-Optimizer framework as a contribution to the team's solid rocket motor design pipeline, enabling GPU-accelerated grain geometry optimization.

---

## CERTIFICATIONS

- **Kaggle** — [Intermediate Machine Learning](https://www.kaggle.com/learn/certification/charmingbug/intermediate-machine-learning)
- **Kaggle** — [Feature Engineering](https://www.kaggle.com/learn/certification/charmingbug/feature-engineering)
- **Kaggle** — [Data Cleaning](https://www.kaggle.com/learn/certification/charmingbug/data-cleaning)
- **Kaggle** — [Data Visualization](https://www.kaggle.com/learn/certification/charmingbug/data-visualization)
- **HackerRank** — [4-Star Rating in Problem Solving](https://www.hackerrank.com/profile/djgamingttt)

---

## ACHIEVEMENTS

- Achieved a 4-Star rating in Problem Solving on [HackerRank](https://www.hackerrank.com/profile/djgamingttt), demonstrating consistent algorithmic and data structure proficiency.
- Competed in 5 hackathons across national (SIH) and corporate (Odoo) platforms, consistently delivering production-grade applications under time constraints.
- Selected as a probation member for the VGEC Rocketry Team and independently developed the team's motor optimization toolchain.

---

## INTERESTS

Culinary exploration, travel, anime, open-source intelligence (OSINT) and public information research, geopolitics, language learning (currently maintaining a 300-day Duolingo streak in Japanese), singing.
