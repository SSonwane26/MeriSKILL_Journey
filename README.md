# MeriSKILL_Journey
Story of my journey in MeriSKILL as Data Analyst, complete information of my Projects and my Final Presentations.

Good Morning, I am Saurabh. Today, I'm here to provide detailed information about my journey as a data analyst intern at MeriSKILL.

### About Me
First, let me introduce myself. My name is Saurabh Sonwane. I hold a degree in mechanical engineering and have been working as a Graduate Engineer Trainee (GET) in a multinational corporation. During my tenure there, my curiosity was piqued by the world of data sciences and analytics. I embarked on a journey to learn various analysis techniques, utilizing tools such as MS Excel and PowerBI. Additionally, I honed my programming skills in SQL and Python.

### About MeriSKILL
MeriSKILL is a platform that provides project-based internships to aspiring students and recent graduates. It aims to bridge the gap between students' theoretical knowledge and real-world experience. MeriSKILL offers internships in a variety of fields, including data analysis, business analysis, human resources, marketing, and digital marketing.

MeriSKILL is a valuable resource for students and recent graduates who are looking to gain real-world experience and enhance their skills. The internships offered by MeriSKILL are well-designed and provide participants with the opportunity to learn from experienced professionals and work on real-world projects.

## About Projects
### Project One
SALES ANALYSIS [DASHBOARD](https://github.com/SSonwane26/MeriSKILL_Journey/blob/main/Project1.png)

**About Dataset:**

The dataset consists of 11 columns, each column representing an attribute of purchase on a product -

- Order ID - A unique ID for each order placed on a product
- Product - Item that is purchased
- Quantity Ordered - Describes how many of that products are ordered
- Price Each - Price of a unit of that product
- Order Date - Date on which the order is placed
- Purchase Address - Address to where the order is shipped
- Month, Sales, City, Hour - Extra attributes formed from the above.

**Cleaninig and Preprocessing the Data:**

For this project, we performed data analysis using Excel, utilizing Power Query. Here are the steps we followed:

1. Data Loading: We loaded the data using Power Query, which is a data transformation tool in Excel.
   
1. Column Headers: We promoted headers to ensure the data columns were appropriately labeled.
   
1. Column Selection: Unwanted columns were removed from the dataset to streamline the analysis.
   
1. New Columns: We inserted additional columns into the dataset, enhancing its usability:
   - Week of Year: A new column was created using the 'Order Date' column to represent the week of the year for each order.
   - City: Another new column was added, extracting the city information from the 'Purchase Address' column.
   - Sales: We introduced a 'Sales' column by combining data from the 'Quantity' and 'Price' columns to calculate the total sales for each order.

**Creating Dashboard:**

After preprocessing the data, the sales data was loaded into a Pivot Table, and various Key Performance Indicators (KPIs) and charts were created. Here are the steps and components:

1. Pivot Table: A Pivot Table was generated using the sales data.

1. Charts , Graphs and Key Performance Indicators (KPIs):
   - Revenue: Calculated the total revenue from the sales data.
   - Total Orders: Determined the count of total orders.
   - Total Products: Counted the total number of unique products.
   - Monthly Sales: Created a column chart to visualize sales on a monthly basis.
   - Weekly Sales: Generated an area chart to visualize sales on a weekly basis.
   - Regionwise Sales: Presented region-wise sales using a bar chart.
   - Top Products by Sales: Displayed the top products by sales using another bar chart.

1. Slicers:
   - Region Slicer: Implemented a slicer to filter data by region.
   - Month Slicer: Included a slicer to filter data by month.

These steps and components help to analyze and visualize the sales data effectively.

**Insights:**

Here are the key insights from the data analysis:

1. Revenue: The total revenue is $34.49 million.

1. Total Orders: There are a total of 185,950 orders.

1. Total Unique Products: There are 19 unique products in the dataset.

1. Most Sales Months: The months of October, November, and December have the highest sales, with Quarter Four being a high sales quarter, likely due to festivals and vacation seasons.

1. Weekly Sales: Weeks 39 to 53 of the year show higher sales.

1. Regional Revenue: San Francisco contributes the most revenue, followed by Los Angeles (LA) and New York (NY).

1. Top Products by Sales: The top-selling products are MacBook, iPhone, and ThinkPad.

1. Slicer Example: Using slicers, you can see that in the Austin region, the total revenue in the month of April is $0.17 million.

These insights provide a clear understanding of the sales performance and trends in the dataset, allowing for informed decision-making and further analysis.

We have successfully completed our first project, gaining valuable insights into the workings of the sales industry and how past data can be used to predict future sales. Additionally, we have acquired the skill of designing attractive and informative dashboards.

### Project Two
After completing Project 1, our next step is Project 2, focusing on diabetes analysis.

DIABETES ANALYSIS [DASHBOARD](https://app.powerbi.com/view?r=eyJrIjoiMTA4NGExZGEtZGYxNS00Njg3LTg1YzYtY2UyODFlYzk4YzQ3IiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9)

**About Dataset:**

This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective is to predict based on diagnostic measurements whether a patient has diabetes. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage.
- Pregnancies: Number of times pregnant
- Glucose: Plasma glucose concentration a 2 hours in an oral glucose tolerance test
- BloodPressure: Diastolic blood pressure (mm Hg)
- SkinThickness: Triceps skin fold thickness (mm)
- Insulin: 2-Hour serum insulin (mu U/ml)
- BMI: Body mass index (weight in kg/(height in m)^2)
- DiabetesPedigreeFunction: Diabetes pedigree function
- Age: Age (years)
- Outcome: Class variable (0 or 1)

**Cleaninig and Preprocessing the Data:**

For this project, we performed data analysis using Power BI, utilizing Visualization Techniques. Here's what we did:

1. Data Loading: We loaded the data using Power Query, which is a data transformation tool in Power BI.

1. Column Headers: We promoted headers to ensure the data columns were appropriately labeled.

1. Column Selection: Unwanted columns were removed from the dataset to streamline the analysis.

1. Column Additions: We added new columns based on specific conditions:

   a. Weightgroup using BMI column.
      - <18.5 : UnderWeight, 18.5 to 34.9 : NormalWeight, 35 to 29.9 : OverWeight, >30 : Obesity
   
   b. BPlevel using blood pressure column.
      - <60 : Low, 60 t0 80 : Normal, >80 : High
   
   c. Glucoselevel using glucose column.
      - <80 : Low, 80 t0 180 : Normal, >180 : High
    
   d. Agegroup using age column.
      - <30 : YounAdult, 31 to 45 : MiddleAgeAdult, >45 : OldAgeAdult

**Creating Dashboard:**

Here's the data visualization plan for our HR Attrition Analysis project, broken down into key points:

1. Key Performance Indicators (KPIs):
   - Total Patients
   - Average Number of Pregnancies
   - Average Skin Thickness
   - Average Insulin

2. Visualization Types:
   - Clustered Columns Chart: To show diabetes status by Age Group, using the number of patients, age group, and 'Diabetic' (yes or no) as legend.
   - Clustered Columns Chart: To visualize diabetes status by Weight Group, with the number of patients, weight group, and 'Diabetic' (yes or no) as legend.
   - Clustered Columns Chart: To illustrate diabetes status by Glucose Level, including the number of patients, glucose level (low, high, normal), and 'Diabetic' (yes or no) as legend.
   - Clustered Columns Chart: For depicting diabetes status by BP Level, using the number of patients, BP Level (low, high, normal), and 'Diabetic' (yes or no) as legend.
   - Area Chart: To represent the relationship between the number of pregnancies and diabetes status, utilizing 'Pregnancies,' 'Number of Patients,' and 'Diabetic' (yes or no) as legend.
   - Pie Chart: To display the proportion of patients with diabetes, with the 'Diabetic' (yes or no) as legend.

3. Slicers:
   - Slicers for filtering by Diabetic status (yes or no).
   - Slicers for filtering by Age Group (middle, old, young).

These visualizations will provide valuable insights for our HR Attrition Analysis.

**Insights:**

Here are the key insights from our HR Attrition Analysis project:

1. Total Patients: There are a total of 768 patients in our dataset.

1. Average Number of Pregnancies: On average, patients have around 4 pregnancies.

1. Average Skin Thickness: The average skin thickness among patients is 21mm.

1. Average Insulin: The average insulin level is approximately 80mu U/ml.

1. Diabetic Chances:
   - Middle Age: Patients in the middle-age category have a 52% chance of being diabetic.
   - Obesity: About 46% of patients with obesity are at risk of diabetes.
   - High Blood Pressure: High blood pressure is associated with a 47% risk of diabetes.
   - Increased Pregnancies: There is an increased risk of diabetes with an increase in the number of pregnancies.

These insights provide a valuable understanding of factors associated with diabetes in our dataset.

With these insights, we've successfully completed Project 2. Now, it's time to move on to our final project, Project 3

### Project Three
Now, onto our third and final project, focusing on HR Attrition Analysis.

HR ATTRITION [DASHBOARD](https://app.powerbi.com/view?r=eyJrIjoiODNiOWQ3ZTUtMDU5OS00MTMxLWE0ODUtYTQ1NTU1YmFmOGE0IiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9)

**About Dataset:**

HR Analytics helps us with interpreting organizational data. It finds the people-related trends in the data and allows the HR Department to take the appropriate steps to keep the organization running smoothly and profitably. Attrition in a corporate setup is one of the complex challenges that the people managers and the HRs personnel have to deal with.
- Plot a correlation map for all numeric variables
- Overtime
- Marital Status
- Job Role
- Gender
- Education Field
- Department
- Business Travel
- Relation between Overtime and Age
- Total Working Years
- Education Level
- Number of Companies Worked
- Distance from Home

**Cleaninig and Preprocessing the Data:**

Certainly, here's the data preprocessing process for Project 3, "HR Attrition," broken down into clear steps:

1. Data Loading: We initiated the analysis by loading the data into Power Query.

2. Header Promotion: Ensured proper column headers by promoting them.

3. Data Cleaning: Removed unnecessary rows and columns to streamline the dataset.

4. Column Renaming: Renamed columns for clarity and consistency.

5. Conditional Columns: Introduced new columns based on conditions,
   - Age Group: Categorized ages into groups (18-24, 25-34, 35-44, 45-54) using the 'Age' column.
   - Distance Status: Defined distance categories (Nearby, Far, Very Far) based on the 'Distance from Home' column.
   - Working Years Group: Grouped years of service (0-10, 11-20, 21-30, 31 & above) using the 'Total Working Years' column.
     
   - Education: 1 'Below College', 2 'College', 3 'Bachelor', 4 'Master', 5 'Doctor'
   - EnvironmentSatisfaction: 1 'Low', 2 'Medium', 3 'High', 4 'Very High'
   - JobInvolvement: 1 'Low', 2 'Medium', 3 'High', 4 'Very High'
   - RelationshipSatisfaction: 1 'Low', 2 'Medium', 3 'High', 4 'Very High'
   - WorkLifeBalance: 1 'Bad', 2 'Good', 3 'Better', 4 'Best'

This comprehensive data preprocessing lays the foundation for our HR Attrition analysis and dashboard creation.

**Creating Dashboard:**

Key Performance Indicators (KPIs):
- Total Employees
- Active Employees
- Attrition Rate
- Average Age
- Attrition by Performance

Bar Charts:
- Utilized 'Education Field' and 'Number of Employees' columns to create a bar chart.
- Employed a 100% stacked bar chart with 'Gender,' 'Number of Employees,' and 'Gender' as legends.
- Constructed a column chart featuring 'Age Group,' 'Number of Employees,' and 'Gender' as legends.

Donut Charts: Developed three donut charts,
  - First chart based on 'Business Travel' and 'Number of Employees' columns.
  - Second chart using 'Distance Status' and 'Number of Employees' columns.
  - Third chart representing 'Department' and 'Number of Employees' columns.

Conditional Table: Employed a conditional table with 'Job Role' and 'Attrition' columns to present relevant data.

Slicers: Implemented slicers for 'Gender' and 'Department' to provide interactive filtering options.

This well-rounded dashboard will provide valuable insights for our HR Attrition analysis, allowing for informed decision-making and exploration of key HR metrics.

**Insights:**

Here are the key insights from our HR Attrition Analysis:

1. Total Employees: Our dataset comprises a total of 1,470 employees.

2. Attrition Rate: The overall attrition rate stands at 16%.

3. Gender-Based Attrition:
   - Male Attrition Rate: 17%
   - Female Attrition Rate: 15%

4. Department Attrition Rates:
   - HR Department: 5% attrition rate
   - Sales Department: 39% attrition rate
   - R&D Department: 56% attrition rate

5. Average Age: The average age of employees in the dataset is 37 years.

Additional Insight (from me):
- These attrition rates shed light on the need to explore and address factors contributing to attrition, particularly in the Sales and R&D departments.

These insights provide a comprehensive view of attrition within the organization, highlighting areas for further analysis and potential interventions.

## Acknowlegement
We've successfully concluded all three projects. I want to extend my gratitude to MeriSKILL and Team for providing me with valuable experiences and knowledge through these projects. Remember, we can always learn from learning, and I'm open to receiving feedback. Let's keep growing and improving together!

> [!NOTE]
> The steps and projects provided are based on my personal experiences during the internship period and may evolve or change in the future. Internship programs can vary, and the specific steps and tasks involved may be subject to modification over time.
