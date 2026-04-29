# Task-Questions Data Analysis

[![Python](https://img.shields.io/badge/python-3.8%2B-blue)](https://www.python.org/) [![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)](https://jupyter.org/) [![MIT License](https://img.shields.io/badge/license-MIT-green)](LICENSE)

A curated set of practical data analysis exercises implemented in a single Jupyter Notebook (`Task-Questions.ipynb`). Each “task” addresses a real-world question—ranging from revenue aggregation to date/time cleanup—using Python, Pandas, NumPy, and SQL-style logic.

---  
                                
## 📖 Table of Contents                        

1. [About](#about)  
2. [Features & Tasks](#features--tasks)  
3. [Visual Preview](#visual-preview)  
4. [Project Structure](#project-structure)  
5. [Getting Started](#getting-started)  
6. [Usage](#usage)  
7. [Notebook Walk-through](#notebook-walk-through)  
8. [Dependencies](#dependencies)  
9. [Contributing](#contributing)  
10. [Authors & Acknowledgments](#authors--acknowledgments)  
11. [License](#license)  

---

## 📌 About

This repository collects a sequence of data-analysis “mini-projects” in a single Jupyter Notebook. Designed for learners and interview prep, it demonstrates how to:

- Clean and transform raw data  
- Perform group-by aggregations and multi-level summaries  
- Handle missing or invalid entries  
- Convert and manipulate dates/times  
- Apply feature-engineering techniques  

---

## ✨ Features & Tasks

Within `Task-Questions.ipynb` you’ll find solutions for:

1. **Day-of-Week Aggregation**  
2. **Customer Revenue Analysis**  
3. **Null-Value Handling**  
4. **Datetime Conversion**  
5. **Category-Level Summaries**  
6. **Advanced Filtering**

---

## 🖼️ Visual Preview

<div align="center">
  <!-- Replace with actual screenshots in /assets or /images -->
  <img src="assets/day_of_week_chart.png" alt="Day-of-Week Revenue Chart" width="300" />  
  <img src="assets/customer_revenue_table.png" alt="Customer Revenue Table" width="300" />
</div>

> **Tip:** Place your images in an `/assets` or `/images` folder and update the paths above.

---

## 🗂 Project Structure

.
├── README.md
├── Task-Questions.ipynb
├── assets/ # screenshots and visuals
│ ├── day_of_week_chart.png
│ └── customer_revenue_table.png
└── data/
└── (input CSVs, if any)

yaml
Copy
Edit

---

## 🛠 Getting Started

1. **Clone the repo**  
   ```bash
   git clone https://github.com/<your-username>/<your-repo-name>.git
   cd <your-repo-name>
(Optional) Virtual environment

bash
Copy
Edit
python3 -m venv venv
source venv/bin/activate      # macOS/Linux
venv\Scripts\activate         # Windows
Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
▶️ Usage
bash
Copy
Edit
jupyter notebook Task-Questions.ipynb
Run each cell to reproduce analyses and view visual outputs.

📝 Notebook Walk-through
🔹 Task 1: Day-of-Week Revenue & Counts

🔹 Task 2: Customer Total Spend

🔹 Task 3: Null-Value Cleanup

🔹 Task 4: DateTime Parsing

🔹 Task 5: Category Summaries

🔹 Task 6: Advanced Filtering

📦 Dependencies
pandas

numpy

jupyter

🤝 Contributing
Fork →

Branch: git checkout -b feature/your-idea →

Commit & push →

Open PR

👤 Author
Laxman B Khedkar

🔗 LinkedIn

📁 Portfolio

✉️ khedkarlaxman823@gmail.com

📄 License
MIT License. See LICENSE.
