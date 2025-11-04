# NTHU MOOCs – Synthetic Dataset (Full, RL-Ready)

This repository provides a **fully synthetic** dataset that replicates the scale and structure of the NTHU MOOCs dataset.  


## 📊 Dataset Overview
- **Courses:** 320  
- **Users:** 12,800  
- **Interactions:** 420,000  


## 📁 Files Included
| File | Description |
|------|--------------|
| `courses.csv` | Course metadata including `course_id`, `title`, `category`, `difficulty`, `description`, `tags`. |
| `users.csv` | Learner attributes and IoT-style usage metrics such as `device_preference`, `session_frequency_week`, and `device_usage_freq_day`. |
| `interactions.csv` | User–course interactions with columns `action`, `timestamp`, `device_type`, `duration_hours`, `click_through_rate`, `quiz_score`, `completion_rate`, and `reward`. |


## 🧩 Purpose
The dataset is intended for reproducibility, benchmarking, and testing recommender system models that integrate semantic, behavioral, and IoT features.

## ⚖️ License
Distributed under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.  
You are free to share and adapt the dataset, provided appropriate credit is given.
