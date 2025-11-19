# AI Jobs Data Analysis

### **Project Overview**
The analysis investigates the potential impact of Artificial Intelligence on the job market by 2030. Using a dataset of 3,000 entries, the project explores hiring trends, salary distributions, experience levels, and the exposure of various roles to AI technologies.

### **Key Data & Structure**
* **Dataset:** `Ai jobs dataset.csv` containing 3,000 rows and 18 columns.
* **Key Columns:** `Job_Title`, `Salary`, `Years_Experience`, `Education_Level`, `AI_Exposure_Index`, `Tech_Growth_Factor`, `Automation_Probability_2030`, `Risk_Category`, and various `Skill` columns.
* **Tools Used:** Python (`pandas` for data manipulation).

### **Analysis Highlights (Exploratory Data Analysis)**

**1. Job Distribution**
* The dataset includes a wide variety of roles ranging from technical (AI Engineer, Software Engineer) to non-technical (Teacher, Chef, Truck Driver).
* **Software Engineer** is the most frequent job title in the dataset (175 entries), followed by UX Researchers and Data Scientists.

**2. Salary Insights**
* The project calculated the average salary for each job title.
* **Highest Paid:** Graphic Designers, Lawyers, and Chefs top the list for average salaries (surpassing traditional tech roles in this specific synthetic dataset).
* **Lowest Paid:** Truck Drivers appear at the bottom of the average salary list.

**3. Experience Levels**
* **Mechanics** have the highest average years of experience (~16.2 years), followed by UX Researchers and Teachers.
* Technical roles like Data Scientists and Software Engineers average around 14 years of experience.

**4. Educational Impact**
* The analysis examines average salaries broken down by `Education_Level`.
* Visualizations indicate that **Bachelor's degree** holders have the highest average salary in this dataset, slightly edging out PhD and Master's holders.

**5. AI & Tech Metrics**
* **Tech Growth Factor:** The analysis identifies which roles are seeing the most technological growth.
* **AI Exposure:** It identifies the top 10 job profiles with the highest `AI_Exposure_Index`.
    * *Top exposed roles:* Automation Engineers, Service Technicians, and Project Managers.
* **Risk Category:** It analyzes the average risk category associated with tech growth.

### **Visualizations**
The notebook generates several bar charts to visually represent:
* Top 5 highest-paying job profiles.
* Top 3 job profiles by years of experience.
* Average salary by education level.
* Top 5 countries (labeled as Job Titles in the code context) with the highest Tech Growth Factor.
* Top 10 job profiles with the highest AI Exposure Index.

### **Conclusion**
This notebook serves as a foundational exploratory analysis to understand how different job roles—both blue-collar and white-collar—might compare in terms of compensation, experience requirements, and vulnerability to AI automation in the near future.
