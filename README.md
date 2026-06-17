# 🚀 10-Day ML Foundations & AI Systems Refresh

A granular tracker to bridge university-level data science foundations with modern Generative AI and LLM orchestration.

---

## 📊 Sprint Overview
* **Start Date:** June 18, 2026
* **Target Completion:** June 28, 2026

### 🚦 Progress Matrix
| Module / Phase | Status | Last Reviewed |
| :--- | :---: | :--- |
| **Module 1:** SQL & Relational Analytics | ⬜ Not Started | — |
| **Module 2:** Statistics & Data Manipulation | 🟫 In Progress | June 17, 2026 |
| **Module 3:** Classical ML & Time Series | ⬜ Not Started | — |
| **Module 4:** Generative AI & LLM Systems | ⬜ Not Started | — |

<!-- *Tip: Update the Status column above to ⬜ (Not Started), 🟫 (In Progress), or ✅ (Completed) as you sweep through the sections.* -->

---

## 🗺️ Master ML Tracker
<!--*Legend: ⬜ Not Started | 🟡 Needs Review | ✅ Completed & Mastered*-->

### 📂 Module 1: SQL & Relational Analytics (Phase 1 Roadmap)
*Goal: Refresh relational data manipulation and analytical queries for feature engineering.*
* ⬜ **SQL Basics**
  * 🟡 `SELECT`, `FROM`, `WHERE`, `ORDER BY`, `LIMIT`
* ⬜ **SQL Intermediate Analytics**
  * 🟡 `GROUP BY`, `HAVING`
  * 🟡 Aggregate Functions: `SUM`, `AVG`, `COUNT`, `MIN`, `MAX`
* ⬜ **Relational Algebra (Joins)**
  * 🟡 `INNER JOIN`
  * 🟡 `LEFT JOIN`
  * 🟡 `RIGHT JOIN`
  * 🟡 `FULL JOIN`
* ⬜ **Advanced SQL Analytics**
  * ⬜ Common Table Expressions (CTEs)
  * ⬜ Subqueries
  * 🟡 String Functions (`CONCAT`, `TRIM`)
  * ⬜ Window Functions: `RANK`, `ROW_NUMBER`, `LEAD`, `LAG`
  * ⬜ Practice: Solve 3-5 targeted problems on HackerRank/LeetCode

### 📂 Module 2: Statistics & Data Manipulation (Phases 2 & 3 Roadmap)
*Goal: Re-verify statistical mechanics and Python data science libraries.*
* ⬜ **Statistics & Probability**
  * ✅ Descriptive Stats: Mean, Median, Mode, Standard Deviation, Variance
  * 🟡 Distributions: Normal Distribution, Binomial, Poisson
  * 🟡 Outlier Management: Identifying via Z-scores or IQR (Interquartile Range)
  * ⬜ Outlier Actions: Deciding whether to cap, transform, or remove them
  * 🟡 Hypothesis Testing: P-values, Null vs. Alternative Hypothesis
  * ⬜ A/B Testing basics
  * 🟡 Correlation vs. Causation principles
* ✅ **Programming for Data (Python)**
  * ✅ Fundamentals: Variables, Loops, Functions, Lists
  * ✅ Pandas & NumPy: Vectorized array operations, DataFrames filtering, merging, and cleaning
  * ✅ Visualization: Matplotlib and Seaborn chart generation

### 📂 Module 3: Classical Machine Learning & Time Series (Phase 4 Roadmap)
*Goal: Refresh core ML paradigms, regularization math, and forecasting models.*
* ⬜ **Feature Engineering & Selection**
  * ⬜ Filter, Wrapper, and Embedded methods
  * 🟡 Dimensionality Reduction: PCA & understanding the "Curse of Dimensionality"
  * 🟡 Model Selection: Choosing feature engineering based on model architecture
* ⬜ **Supervised Learning Deep Dive**
  * 🟡 Core Paradigm: Supervised vs. Unsupervised operational differences
  * 🟡 Algorithm Choice: Tree-based models vs. Regression-based models for regression tasks
  * 🟡 Feature Scaling/Normalization: Mandatory (distance-based, gradient descent) vs. Optional (tree-based)
  * 🟡 Ensemble Methods: Bagging (reducing variance) vs. Boosting (reducing bias via weights)
  * 🟡 Neural Mechanics: Activation functions and Loss functions for classification vs. regression
* ⬜ **Unsupervised Learning & Advanced Optimization**
  * 🟡 Clustering Models: K-Means Clustering, DBSCAN, Hierarchical Clustering
  * ⬜ Anomaly Detection: Isolation Forest
  * ⬜ Cluster Evaluation: Silhouette Coefficient (cohesion and separation without labels)
  * 🟡 Bias-Variance Tradeoff: Spotting Underfitting (high bias) vs. Overfitting (high variance)
  * 🟡 Overfitting Fixes: Tweaking complexity, adding data, Cross-Validation
  * 🟡 Regularization Math: L1/Lasso (pushes coefficients to zero) vs. L2/Ridge (shrinks weights)
  * 🟡 Optimization: Gradient Descent mechanics (Batch, SGD, Mini-Batch)
  * 🟡 Imbalanced Data: Resampling, Class weighting, Precision/Recall/F1-score mechanics
  * 🟡 Metrics Evaluation: Precision vs. Recall usage criteria, Adjusted $R^2$ vs. $R^2$
  * ⬜ MLOps Concepts: Data Drift vs. Concept Drift monitoring over time
* ⬜ **Time Series Analysis**
  * ⬜ Components: Trend, Seasonality, Cyclical, Noise
  * ⬜ Structural Models: Additive vs. Multiplicative models
  * ⬜ Stationarity: Definition, testing, and mathematical necessity
  * ⬜ Transformation: Differencing and Autocorrelation (ACF/PACF)
  * ⬜ Forecasting Frameworks: ARIMA and Prophet (including traditional models with external regressors)

### 📂 Module 4: Generative AI & LLM Systems (Phase 5 Roadmap)
*Goal: Master Transformer mechanics, RAG pipelines, and agentic orchestration.*
* ⬜ **Transformer Architecture & Mechanics**
  * 🟡 Core Concepts: Self-Attention, Multi-head Attention, Feed-Forward Networks
  * 🟡 Input Pipelines: Tokenization and Positional Encoding
  * 🟡 Mathematical Deep Dive: $Q, K, V$ (Query, Key, Value) matrices and attention scores
  * 🟡 Context-aware representations vs. static embeddings (e.g., GloVe vs. BERT)
  * 🟡 Text Generation Mechanics: Decoder blocks, Masked Self-Attention (causal masking)
  * 🟡 Output Layer: Next-token prediction via logits/softmax, Temperature randomness control
* ⬜ **Architectures & Optimization (RAG vs. Fine-Tuning)**
  * ⬜ Strategy Matrix: RAG (factual lookup) vs. Fine-Tuning (behavioral adaptation)
  * ⬜ PEFT: Freezing base weights and training <1% parameters
  * ⬜ LoRA Mechanics: Lower-rank matrix decomposition
  * ⬜ QLoRA Mechanics: 4-bit quantization compression for lower VRAM usage
* ⬜ **Retrieval-Augmented Generation (RAG) Pipelines**
  * ⬜ Storage: Vector Databases (FAISS) and embedding models
  * ⬜ Distance Metrics: Cosine Similarity vs. Euclidean Distance
  * ⬜ Advanced Retrieval: Semantic/hierarchical chunking, Metadata enrichment
  * ⬜ Post-Processing: Reranking step (Cross-encoder/BERT)
  * ⬜ Keyword Fallback: Traditional BM25 (Term Frequency, IDF, document length normalization)
* ⬜ **AI Agents, Orchestration & Safety**
  * ⬜ Core Frameworks: LangChain and AgentExecutor (using Groq for testing)
  * ⬜ Execution Loops: ReAct (Reason-Action-Observation) workflow
  * ⬜ Error Feedback: Passing parsing errors back as observations for self-correction
  * ⬜ Evaluation Framework: Answer Relevance, Context Precision, and Context Recall
  * ⬜ Safety & Validation: Enforcing JSON structures using Pydantic schema validation (`BaseModel`)
  * ⬜ State Management: Conversational Buffer Memory and Summary Memory

---

## 📓 Daily Study Logs & Progress Notes

### Day 0: 17/06
* **Focus:** 
Setup, identifying necessary topics, initializing this repository
* **Completed Micro-topics:** 
Programming section in module 2
* **Blockers/Insights encountered:** 
Lots of coursework overlap, some topics need refreshing while others require more in-depth understanding. Updated on table


### Day 1: 18/06
* **Focus:**
  
* **Completed Micro-topics:**
  
* **Blockers/Insights encountered:**
  

*(Duplicate day blocks as you move through the sprint)*
