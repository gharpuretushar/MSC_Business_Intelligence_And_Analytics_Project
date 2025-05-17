# 💊 Business Intelligence & CRM Integration for PTU Pharmacy

A full-scale business analytics and CRM implementation project aimed at reviving the sales, operations, and customer engagement for **PTU Pharmacy**, a hospital-based pharmacy. This project utilizes **Power BI dashboards** and **Salesforce CRM** to enhance data-driven decision-making, optimize operations, and provide a competitive edge over rivals like **Best Pharma**.

---

## 📌 Project Overview

> PTU Pharmacy was facing operational decline due to poor inventory tracking, weak customer engagement, inefficient supplier performance, and strong competitor pressure. This project addresses these gaps using BI and CRM systems.

### Key Objectives:
- Increase pharmacy sales
- Improve customer retention
- Automate inventory and supplier insights
- Create loyalty-based customer journeys using Salesforce

---

## 🛠️ Tools & Technologies

- **Visualization**: Power BI (4 dashboards)
- **CRM Platform**: Salesforce (Custom CRM Objects & Reports)
- **Mock Data Generator**: [Mockaroo](https://mockaroo.com)
- **Collaboration**: Trello, Miro
- **Scripting**: SOQL (Salesforce), Power Query (Power BI)
- **DB Structure**: Custom ERD, CSV datasets

---

## 🗂️ Project Structure

| File/Folder | Description |
|-------------|-------------|
| `BIBA REPORT 2 (1).docx` | Final academic report with methodology, visualizations, dashboards, CRM flows, and outcomes. |
| `Reports.zip` | Includes all dashboards, CRM screenshots, and CSVs used in Power BI and Salesforce. |
| `dataset links.txt` | External dataset sources used for mock data design and testing. |

---

## 📊 Dashboards Overview

1. **PTU Sales Dashboard**
   - Product-wise sales, pricing distribution, customer trends
   - Highlights stockouts & limited working hours

2. **Best Pharma Dashboard**
   - Competitor pricing strategies, loyalty schemes, seasonal preparedness

3. **Supplier Comparison Dashboard**
   - Compares delivery efficiency & vendor performance (PTU vs Best Pharma)

4. **Hospital Visit Dashboard**
   - Maps hospital patient footfall to PTU pharmacy conversion

Each dashboard contains **interactive filters, KPIs, time trends**, and **category breakdowns**.

---

## 📦 Salesforce CRM Implementation

Objects Created:
- `Customer`: Loyalty points, personal details, contact validation
- `Order`: Sales linked with medicine, customer
- `Medicine`: Linked to `Supplier`, tracks stock and pricing
- `Supplier`: Contact and brand link
- `Driver`: Delivery management
- `CRM Queries`: Complaint and feedback tracking

Key Features:
- Lookup relationships for traceability
- Validation rules and Data Import Wizard usage
- Custom dashboards and tabular reports (e.g., PTU Orders Report)

---

## 🧬 Data Model

- **ERD**: Captures relations among `Sales`, `Inventory`, `Supplier`, `Customer`, `CRM`
- **Data Dictionary**: Defines columns, types, and use cases
- **Mock Data**: Inspired by Kaggle, GitHub datasets + extended with custom CRM fields

Sources:
- [Pharma Dataset 1 – Kaggle](https://www.kaggle.com/datasets/shuvokumarbasak2030/drug-pharma-new-dataset)
- [Pharma Dataset 2 – GitHub](https://github.com/mcallara/pharma-sales-data)
- [Supplier Dataset – Kaggle](https://www.kaggle.com/datasets/snowyowl22/pharmacy-dataset)
- [Pharma Power BI Repo – GitHub](https://github.com/sssingh/pharmaceutical-sales-analysis-powerbi)
- [Indian Medicines Dataset – Kaggle](https://www.kaggle.com/datasets/shudhanshusingh/az-medicine-dataset-of-india)

---

## 🔍 Key Findings

- **Low Customer Conversion**: ~70% of hospital patients are not PTU customers.
- **Pricing Gap**: PTU prices higher than Best Pharma; no loyalty offers.
- **Supplier Delays**: PTU’s vendors are fewer and slower than competitors’.
- **Low Operational Hours**: PTU closes at 7pm; sales drop vs 24/7 Best Pharma.

**CRM Benefits**:
- Accurate customer tracking and order management
- Loyalty program integration and complaint handling

---

## 💡 Future Scope

- Integrate **automated loyalty reminders** & **email campaigns**
- Add **driver dispatch tracking** into CRM
- Include **sentiment analysis** on feedback forms
- Predictive alerts for **seasonal medicine stock-ups**

---

## 👨‍💻 Team & Collaboration

- **Utkarsh Satpute** – Report writing, data modeling, planning
- **Tushar Gharpure** – Dashboard development in Power BI
- **Pintoo Baghel** – Salesforce CRM implementation

Tools Used:
- [Trello Project Board](https://trello.com/invite/b/67d9c07ea14e349e7120df95/ATTI54fd50572ac999eaa998e86700650544D011C5E6/ptu-in-house-pharmacy-bi-ba-project)
- [Miro Dashboard Planning](https://miro.com/app/board/uXjVIWNeoZk=/?share_link_id=222356666989)

---

## 📚 References

1. [Exploring BI in Healthcare – Future Computing & Informatics Journal, 2024](https://www.sciencedirect.com/science/article/pii/S111086652400001X)
2. [Pharma KPIs & Dashboards – Advances in Intelligent Systems, 2020](https://www.researchgate.net/publication/338349285)
3. [Journal of Economics, Management and Trade – CRM Use in Pharmacy, 2023](https://journaljemt.com/index.php/JEMT/article/view/1258)

---

## 📘 License

This is an academic project submitted to **National College of Ireland** under the MSc. in Data Analytics program. Not for commercial reuse.

---

## 🔖 Tags

`#PowerBI` `#SalesforceCRM` `#HealthcareBI` `#PharmacySales` `#ETL` `#InventoryTracking` `#LoyaltyProgram` `#CustomerEngagement` `#BIinPharma`