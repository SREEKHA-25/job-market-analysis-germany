# 📊 Job Market Analysis – Germany

This project explores the current job market in Germany using real job posting data. The goal is to analyze job trends, top hiring countries and companies, popular job titles, and work formats using **Python**, **SQL**, and **Excel**.

## 📁 Project Structure

- `python_analysis.ipynb` – Python-based data cleaning and visualization
- `sql_analysis.ipynb` – SQL-based queries for job trend insights
- `job_data.db` – SQLite database created from the dataset
- `README.md` – Project overview and insights
- `charts/` – Folder containing exported visualizations 

## 🔍 Data Overview

- **Source**: Scraped job posting dataset
- **Fields**: Job title, location, category, seniority, salary, contract type, company, etc.
- **Time Period**: Last seen dates vary between April 2024

🔧 Tools Used

- Python (Pandas, Matplotlib, Seaborn)
- SQLite (via `sqlite3`)
- Jupyter Notebook
- Excel (Pivot tables and charts)
- Git & GitHub

## 📈 Key Insights

### A. Top Countries by Job Listings
Germany, France, and Spain dominate the listings across Europe.

### B. Most Common Job Titles
Internships and entry-level roles like:
- Working Student
- Intern (m/f/d)
- Sales Analyst
- Software Engineer

### C. Work Type Trends
- High number of **remote** and **internship** roles
- Most jobs are **closed** (status field)

### D. Top Companies Hiring
Companies like **Bosch**, **ZF**, and **Heraeus** had multiple listings.

## 📦 How to Use

1. Clone the repository
2. Open `python_analysis.ipynb` or `sql_analysis.ipynb` in Jupyter
3. Run the cells and explore insights
4. The SQLite database file `job_data.db` was used for internal analysis and is not included in this repository.
   However, you can recreate it easily using the provided SQL or Python code.

## ✅ Project Status

- [x] Data cleaned and encoded
- [x] Exploratory analysis using Python
- [x] SQLite database created
- [x] SQL queries executed and visualized
- [x] Project uploaded to GitHub

## 📌 Next Steps

- Add more time-based trends (e.g., jobs by month)
- Deep dive into salaries (if available)
- Connect to a live job API for real-time tracking

## 👤 Author

**Sreekha**  
[GitHub Profile](https://github.com/SREEKHA-25)  
LinkedIn:   www.linkedin.com/in/sreekham2000

## 📝 License

This project is for educational purposes. Feel free to fork and build upon it.

