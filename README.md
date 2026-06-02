# Hi, I'm Michael Potishman 👋

I'm a Computer Science student with a passion for building full-stack applications and machine learning systems. Currently on placement at **PwC**, working in the Product Service Support team where I design and build automation tools in Python to eliminate manual workflows.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/michael-potishman-35b145280/)

---

## 🚀 Notable Projects

### [Pilot](https://github.com/mpotishman/Pilot---TV-Show-Rating-Website) — TV Tracking Web App
<p align="center">
  <img width="420" alt="Home Page 
" src="https://github.com/user-attachments/assets/8f1d5b09-cd38-429c-860c-5e103161e5ab" />
  <img width="420" alt="Simulate Matchup" src="https://github.com/user-attachments/assets/bbf0867c-954c-4a35-9dde-c89022a506a6" />
</p>

*Technologies: Next.js App Router, React, SQLite, Lucia Auth, Tailwind CSS, TMDB API*

- Built a full-stack TV tracking app where users can browse trending shows, rate individual episodes, manage a watchlist, and view personal stats on a profile page.
- Implemented a complete authentication system from scratch using **Lucia Auth** with secure session cookies and password hashing.
- Designed a relational SQLite schema with foreign keys, indexes, and transactional writes to maintain episode ratings, stats, and activity feeds.
- Integrated the **TMDB API** with Next.js ISR caching for efficient data fetching across show pages, episode details, cast, and similar shows.
- Built live search with a debounced dropdown and a dedicated results page using server components.

---

### [Tennis Predictor](https://github.com/mpotishman/Tennis-Prediction) — ML Tournament Simulator

<p align="center">
  <img width="420" alt="Simulate Tournament" src="https://github.com/user-attachments/assets/92d19ca0-e84d-449d-9b90-9e0086af0345"/>
  <img width="420" alt="Simulate Matchup" src="https://github.com/user-attachments/assets/5bcfc859-e178-413c-b2a2-25af0f319a9d" />
</p>

*Technologies: Python, XGBoost, scikit-learn, pandas, Next.js, Tailwind CSS*

- Built a machine learning pipeline that trains on historical ATP match data to predict tennis match outcomes, achieving strong test accuracy on the 2026 Australian Open.
- Engineered 11 sequential features per match including **ELO ratings**, surface-specific ELO, head-to-head records, serve statistics, and days rest — all computed in strict chronological order to prevent data leakage.
- Implemented a **Monte Carlo tournament simulator** that runs 1,000+ simulations to generate probabilistic bracket predictions with per-match win percentages.
- Built a **Next.js frontend** with an interactive bracket visualisation, head-to-head matchup tool, and support for comparing players across different eras using a year slider.
- Supports three model types: **XGBoost**, Random Forest, and Logistic Regression, selectable at runtime with configurable feature sets.

---

## 🛠 Tech Stack

**Languages:** Python · JavaScript · SQL  
**Frontend:** Next.js · React · Tailwind CSS  
**Backend / Data:** SQLite · pandas · scikit-learn · XGBoost  
**Tools:** Git · Node.js · REST APIs
