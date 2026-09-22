### Hi, I'm Tal 👋

I'm a data scientist with an MS in Information Studies from UT Austin (GPA 4.0), focused on healthcare and public-safety analytics. I design, build, and deploy machine learning solutions on large-scale operational and regulated datasets, turning complex analysis into insights people can act on.

📍 Austin, TX &nbsp;·&nbsp; 🔗 [LinkedIn](https://www.linkedin.com/in/tal-asoolyn-9599401b8/)

---

### Featured projects

#### 🚑 [NYC EMS Response Time Analysis](https://github.com/Talasoolyn/ems-response-time-analysis)
*MS capstone, UT Austin (2026)*

Analyzed the full EMS call lifecycle in NYC using FDNY dispatch data (~28.7M records). Engineered temporal, cyclical, spatial, and rolling-window features, compared **8 models** (linear regression, random forest, gradient boosting, XGBoost, LightGBM, MLP, LSTM, and an ensemble), and used a **DeepSurv survival model** to estimate the probability of delayed ambulance arrival in different scenarios, such as weekday rush hour vs. weekend night.

**Findings:** Tree-based ensembles outperformed linear and LSTM models. Hospital turnaround (median ≈ 40 min) and on-scene time (≈ 22 min) drive total cycle time far more than dispatch or travel.

`Python` `Machine Learning` `Deep Learning` `Random Forest` `LSTM` `DeepSurv` `pandas` `scikit-learn` `XGBoost` `LightGBM` `TensorFlow` `Survival analysis`


#### 🏈 [Does a Bigger Budget Mean Better Football?](https://github.com/Talasoolyn/ncaa-roi-analysis)

Tested whether college football programs that spend more win more, using three datasets (a 710-column federal financial file, bowl results, and season results), joined across inconsistent school names with an AI-assisted, manually verified lookup table. The same pipeline is implemented in **R, SQL (DuckDB), and Python** to compare the approaches.

**Findings:** Higher-spending programs have a higher median win percentage and more consistent results, and the gap between the top-25 and bottom-25 spenders holds across seasons from 2004 to 2021.

`R` `SQL` `DuckDB` `Python` `Quarto`

#### 🎙️ [AI Audio Detector](https://github.com/Talasoolyn/AI-Audio-Detector)
*Team project, Deep Learning and Multimodal Systems (with Sharon Lobo and Carlie Herrera)*

Detects AI-generated speech using **Wav2Vec2 embeddings** and Mel-spectrogram features on 2-second audio clips. Compared a baseline MLP, a dropout-regularized MLP, and a spectrogram-based model. Test accuracy on the Fake-or-Real dataset improved from about 53% for the first baseline to about 92% for the best model.

`Python` `Machine Learning` `Deep Learning` `MLP` `Wav2Vec2` `PyTorch` `Hugging Face Transformers` `Librosa`


#### 🧾 [Invoice Processing Automation](https://github.com/Talasoolyn/galatiq-Assessment)
*Case study prototype*

An end-to-end pipeline that automates a four-stage invoice workflow (**ingest → validate → approve → pay**), reading five file formats. An LLM handles messy text extraction and approval reasoning with a self-critique pass, while the costly business rules (such as the $10K scrutiny threshold) are enforced in plain Python. A batch runner produces an audit-friendly summary of every decision.

`Python` `LLM APIs` `SQLite` `AI-Agents` `sqlite`

---

### Skills

- **Languages:** Python, SQL, R
- **Analysis and modeling:** regression, tree-based ensembles, deep learning, survival analysis, feature engineering, entity resolution
- **Libraries and tools:** pandas, scikit-learn,NumPy, XGBoost, LightGBM, TensorFlow, PyTorch, tidyverse, DuckDB, SQLite, Quarto, Jupyter, Git
- **Domains:** healthcare, emergency services, public data

---

### Currently

Looking for data analyst and data scientist roles. Happy to talk about healthcare analytics, emergency response data, or anything on this page.
