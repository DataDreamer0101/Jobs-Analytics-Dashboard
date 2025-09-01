## 📊 Project Overview
- **Dataset Source:** [Remotive.io Jobs API](https://remotive.com/)  
- **Goal:**  
  - Scrape job postings with Python  
  - Clean and preprocess dataset (handling duplicates, missing values, salary parsing)  
  - Explore **job categories, hiring companies, job types, and locations**  
  - Build a **Power BI Dashboard** for interactive analysis  
- **Deliverables:**  
  - Clean dataset (`jobs_cleaned.csv`)  
  - Jupyter Notebook (`job_scraping.ipynb`)  
  - Power BI Dashboard (`Remote_Jobs_Dashboard.pbix`)  
  - Conda environment (`environment.yml`)  

---

## 🛠 Tools & Libraries
- **Python:** pandas, requests, matplotlib, seaborn  
- **Environment:** Conda (`job_scraping`)  
- **Visualization:** Power BI (interactive dashboard)  
- **Exported Deliverables:** dataset (`.csv`), notebook (`.ipynb`), dashboard (`.pbix`), env (`.yml`)  

---

## 🔑 Key Steps
1. **Web Scraping**  
   - Collected job postings using Remotive API (sample of ~1400 jobs).  

2. **Data Cleaning**  
   - Removed duplicates, handled missing values  
   - Standardized categorical fields (`Job Category`, `Job Type`, `Location`)  
   - Parsed salary ranges into numeric fields  

3. **Exploratory Data Analysis (EDA)**  
   - Top Job Categories  
   - Top Hiring Companies  
   - Job Type Distribution  
   - Location-based insights  
   - Salary (cleaned ranges)  

4. **Dashboard in Power BI**  
   - 📌 **Visuals Used:**  
     - Bar Chart → Top Job Categories  
     - Bar Chart → Top Hiring Companies  
     - Pie Chart → Job Type Distribution  
     - Map → Job Locations  
     - Histogram → Salary Distribution (Bins)  

---

## 📌 Key Insights
1. **Software Development** dominates as the top remote job category.  
2. Most roles are **Full-Time** (~85%), followed by Contract and Part-Time.  
3. Remote hiring is concentrated in **USA, UK, and Europe**, but growing globally.  
4. Certain companies (e.g., NearSure, Mozilla) consistently post remote opportunities.  
5. Salary ranges vary widely, with most clustered in mid-level ranges.  

---

## ⚙️ Setup Instructions  

### 1️⃣ Clone Repository
```bash
git clone https://github.com/your-username/job_scraping_project.git
cd job_scraping_project
2️⃣ Create the Conda Environment
bash
Copy code
conda env create -f environment.yml
conda activate job_scraping
3️⃣ Run Jupyter Notebook
bash
Copy code
jupyter notebook job_scraping.ipynb
4️⃣ Open Power BI Dashboard
Open Remote_Jobs_Dashboard.pbix in Power BI Desktop

Connect it with the jobs_cleaned.csv dataset

