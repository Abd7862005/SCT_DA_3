# 📊 Task 3 – HR Employee Attrition Analysis Dashboard  

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?size=22&duration=3000&color=1F77B4&center=true&vCenter=true&width=700&lines=Data+Analyst+Intern+at+Skill+Craft+Technology;HR+Analytics+Dashboard+using+Power+BI;Interactive+Insights+Driven+Project" />
</p>

---

## 🏢 Internship Role
**Data Analyst Intern – Skill Craft Technology**

This project was completed as **Task 3** during my internship, focusing on analyzing employee attrition trends using Power BI.

---

## 🎯 Project Objective

To design and develop an interactive HR Analytics dashboard that:

- Identifies key drivers of employee attrition  
- Highlights high-risk departments  
- Analyzes salary, age, gender, and overtime impact  
- Supports data-driven HR decision-making  

---

## 🛠 Tech Stack

<p>
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
  <img src="https://img.shields.io/badge/DAX-0176D3?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Data%20Modeling-0A66C2?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/HR%20Analytics-FF6F00?style=for-the-badge"/>
</p>

---

## 📊 Key KPIs

- Total Employees  
- Attrition Count  
- Attrition Rate (%)  
- Average Income of Employees Who Left  

---

## 📈 Dashboard Features

- 🔘 Interactive button-style slicers  
- 📊 Department-wise attrition analysis  
- 📉 Salary slab impact visualization  
- 👥 Gender-based comparison  
- ⏳ Overtime vs Attrition insights  
- 🎨 Clean and professional layout  

---

## 🧠 DAX Measures

### Attrition Count
```DAX
Attrition Count =
CALCULATE(
    COUNTROWS(HR_Employee_Attrition),
    HR_Employee_Attrition[Attrition] = "Yes"
)
```

### Attrition Rate %
```DAX
Attrition Rate % =
DIVIDE(
    [Attrition Count],
    COUNTROWS(HR_Employee_Attrition)
)
```

---

## 🔍 Key Insights

- Higher attrition observed in specific departments  
- Lower salary slabs show increased turnover  
- Overtime correlates strongly with attrition  
- Younger employees demonstrate higher exit rates  

---

## 🚀 Business Impact

✔ Identifies high-risk employee segments  
✔ Helps improve retention strategies  
✔ Enables HR data-driven planning  
✔ Provides actionable workforce insights  

---

## 📌 Conclusion

Task 3 demonstrates practical industry-level skills in:

- Data Analysis  
- Dashboard Development  
- Business Intelligence  
- Insight Interpretation  

This project reflects hands-on experience gained as a **Data Analyst Intern at Skill Craft Technology**.

---

<p align="center">
⭐ If you found this project interesting, consider giving it a star!
</p>
