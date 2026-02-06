# Resume Analysis from HeadHunter (hh_project)

## Project Overview

This repository contains a **data analysis project** focused on processing, cleaning, and exploring a dataset of resumes collected from the HeadHunter job platform. The main goal is to extract useful insights about candidates’ education, experience, desired salary, location, and job preferences.

The analysis demonstrates **data cleaning, exploratory data analysis (EDA), visualization, and insights presentation** using Python and Pandas. :contentReference[oaicite:1]{index=1}

---

## Dataset

The dataset contains information from resumes, including:
- Candidate demographics (age, gender, location)
- Education level
- Work experience
- Desired salary
- Job preferences

You can download the raw dataset from:  
**https://drive.google.com/file/d/1jhRb4pokG9-WwTAcMm3hWl0Czv-WCpQ5/view?usp=sharing**

---

## Technologies & Libraries

This project uses:

- Python
- Pandas (data processing)
- Seaborn & Matplotlib (visualizations)
- Jupyter Notebook

All required dependencies are listed in `requirements.txt`.

---

## Key Insights

These are the main insights your analysis notebook explores:

- The dataset contains **44,744 rows**, with some missing values in key columns like work experience and current position. :contentReference[oaicite:2]{index=2}  
- Education breakdown shows that **most applicants have a higher education degree**. :contentReference[oaicite:3]{index=3}  
- Median work experience is around **100 months (≈8 years)**. :contentReference[oaicite:4]{index=4}  
- **Gender distribution** shows around 19% female applicants. :contentReference[oaicite:5]{index=5}  
- **Location distribution** indicates a large share of applicants from Moscow and Saint Petersburg. :contentReference[oaicite:6]{index=6}  

These findings can be useful for HR analytics, labour market studies, or shaping hiring strategies.

---

## How to Run This Project

To run this analysis locally:

1. **Clone the repository**
    ```bash
    git clone https://github.com/agness-anshukova/hh_project.git
    cd hh_project
    ```

2. **Create a virtual environment**
    ```bash
    python -m venv venv
    source venv/bin/activate   # MacOS / Linux
    # or
    venv\Scripts\activate      # Windows
    ```

3. **Install dependencies**
    ```bash
    pip install -r requirements.txt
    ```

4. **Open the Jupyter Notebook**
    ```bash
    jupyter notebook
    ```

5. Run the notebook cells to explore the data cleaning steps, visualizations, and conclusions.


---

## Notes

- Some parts of the notebook may contain comments and labels in Russian — the key insights are described in English in this README.
- This project does not include a deployed dashboard, but the Jupyter Notebook provides clear visuals and findings.


