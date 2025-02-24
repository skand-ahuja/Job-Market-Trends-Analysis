# **📊 Job Market Trends Analysis**  
🚀 **Analyzing Data Science job market trends in India using web-scraped job listings**  

## **📌 Project Overview**  
This project aims to analyze **hiring trends, salary distributions, skill demand, and experience impact** for **Data Science roles in India**. Using **real-world job postings**, we extract valuable insights to help:  

✅ **Job Seekers** → Identify high-demand skills, top hiring companies, and best-paying roles.  
✅ **Employers** → Benchmark salary trends and hiring patterns.  
✅ **Researchers & Analysts** → Understand the evolving Data Science job market.  

---

## **📁 Project Structure**  
```bash
Job-Market-Trends-Analysis/
│── Assets/                     # Plots of analysis
│── Data/                     # Folder for raw & processed data
│   ├── synthetic_jobs.csv     # Synthetic dataset (if real-time scraping isn't used)
│   ├── cleaned_jobs.csv       # Cleaned dataset after preprocessing
│   ├── processed_jobs.csv     # Final dataset after feature engineering
│── Notebooks/                 # Jupyter notebooks for analysis
│   ├── EDA.ipynb              # Exploratory Data Analysis
│   ├── hypothesis_testing.ipynb # Hypothesis & A/B Testing
│   ├── feature_engineering.ipynb # Feature Engineering
│── src/                       # Source code folder
│   ├── scrape_timesjobs.py    # Web scraping script (if applicable)
│── Reports/                   # Reports & insights
│   ├── Job_Market_Trends_Report.pdf  # Final report
│── README.md                  # Project documentation
│── requirements.txt           # List of required Python packages
│── .gitignore                 # Files to ignore in GitHub
│── LICENSE                    # Open-source license (MIT recommended)
```

---

## **🛠 Technologies Used**  
✅ **Programming Language:** Python 🐍  
✅ **Libraries & Tools:**  
- Data manipulation → `pandas`, `numpy`   
- Data visualization → `matplotlib`, `seaborn`
- Statistical analysis → `scipy.stats`
- Feature engineering → `sklearn.preprocessing`
- Web scraping → `BeautifulSoup`, `requests`

---

## **📊 Data Analysis & Insights**  
### **1️⃣ Top Hiring Companies**  
📌 **Google, Infosys, and other tech giants** are the leading recruiters for Data Science roles.  

📊 **Figure:**
![Alt text](https://external-website.com/path/to/image.png)
![Top Hiring Companies](</Assets/1. Top Hiring Companies.png>)

---

### **2️⃣ Most In-Demand Skills**  
📌 The **most required skills** for Data Science jobs:  
✅ Python, SQL, Machine Learning  
✅ Data Wrangling, Pandas, NumPy  
✅ Power BI, Tableau, Deep Learning  

📊 **Figure:**  
![Most In-Demand Skills](</Assets/2. Most In-Demand Skills.png>)

---

### **3️⃣ Salary Trends**  
📌 **Salaries vary based on seniority level:**  
- **Junior Roles** → ₹1-3 LPA  
- **Mid-Level Roles** → ₹4-7 LPA  
- **Senior Roles** → ₹8+ LPA  

📊 **Figure:** 
![Salary Distribution](</Assets/3. Salary Distribution.png>)
![Salary Distribution by Seniority](</Assets/3. Salary Distribution by Seniority.png>)

---

### **4️⃣ Experience vs. Salary**  
📌 **Experience alone does not significantly impact salary**.  
📌 **Skills and industry demand have a greater influence** on pay.  

📊 **Figure:**  
![Experience vs. Salary](</Assets/4. Experience vs. Salary.png>)


---

### **5️⃣ Job Locations**  
📌 **Chennai, Delhi, and Mumbai** are the top cities for Data Science jobs.  
📌 **Bangalore has fewer job postings in this dataset, which may indicate niche hiring trends.**  

📊 **Figure:**
![Salary Distribution by Seniority](</Assets/5. Job Locations.png>)

---

## **📊 Hypothesis Testing & A/B Testing**  
| **Hypothesis** | **P-Value** | **Conclusion** |
|---------------|-----------|---------------|
| **Salary Differences by Location** | 0.018 | ✅ **Significant difference** |
| **Skill Demand (Python vs. SQL)** | 1.000 | ❌ **No difference in demand** |
| **Experience vs. Salary Correlation** | 0.968 | ❌ **No correlation** |
| **Data Scientist vs. ML Engineer Salaries** | 0.951 | ❌ **No significant difference** |

📌 **Key Takeaway:**  
✅ **Skills matter more than experience in salary growth.**  
✅ **Data Scientists and ML Engineers earn similar salaries.**  
✅ **Python & SQL are equally in demand.**  

📊 **[See Boxplots, Histograms, and Regression Plots → `/reports/`]**  

---

## **🚀 How to Run the Project**  
### **1️⃣ Clone the Repository**  
```bash
git clone https://github.com/skand-ahuja/Job-Market-Trends-Analysis.git
cd Job-Market-Trends-Analysis
```

### **2️⃣ Install Dependencies**  
```bash
pip install -r requirements.txt
```

### **3️⃣ Run the Jupyter Notebooks**  
```bash
jupyter notebook
```
- Open `EDA.ipynb` to explore the data.  
- Run `hypothesis_testing.ipynb` for statistical analysis.  
- Use `feature_engineering.ipynb` to check feature transformations.  

---

## **📝 Future Scope**  
✅ Extend analysis to **more job roles** (ML Engineer, AI Researcher, etc.).  
✅ Build a **Machine Learning model** to predict salaries.  
✅ Automate **real-time job scraping** for updated insights.  
✅ Deploy a **dashboard using Power BI/Tableau** for dynamic visualizations.  

---

## **📜 License**  
This project is licensed under the **MIT License** – feel free to use, modify, and share!  

---

### **✅ Ready to Explore Job Market Trends?**
If you found this project helpful, **give it a ⭐ on GitHub!** 🚀  

---