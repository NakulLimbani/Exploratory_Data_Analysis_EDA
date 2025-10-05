# 📊 Exploratory Data Analysis (EDA) Collection

Welcome to **Exploratory_Data_Analysis_EDA** — a collection of hands-on Exploratory Data Analysis (EDA) projects.  
Each project explores a different dataset, focusing on data cleaning, visualization, and insight generation.

---

## 🎯 Purpose

This repository serves as a central space for all my EDA work.  
Instead of maintaining multiple repositories for each dataset, this structure keeps everything organized and easy to expand in the future.

---

## 📁 Repository Structure
```
Exploratory_Data_Analysis_EDA/
├─ README.md # Overview of the whole repo (you’re here)
├─ .gitignore # Ignore raw data, checkpoints, etc.
└─ projects/
├─ iris/ # EDA on the Iris dataset 🌸
├─ titanic/ # (future) Titanic dataset EDA 🚢
└─ ... # Add future EDA projects here
```

Each dataset has:
- its own folder under `projects/`
- a dedicated `README.md`
- Jupyter notebooks and supporting scripts
- (optional) data and reports directories

---

## 🚀 How to Use

### 1. Clone the repository
```
git clone https://github.com/NakulLimbani/Exploratory_Data_Analysis_EDA.git
cd Exploratory_Data_Analysis_EDA
```
2. Choose a project
Navigate to a dataset folder, for example:
```
cd projects/iris
```
4. Run the analysis
Open the notebook(s) inside and execute all cells to reproduce the analysis.
```
jupyter lab
```
🔍 Current & Upcoming Projects
Project	Status	Description
Iris	✅ Complete	Statistical exploration and visualizations of the classic Iris dataset.
Titanic	🚧 Planned	Passenger survival analysis and feature exploration.
More coming soon...	🧩	Additional datasets will be added over time.

🛠️ Tech Stack
- Python
- Jupyter Notebook / JupyterLab / Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn

🧭 How to Add a New EDA Project
Create a new folder under projects/, for example:
```
mkdir projects/your_dataset_name
```
Inside it, add:
```
your_dataset_name/
├─ README.md
├─ notebooks/
│  ├─ 01_overview.ipynb
│  └─ 02_analysis.ipynb
├─ data/
│  ├─ raw/
│  └─ processed/
└─ reports/  # optional
```
Update this main README to include your new project.

---

💡 Vision
“Exploration is the first step towards understanding.”
This repository is built for curiosity — exploring data, discovering insights, and building a strong foundation in data analysis.

---

🪪 Author
Nakul Limbani

---

📜 License
This project is open-source under the MIT License.
Datasets used belong to their respective original sources (UCI, Kaggle, etc.).
