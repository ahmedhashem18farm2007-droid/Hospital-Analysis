# Hospital-Analysis
🏥 Hospital Analytics Dashboard
An interactive Hospital Analytics dashboard built with Microsoft Power BI to explore hospital visits, patient demographics, doctors, departments, treatments, and treatment costs.

📊 Project Overview
This project uses hospital-related data to help explore operational and financial patterns, including patient visits, treatment costs, and insurance coverage. The dashboard is provided as a Power BI .pbix file, with the source dataset available in Excel format.

🗂️ Dataset
The Excel workbook contains five tables:
Table	Rows	Description

Patients	15,000	Patient details such as gender, age, city, and age group
Doctors	500	Doctor names, specialties, and department IDs
Departments	10	Hospital department names
Treatments	50	Treatment names and base costs
Visits	100,000	Visit records, diagnoses, dates, treatment costs, and insurance coverage


Main fields
- Patients: PatientID, Gender, Age, City, Age Group
- Doctors: DoctorID, Specialty, DepartmentID
- Departments: DepartmentID, DepartmentName
- Treatments: TreatmentID, TreatmentName, BaseCost
- Visits: VisitID, PatientID, DoctorID, TreatmentID, VisitDate, Diagnosis, TreatmentCost, InsuranceCovered
- 
🛠️ Tools Used
- Microsoft Power BI — dashboard development and data visualization
- Microsoft Excel — dataset storage and organization
- 
🔍 Suggested Analysis Areas
The dataset supports analysis of:
- Patient demographics by age group, gender, and city
- Visit volume and diagnosis patterns
- Treatment costs and base-cost comparisons
- Insurance coverage across visits
- Doctor specialties and department information
- Changes in visits and costs over time
  
These are potential analysis areas based on the available data fields; the exact visuals and KPIs depend on the report pages in the Power BI file.

🚀 How to Open the Project
1. Download or clone this repository.
2. Open Hospital analysis.pbix using Microsoft Power BI Desktop.
3. If Power BI asks for a data source, update it to the location of Hospital_Analytics_Pro_100K(0)(1).xlsx.
4. Refresh the data if needed.
   
📁 Repository Files
- Hospital analysis.pbix — Power BI report
- Hospital_Analytics_Pro_100K(0)(1).xlsx — Excel dataset
  
💡 Learning Goals
This project demonstrates practical work with a multi-table dataset and the process of building a business intelligence report for hospital data.

👤 Author
Ahmed Hashem

Data Science Student | Aspiring Data Analyst
If you find this project useful, feel free to ⭐ the repository.
