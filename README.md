# 🚀 ML Foundations & AI Systems Refresh

A granular tracker bridging university-level data science foundations with production ML and modern AI systems — structured around a sprint at Astrikos AI.

---

## 📊 Sprint Overview
* **Start Date:** June 18, 2026
* **Target Completion:** June 28, 2026

### 🚦 Progress Matrix
| Module / Phase | Hours Allocated | Status | Last Reviewed |
| :--- | :---: | :---: | :--- |
| **Module 1:** SQL & Relational Analytics | 8h | 🟫 In Progress | June 23, 2026 |
| **Module 2:** Statistics & Data Manipulation | 8h | ✅ Completed | June 22, 2026 |
| **Module 3:** Classical ML & Time Series | 30h | 🟫 In Progress | June 24, 2026 |
| **Module 4:** Generative AI & LLM Systems | 24h | ⬜ Not Started | — |

---

## 🗺️ Master ML Tracker

<!--*Legend: ⬜ Not Started | 🟡 Needs Review | ✅ Completed & Mastered*-->

### 📂 Module 1: SQL & Relational Analytics
*Goal: Refresh relational data manipulation and analytical queries for feature engineering.*

* ✅ **SQL Basics**
  * ✅ `SELECT`, `FROM`, `WHERE`, `ORDER BY`, `LIMIT`

* ✅ **SQL Intermediate Analytics**
  * ✅ `GROUP BY`, `HAVING`, `DISTINCT`, `CASE`
  * ✅ Aggregate Functions: `SUM`, `AVG`, `COUNT`, `MIN`, `MAX`

* ✅ **Relational Algebra (Joins)**
  * ✅ `INNER JOIN`
  * ✅ `LEFT JOIN`
  * ✅ `RIGHT JOIN`
  * ✅ `FULL JOIN`

* ⬜ **Advanced SQL Analytics**
  * ⬜ Common Table Expressions (CTEs)
  * ⬜ Subqueries
  * 🟡 String Functions (`CONCAT`, `TRIM`)
  * ⬜ Window Functions: `RANK`, `ROW_NUMBER`, `LEAD`, `LAG`
  * ⬜ Practice: Solve 3–5 targeted problems on HackerRank / LeetCode

---

### 📂 Module 2: Statistics & Data Manipulation
*Goal: Re-verify statistical mechanics and Python data science libraries.*

* ✅ **Statistics & Probability**
  * ✅ Descriptive Stats: Mean, Median, Mode, Standard Deviation, Variance
  * ✅ Distributions: Normal, Binomial, Poisson
  * ✅ Outlier Management: Identifying via Z-scores or IQR
  * ✅ Outlier Actions: Deciding whether to cap, transform, or remove
  * ✅ Hypothesis Testing: P-values, Null vs. Alternative Hypothesis
  * ✅ A/B Testing basics
  * ✅ Correlation vs. Causation principles

* ✅ **Programming for Data (Python)**
  * ✅ Fundamentals: Variables, Loops, Functions, Lists
  * ✅ Pandas & NumPy: Vectorized array operations, DataFrames filtering, merging, cleaning
  * ✅ Visualization: Matplotlib and Seaborn chart generation

---

### 📂 Module 3: Classical Machine Learning & Time Series
*Goal: Refresh core ML paradigms, regularization, anomaly detection, and forecasting.*

* ⬜ **Production ML**
  * ✅ Deployment: Batch vs. real-time inference, model versioning, latency
  * ⬜ Monitoring: Data Drift vs. Concept Drift — detection and response
  * ⬜ Continual Learning: Retraining pipelines as new data arrives

* ⬜ **Feature Engineering & Selection**
  * ⬜ Filter, Wrapper, and Embedded methods
  * 🟡 Dimensionality Reduction: PCA & the Curse of Dimensionality
  * 🟡 Model Selection: Choosing feature engineering based on model architecture

* ⬜ **Supervised Learning Deep Dive**
  * 🟡 Core Paradigm: Supervised vs. Unsupervised operational differences
  * 🟡 Algorithm Choice: Tree-based vs. Regression-based models for regression tasks
  * 🟡 Feature Scaling/Normalization: Mandatory vs. Optional by model type
  * 🟡 Ensemble Methods: Bagging (variance reduction) vs. Boosting (bias reduction)
  * 🟡 Neural Mechanics: Activation functions and Loss functions for classification vs. regression

* ⬜ **Unsupervised Learning & Anomaly Detection**
  * 🟡 Clustering: K-Means, DBSCAN, Hierarchical Clustering
  * ✅ Anomaly Detection: Isolation Forest
  * ⬜ Anomaly Detection: LSTM Autoencoder on time-series data
  * ⬜ Cluster Evaluation: Silhouette Coefficient
  * 🟡 Bias-Variance Tradeoff: Underfitting vs. Overfitting
  * 🟡 Overfitting Fixes: Complexity tuning, adding data, Cross-Validation
  * 🟡 Regularization: L1/Lasso vs. L2/Ridge
  * 🟡 Optimization: Gradient Descent — Batch, SGD, Mini-Batch
  * 🟡 Imbalanced Data: Resampling, Class weighting, Precision/Recall/F1
  * 🟡 Metrics Evaluation: Precision vs. Recall, Adjusted R² vs. R²

* ⬜ **Time Series Analysis**
  * ⬜ Components: Trend, Seasonality, Cyclical, Noise
  * ⬜ Structural Models: Additive vs. Multiplicative
  * ⬜ Stationarity: Definition, testing, mathematical necessity
  * ⬜ Transformation: Differencing and Autocorrelation (ACF/PACF)
  * ⬜ Forecasting Frameworks: ARIMA and Prophet

---

### 📂 Module 4: Generative AI & LLM Systems
*Goal: Master Transformer mechanics, RAG pipelines, and agentic orchestration.*

* ⬜ **Transformer Architecture & Mechanics**
  * 🟡 Core Concepts: Self-Attention, Multi-head Attention, Feed-Forward Networks
  * 🟡 Input Pipelines: Tokenization and Positional Encoding
  * 🟡 Q, K, V matrices and attention scores
  * 🟡 Context-aware representations vs. static embeddings (GloVe vs. BERT)
  * 🟡 Text Generation: Decoder blocks, Masked Self-Attention (causal masking)
  * 🟡 Output Layer: Next-token prediction via logits/softmax, Temperature control

* ⬜ **Architectures & Optimization (RAG vs. Fine-Tuning)**
  * ⬜ Strategy Matrix: RAG (factual lookup) vs. Fine-Tuning (behavioral adaptation)
  * ⬜ PEFT: Freezing base weights, training <1% of parameters
  * ⬜ LoRA: Lower-rank matrix decomposition
  * ⬜ QLoRA: 4-bit quantization for lower VRAM usage

* ⬜ **Retrieval-Augmented Generation (RAG) Pipelines**
  * ⬜ Storage: Vector Databases (FAISS) and embedding models
  * ⬜ Distance Metrics: Cosine Similarity vs. Euclidean Distance
  * ⬜ Advanced Retrieval: Semantic/hierarchical chunking, Metadata enrichment
  * ⬜ Post-Processing: Reranking step (Cross-encoder / BERT)
  * ⬜ Keyword Fallback: BM25 (Term Frequency, IDF, document length normalization)

* ⬜ **AI Agents, Orchestration & Safety**
  * ⬜ Core Frameworks: LangChain and AgentExecutor (using Groq for testing)
  * ⬜ Execution Loops: ReAct (Reason-Action-Observation) workflow
  * ⬜ Error Feedback: Passing parsing errors back as observations for self-correction
  * ⬜ Evaluation Framework: Answer Relevance, Context Precision, Context Recall
  * ⬜ Safety & Validation: Enforcing JSON structures using Pydantic (`BaseModel`)
  * ⬜ State Management: Conversational Buffer Memory and Summary Memory

---

## 📚 Resources

### Production ML
| Topic | Resource |
| :--- | :--- |
| Deployment, drift & monitoring | [Chip Huyen — DMLS Ch. 6, 7, 8, 9 (free summaries)](https://github.com/serodriguez68/designing-ml-systems-summary) |
| Monitoring in practice | [Evidently AI — ML Monitoring Guide](https://www.evidentlyai.com/ml-in-production/model-monitoring) |
| Airbnb Case Study | [Using Machine Learning to Predict Value of Homes on Airbnb](https://medium.com/airbnb-engineering/using-machine-learning-to-predict-value-of-homes-on-airbnb-9272d3d4739d) |

### Module 1 — SQL
| Topic | Resource |
| :--- | :--- |
| Basics through advanced | [Mode SQL Tutorial](https://mode.com/sql-tutorial/) |
| Window functions | [Mode — Window Functions](https://mode.com/sql-tutorial/sql-window-functions/) |
| Practice | [LeetCode SQL 50](https://leetcode.com/studyplan/top-sql-50/) |

### Module 2 — Statistics
| Topic | Resource |
| :--- | :--- |
| Distributions, hypothesis testing, outliers | [StatQuest — Statistics Playlist](https://www.youtube.com/@statquest/playlists) |
| A/B Testing | [Evan Miller — A/B Testing Guide](https://www.evanmiller.org/ab-testing/) |

### Module 3 — Classical ML & Time Series
| Topic | Resource |
| :--- | :--- |
| Classical ML — full overview | [Scikit-learn User Guide](https://scikit-learn.org/stable/user_guide.html) |
| Ensemble methods, PCA, clustering | [StatQuest — ML Playlist](https://www.youtube.com/@statquest/playlists) |
| Anomaly Detection — classical | [Andrew Ng ML Specialization, C3W3](https://www.coursera.org/specializations/machine-learning-introduction) *(free to audit)* |
| Anomaly Detection — LSTM Autoencoder | [Coursera Project — Anomaly Detection in Time Series with Keras](https://www.classcentral.com/course/anomaly-detection-time-series-keras-19381) |
| Time series — full | [FPP3 — Forecasting: Principles and Practice](https://otexts.com/fpp3/) *(free online)* |

### Module 4 — Generative AI & LLMs
| Topic | Resource |
| :--- | :--- |
| Transformer intuition | [3Blue1Brown — Attention in Transformers](https://www.youtube.com/watch?v=eMlx5fFNoYc) |
| RAG pipelines | [Pinecone — RAG Guide](https://www.pinecone.io/learn/retrieval-augmented-generation/) |
| LoRA & QLoRA | [Sebastian Raschka — LoRA explained](https://sebastianraschka.com/blog/2023/llm-finetuning-lora.html) |
| LangChain agents | [LangChain — Quickstart](https://python.langchain.com/docs/get_started/quickstart) |
| RAG evaluation | [RAGAS](https://docs.ragas.io/en/latest/) |

---

## ⏱️ Rough Timeline

| Days | Focus |  
| :--- | :--- |  
| **Day 1** | Production ML first -> Case Study & DMLS |  
| **Day 2** | Production ML -> DMLS, Implementation. Module 2 stat gaps |   
| **Day 3** | Module 3 unsupervised learning → clustering → anomaly detection |  
| **Day 4** | Module 3 time series — components, stationarity, ACF/PACF |  
| **Day 5** | Module 3 time series — ARIMA, Prophet → LSTM autoencoder project |  
| **Day 6** | Module 4 transformer architecture → RAG pipelines |  
| **Day 7** | Module 4 fine-tuning strategies (LoRA, QLoRA) → agents & orchestration |  
| **Day 8** | Module 4 safety & evaluation → wrap-up, deferred topics, review |  

<!-- > Production ML is Day 1 because it reframes everything that follows. Understanding how models are deployed, monitored, and maintained in the real world changes how you read every algorithm and technique in Modules 1–4. -->

---

## 📓 Daily Study Logs & Progress Notes

### Day 0: 17/06
* **Focus:**
  Setup, identifying necessary topics, initializing this repository
* **Completed Micro-topics:**
  Programming section in Module 2
* **Blockers/Insights encountered:**
  Lots of coursework overlap — some topics need refreshing while others require more in-depth understanding. Updated in table.

---

### Day 1: 18/06
* **Focus:**
  Complete setup with timeline
  Basic ML review
  airbnb case study
  Production ML first — deployment, drift, monitoring, continual learning
* **Completed Micro-topics:**
  Setup completed. 
  Basic ML review, airbnb case study notes in module-3.md
  Started DMLS
* **Blockers/Insights encountered:**
  Ran thru the entire ml production process in theory (airbnb case study), learned the questions we need to be asking for productionization of code. 
---

### Day 2: 19/06
* **Focus:**
  DMLS 
* **Completed Micro-topics:**
  DMLS chapter 6
* **Blockers/Insights encountered:**
  dmls is heavy, takes time to make notes on the chapter but going back and looking at self-summarized takeaways is a good way to remember key points
---

### Day 3: 22/06
* **Focus:**
  module 2 stats  
* **Completed Micro-topics:**
  outliers, hypothesis testing, a/b testing, causation vs correlation
* **Blockers/Insights encountered:**
  none
---

### Day 4: 23/06
* **Focus:**
  module 1 sql 
* **Completed Micro-topics:**
  sql basics, advanced ctes, window functions, subqueries 
* **Blockers/Insights encountered:**
  yet to do practice problems 
---

### Day 5: 24/06
* **Focus:**
  dmls ch7-9
  code something
* **Completed Micro-topics:**
  dmls ch7. implementation of anomaly detection using isolation forests 
* **Blockers/Insights encountered:**

---

### Day 6: 25/06
* **Focus:**

* **Completed Micro-topics:**

* **Blockers/Insights encountered:**

---

### Day 7: 26/06
* **Focus:**

* **Completed Micro-topics:**

* **Blockers/Insights encountered:**

---

### Day 8: 27/06
* **Focus:**

* **Completed Micro-topics:**

* **Blockers/Insights encountered:**

---

### Day 9: 28/06
* **Focus:**

* **Completed Micro-topics:**

* **Blockers/Insights encountered:**

---

### Wrap-up: 
* **Modules completed:**

* **Topics deferred to next sprint:**

* **Key things to discuss with Astrikos ML team:**