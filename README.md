# trace-clustering-article

Welcome! Here, you'll find a collection of Google Colab notebooks used on article that explore and optimize clustering techniques, specifically tailored for applications using unsupervised learning methods. Each notebook contains code and detailed explanations, making it suitable for both beginners and experienced data scientists.

---

## 🛠️ Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/tsa2ufpe/trace-clustering-article.git

---

## 🚀 Highlights of the Repository

### 1️⃣ **Parameter Search Space Generation**  
**File:** `param_search.ipynb`  
This notebook provides a creative approach to generating a sequence of numbers for tuning the `min_cluster_size` parameter in HDBSCAN. The values are dynamically adjusted based on a starting limit and adaptive learning rates, creating a progressively narrowing search space. 

**Key Features:**
- Dynamically calculates a range of parameter values.
- Adapts sil rates over iterations for efficient optimization.
- Ideal for experimentation and fine-tuning clustering parameters.

📌 *Use this notebook to optimize clustering method parameters and ensure effective clustering results.*

---

### 2️⃣ **Steps in Clustering Methodology**
**Files:**
- `clustering_experiment_v2_c1.ipynb`
- `clustering_experiment_v2_c2.ipynb`
- `clustering_experiment_v2_c3.ipynb`

These notebooks guide you through the four key steps of clustering analysis, as described in cutting-edge research:

#### 🔍 **Feature Selection/Extraction**  
Identify the most significant attributes that distinguish patterns across clusters. Proper feature selection simplifies analysis and enhances clustering outcomes.

#### ⚙️ **Algorithm Design/Selection**  
Select the optimal clustering algorithm and proximity measure to structure your data effectively. This ensures the accuracy and relevance of the formed clusters.

#### ✅ **Cluster Validation**  
Validate the generated clusters using:
- **Structural Metrics**: Analyze cluster structure directly.
- **Behavioral Metrics**: Evaluate process mining metrics (e.g., fitness, precision, f-score, simplicity).
- **Quantitative Business Metrics**: Assess frequency and lift of key activities within clusters.
- **Qualitative Business Metrics**: Interpret results with domain experts to identify actionable insights.

#### 📊 **Result Interpretation**  
Dive deep into the insights derived from clustering, identifying behaviors and trends aligned with business goals.

📌 *Leverage these notebooks to conduct robust clustering experiments and derive meaningful insights.*

---

## 📂 Repository Structure

- **`param_search.ipynb`**: Generate a parameter search space for HDBSCAN.
- **`clustering_experiment_v2_c1.ipynb`**: First step of clustering methodology (Feature Selection).
- **`clustering_experiment_v2_c2.ipynb`**: Algorithm design and validation techniques.
- **`clustering_experiment_v2_c3.ipynb`**: Advanced validation and business interpretation.

