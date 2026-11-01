# AP-Education-PowerBI-Dashboard-2020-2026
Advanced Andhra Pradesh Degree and B.Tech College Analytics Dashboard (2020–2026) using Python, Streamlit, Plotly and Power BI-ready synthetic datasets. Includes year-wise, section-wise, branch-wise and gender-wise visualizations.
# AP Education Power BI & Streamlit Dashboard (2020–2026)

## Project Overview

An interactive Andhra Pradesh Degree and B.Tech College Analytics Dashboard built using Python, Streamlit, Pandas and Plotly.

### Features
- Academic-year analysis from 2020 to 2026
- Degree and B.Tech college comparisons
- Branch-wise and section-wise student analytics
- Separate male and female student statistics
- Interactive bar graphs and pie charts
- Power BI-style visualizations
- Downloadable CSV and Excel datasets

## Installation Guide (Windows)

### 1. Prerequisites

Install:
- Python 3.11 or later
- Git for Windows
- VS Code (optional)

### 2. Clone the GitHub repository

Open Command Prompt and run:

```cmd
cd %USERPROFILE%\Downloads
git clone https://github.com/jasahwang3387-byte/AP-Education-PowerBI-Dashboard-2020-2026.git
cd AP-Education-PowerBI-Dashboard-2020-2026
```

The clone command works after the repository is created and the project files are uploaded.

### 3. Verify the project files

```cmd
dir
```

Confirm that `app.py` and `requirements.txt` are present. If they are inside a subfolder, open that subfolder using `cd`.

### 4. Create a virtual environment

```cmd
py -m venv .venv
.venv\Scripts\activate
```

### 5. Install dependencies

```cmd
python -m pip install -r requirements.txt
```

### 6. Run the Streamlit dashboard

```cmd
python -m streamlit run app.py
```

### 7. Open the dashboard

Visit:

http://localhost:8501

### 8. Stop the dashboard

Press `Ctrl+C` in Command Prompt.

## Troubleshooting

**Error: requirements.txt not found**

Run `dir` to locate the requirements file and navigate into the correct folder.

**Error: app.py not found**

Use:

```cmd
dir /s /b app.py
```

Navigate into the folder containing `app.py`.

**Error: No module named streamlit**

Run:

```cmd
python -m pip install streamlit
```

## Dataset Notice

All student enrollment figures are synthetic demonstration data for educational and visualization purposes. They do not represent verified official college enrollment statistics.

## Technologies

Python | Streamlit | Pandas | Plotly | Excel | CSV | Power BI-ready Data
