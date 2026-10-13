#  Passive Sensing for Mental Wellness

> **Explainable machine learning for early depression risk screening from unobtrusive smartphone behavioral data.**

###  Overview
Traditional mental health screening relies on retrospective self-report questionnaires (like PHQ-9), which suffer from recall bias and social stigma. **Passive Sensing for Mental Wellness** is a digital phenotyping research platform that predicts potential depression risk ($\text{PHQ-9} \ge 10$) using everyday passive smartphone metrics:
-  **Sleep Patterns** (inferred bedtime, duration, sleep irregularity)
-  **Phone Usage** (unlock frequency, daily screen time)
-  **Mobility & Activity** (walking duration, location entropy)
-  **Social Audio** (ambient conversation duration)

To build user trust and transparency, every prediction is paired with **TreeSHAP** explanations that highlight the specific lifestyle factors influencing the score.

### Tech Stack
- **ML & Explainability:** Python, Scikit-learn (Decision Tree), SHAP (TreeSHAP)
- **Backend:** FastAPI, SQLite, Pydantic, Uvicorn
- **Frontend / Mobile:** Flutter (Android Native) & Responsive HTML5/CSS3 Web UI
- **Dataset:** Dartmouth StudentLife Dataset

**Disclaimer:** This project is designed strictly for research, educational awareness, and wellness screening. It is not a clinical medical diagnostic device.*
