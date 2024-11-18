# **Closed Deals Performance Analysis**

## **Overview**
This project analyzes data on qualified leads and closed deals, focusing on identifying trends, evaluating deal outcomes, and providing actionable insights. By merging and exploring datasets, this project uncovers key patterns in lead qualification and deal closures, offering strategies to optimize sales pipelines.

---

## **Objectives**
1. Merge qualified leads and closed deals datasets for comprehensive analysis.
2. Explore key metrics, including lead quality and deal closure success rates.
3. Visualize patterns in deal performance using treemaps and other graphical tools.
4. Provide actionable recommendations to enhance deal closure rates.

---

## **Technologies Used**
### **Programming Languages**
- Python

### **Libraries**
- **Data Manipulation**: Pandas
- **Visualization**: Matplotlib, Squarify
- **Database Interaction**: SQLite3

---

## **Dataset**
The project uses two main datasets:
1. **Qualified Leads Dataset (`olist_marketing_qualified_leads_dataset.csv`)**:
   - Contains information on marketing-qualified leads.
2. **Closed Deals Dataset (`olist_closed_deals_dataset.csv`)**:
   - Contains details of closed deals, including the `won_date` and related metrics.

### **Merged Dataset**
- The datasets are merged on the common key `mql_id` to form a comprehensive dataset for analysis.

---

## **Project Workflow**
### **1. Data Preprocessing**
- Loaded and inspected the datasets to understand their structure.
- Merged datasets on `mql_id` to combine lead qualification and deal closure details.
- Identified and handled missing values (e.g., missing `won_date`).

### **2. Exploratory Data Analysis (EDA)**
- Explored the merged dataset to identify:
  - Distribution of deal statuses (e.g., won, lost).
  - Patterns in lead qualification and deal closures.
  - Key metrics like deal duration and revenue generated.

### **3. Visualization**
- Created insightful visualizations to highlight performance patterns:
  - **Treemaps** to showcase the distribution of deals across various categories.
  - **Bar Charts** to analyze deal closure trends.


