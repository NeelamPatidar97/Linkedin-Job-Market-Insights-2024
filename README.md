%md
### ✨ **Author Information** 

|                    |                                                                 |
|--------------------|-----------------------------------------------------------------|
| **Author**         | Neelam Patidar                                                  |
| **Date**           | May 13, 2025                                                 |
| **Supervisor**     | Dr. Jongwook Woo                                              |
| **Affiliation**    | Big Data AI Center (BigDAI): High Performance Information Computing Center (HiPIC) |

---

### 📘 About the Project

This project presents an advanced data-driven analysis of 1.3 M job postings collected from LinkedIn in 2024, with a special focus on U.S.-based **tech job trends**. The analysis aims to uncover actionable insights for job seekers, hiring managers, and academic researchers by applying **Big Data tools**, **unsupervised machine learning**, and **content-based recommendation algorithms**.

Dataset URL- https://www.kaggle.com/datasets/asaniczka/1-3m-linkedin-jobs-and-skills-2024

#### 🔍 Objectives:
- Identify **geographic and industry-level trends** in tech hiring.
- Analyze **in-demand job titles, job levels, and company-wise hiring activity**.
- Uncover **latent skill clusters** using **LDA (Latent Dirichlet Allocation)** to group job roles based on required competencies.
- Design a **job recommendation system** using **TF-IDF vectorization and cosine similarity**, tailored to user preferences.

#### 🛠 Technologies & Techniques Used:
- **Apache Spark (PySpark)** for distributed data processing.
- **Spark MLlib** for text preprocessing, feature extraction, and topic modeling.
- **Latent Dirichlet Allocation (LDA)** to uncover dominant job skill clusters.
- **TF-IDF** for textual vectorization of job postings.
- **Content-Based Filtering Recommendation Model(Unsupervised Learning)** to suggest jobs based on user-input preferences.
- **Matplotlib & Seaborn** for data visualization.

#### Key Outcomes:
- Identified top job locations (cities, states), job types (onsite, remote, hybrid), and job levels (entry, mid-senior).
- Standardized and grouped thousands of job titles using NLP-based rules and regular expressions.
- Clustered jobs into **8 interpretable skill-based topics** (e.g., Data Science, Cloud DevOps, ERP Systems).
- Developed a **custom job recommendation system** based on semantic similarity to user input.

This pipeline demonstrates how **Big Data tools can power intelligent career insights** and guide both individuals and organizations in navigating the evolving tech job market.
