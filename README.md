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

**Cleaninig and Modeling the Data:**

For this project, we performed data analysis using Excel, utilizing Power Query. Here are the steps we followed:

1. Data Loading: We loaded the data using Power Query, which is a data transformation tool in Excel.

2. Column Headers: We promoted headers to ensure the data columns were appropriately labeled.

3. Column Selection: Unwanted columns were removed from the dataset to streamline the analysis.

4. New Columns: We inserted additional columns into the dataset, enhancing its usability:

   a. Week of Year: A new column was created using the 'Order Date' column to represent the week of the year for each order.

   b. City: Another new column was added, extracting the city information from the 'Purchase Address' column.

   c. Sales: We introduced a 'Sales' column by combining data from the 'Quantity' and 'Price' columns to calculate the total sales for each order.

**Creating Dashboard:**

After preprocessing the data, the sales data was loaded into a Pivot Table, and various Key Performance Indicators (KPIs) and charts were created. Here are the steps and components:

1. Pivot Table: A Pivot Table was generated using the sales data.

2. Key Performance Indicators (KPIs):
   - Revenue: Calculated the total revenue from the sales data.
   - Total Orders: Determined the count of total orders.
   - Total Products: Counted the total number of unique products.
   - Monthly Sales: Created a column chart to visualize sales on a monthly basis.
   - Weekly Sales: Generated an area chart to visualize sales on a weekly basis.
   - Regionwise Sales: Presented region-wise sales using a bar chart.
   - Top Products by Sales: Displayed the top products by sales using another bar chart.

3. Slicers:
   - Region Slicer: Implemented a slicer to filter data by region.
   - Month Slicer: Included a slicer to filter data by month.

These steps and components help to analyze and visualize the sales data effectively.

**Insights:**

Here are the key insights from the data analysis:

1. Revenue: The total revenue is $34.49 million.

2. Total Orders: There are a total of 185,950 orders.

3. Total Unique Products: There are 19 unique products in the dataset.

4. Most Sales Months: The months of October, November, and December have the highest sales, with Quarter Four being a high sales quarter, likely due to festivals and vacation seasons.

5. Weekly Sales: Weeks 39 to 53 of the year show higher sales.

6. Regional Revenue: San Francisco contributes the most revenue, followed by Los Angeles (LA) and New York (NY).

7. Top Products by Sales: The top-selling products are MacBook, iPhone, and ThinkPad.

8. Slicer Example: Using slicers, you can see that in the Austin region, the total revenue in the month of April is $0.17 million.

These insights provide a clear understanding of the sales performance and trends in the dataset, allowing for informed decision-making and further analysis.

We have successfully completed our first project, gaining valuable insights into the workings of the sales industry and how past data can be used to predict future sales. Additionally, we have acquired the skill of designing attractive and informative dashboards.

### Project Two
DIABETES ANALYSIS [DASHBOARD](https://github.com/SSonwane26/MeriSKILL_Journey/blob/main/Project2.png)

**About Dataset:**

This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective is to predict based on diagnostic measurements whether a patient has diabetes. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage.

-bPregnancies: Number of times pregnant
- Glucose: Plasma glucose concentration a 2 hours in an oral glucose tolerance test
- BloodPressure: Diastolic blood pressure (mm Hg)
- SkinThickness: Triceps skin fold thickness (mm)
- Insulin: 2-Hour serum insulin (mu U/ml)
- BMI: Body mass index (weight in kg/(height in m)^2)
- DiabetesPedigreeFunction: Diabetes pedigree function
- Age: Age (years)
- Outcome: Class variable (0 or 1)

**Cleaninig and Modeling the Data:**

After completing Project 1, our next step is Project 2, focusing on diabetes analysis.

For this project, we performed data analysis using Power BI, utilizing Visualization Techniques. Here's what we did:

1. Data Loading: We loaded the data using Power Query, which is a data transformation tool in Power BI.

2. Column Headers: We promoted headers to ensure the data columns were appropriately labeled.

3. Column Selection: Unwanted columns were removed from the dataset to streamline the analysis.

4. Column Additions: We added new columns based on specific conditions:

   a. Weightgroup using BMI column.
      - <18.5 : UnderWeight, 18.5 to 34.9 : NormalWeight, 35 to 29.9 : OverWeight, >30 : Obesity
   
   b. BPlevel using blood pressure column.
      - <60 : Low, 60 t0 80 : Normal, >80 : High
   
   c. Glucoselevel using glucose column.
      - <80 : Low, 80 t0 180 : Normal, >180 : High
    
   d. Agegroup using age column.
      - <30 : YounAdult, 31 to 45 : MiddleAgeAdult, >45 : OldAgeAdult

**Creating Dashboard:**

### Project Three
HR ATTRITION [DASHBOARD](https://github.com/SSonwane26/MeriSKILL_Journey/blob/main/Project3.png)

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

Education
1 'Below College'
2 'College'
3 'Bachelor'
4 'Master'
5 'Doctor'

EnvironmentSatisfaction
1 'Low'
2 'Medium'
3 'High'
4 'Very High'

JobInvolvement
1 'Low'
2 'Medium'
3 'High'
4 'Very High'

JobSatisfaction
1 'Low'
2 'Medium'
3 'High'
4 'Very High'

PerformanceRating
1 'Low'
2 'Good'
3 'Excellent'
4 'Outstanding'

RelationshipSatisfaction
1 'Low'
2 'Medium'
3 'High'
4 'Very High'

WorkLifeBalance
1 'Bad'
2 'Good'
3 'Better'
4 'Best'

**Cleaninig and Modeling the Data:**

**Creating Dashboard:**

**Insights:**
