# ⚡ AI for Grid Collapse Prediction

This project was carried out as part of the **Deep Learning Indaba Community Challenge 2025**.  
It focuses on leveraging **Artificial Intelligence (AI)** and **Machine Learning (ML)** to build a system capable of predicting the **probability of national grid collapse** based on historical data.

---

## 🌍 Project Overview

Power grid collapse is a critical issue in many developing nations, including Nigeria, leading to widespread blackouts, economic losses, and safety risks.  
This project explores how AI can be used to **anticipate grid instability** and help authorities take **proactive measures** to prevent such collapses.

The ultimate goal is to provide a data-driven solution that can:
- Detect potential patterns leading to grid failure.  
- Predict the **likelihood of grid collapse** at specific times.  
- Support **decision-making** for improved power infrastructure management.

---

## 🧩 Data Generation

Due to the **limited availability of real-world national grid data**, this project uses **synthetically generated data** to simulate realistic grid behaviors over time.

The dataset was designed to reflect:
- Hourly and daily variations in power demand and supply.  
- Frequency fluctuations and voltage irregularities.  
- System load patterns under different operational conditions.

Although synthetic, the data was modeled to maintain realistic statistical characteristics, enabling valid experimentation and learning.

---

## 🔬 Methodology

### 1. **Data Preparation**
- Generated data was **cleaned**, normalized, and structured into **hourly** and **daily** subsets.  
- Feature engineering was applied to derive key indicators of grid health.

### 2. **Unsupervised Learning (Initial Phase)**
- **Clustering** techniques were tested using **Principal Component Analysis (PCA)** to identify latent patterns in the grid behavior.
- However, unsupervised learning resulted in **low prediction accuracy**, indicating the need for supervised approaches.

### 3. **Supervised Learning with AutoGluon**
- Adopted **AutoGluon**, an AutoML framework, to automate model selection and hyperparameter optimization.
- Multiple models were trained and evaluated automatically.
- The **Extra Trees Classifier** achieved the **best performance** in predicting grid collapse probability.

### 4. **Model Evaluation**
- Metrics such as **accuracy**, **F1-score**, and **ROC-AUC** were used to assess model performance.
- The trained model demonstrated strong predictive power on the synthetic dataset, showing the potential of AI-based monitoring systems.

---

## 🛠️ Tools and Technologies

| Tool | Purpose |
|------|----------|
| **Python** | Data generation, preprocessing, and model building |
| **AutoGluon** | Automated machine learning (AutoML) model training and selection |
| **Pandas & NumPy** | Data manipulation and analysis |
| **Matplotlib & Seaborn** | Data visualization |
| **Scikit-learn** | Model evaluation and preprocessing utilities |

---

## 📈 Results and Insights

- **Extra Trees Classifier** emerged as the top-performing model.  
- Demonstrated that **AI-driven monitoring systems** can detect instability patterns before grid failure.  
- Validated that **AutoML frameworks** can accelerate model experimentation and optimization.

---

## 🚀 Future Work

- Integrate **real-time grid data** once available.  
- Explore **deep learning models** like LSTMs or Transformers for time-series forecasting.  
- Build a **dashboard or API** for real-time prediction and visualization.  
- Investigate **feature importance** to identify key risk indicators contributing to grid instability.

---

## 🧾 Authors

**Adenike Adewumi**
**Soyinka Enoch**
**Glory Akanbi**
**Onyeibor Samuel**




