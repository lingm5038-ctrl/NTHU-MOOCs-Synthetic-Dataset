# NTHU MOOCs – Dataset (Full, RL-Ready)

This repository provides a dataset designed to reflect large-scale MOOC learning environments,  
covering user–course interactions, behavioral metrics, and reinforcement learning–ready reward structures.

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
This dataset is provided for reproducibility, benchmarking, and evaluation of intelligent recommendation models  
that incorporate semantic, behavioral, and IoT-contextual information in MOOC environments.

## ⚖️ License
Distributed under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.  
You are free to share and adapt the dataset, provided appropriate credit is given.
