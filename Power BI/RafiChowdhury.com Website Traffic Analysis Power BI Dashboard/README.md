![image](https://github.com/user-attachments/assets/1b347baa-3a75-47ee-8f94-07ce351f8bf5)

---

## Website Traffic Data Visualization Project

### Overview
This project showcases the process I followed to take website traffic data from my personal website, rafichowdhury.com, using Google Analytics 4 (GA4). I exported the data to Google Sheets for cleaning, and then visualized the cleaned data using Power BI. The final visualizations provide insights into the website traffic patterns and user behavior.

### Step-by-Step Process

#### 1. Collecting Data from Google Analytics 4 (GA4)
1. **Access Google Analytics**: I logged into my Google Analytics account and navigated to the property associated with rafichowdhury.com.
2. **Select the Data Range**: I chose the date range for the data I wanted to analyze.
3. **Create a Custom Report**:
   - I went to the "Explore" section in GA4.
   - I created a new exploration report and included the necessary metrics and dimensions such as users, sessions, page views, bounce rate, etc.
4. **Export Data**:
   - After customizing my report, I clicked on the "Export" button.
   - I chose "Google Sheets" as the export format.

#### 2. Cleaning Data in Google Sheets
1. **Open the Exported Sheet**: I accessed the Google Sheets file where the GA4 data was exported.
2. **Organize the Data**: 
   - I ensured the data was structured in a tabular format.
   - I removed any unnecessary columns that were not relevant for the analysis.
3. **Handle Missing Values**: 
   - I identified and handled any missing or null values.
   - I used methods such as filling with mean/median values or simply removing rows with missing data, depending on the context.
4. **Standardize Data**: 
   - I standardized date formats and any other categorical data to ensure consistency.
   - I created additional columns if necessary, such as converting timestamps to a readable date format.
5. **Filter Data**:
   - I applied filters to focus on specific metrics or dimensions if needed.
   - For example, I filtered out bot traffic or irrelevant user data.

#### 3. Importing Data to Power BI
1. **Open Power BI Desktop**: I launched the Power BI Desktop application.
2. **Get Data**:
   - I clicked on "Get Data" and selected "Google Sheets".
   - I authenticated my Google account and navigated to the Google Sheets file containing the cleaned data.
3. **Load Data**:
   - I selected the relevant sheets and loaded the data into Power BI.
   - I performed any additional data transformations if required using the Power Query Editor.

#### 4. Creating Visualizations in Power BI
1. **Data Model**:
   - I created relationships between different tables if there were multiple data sources.
   - I ensured the data model was correctly set up for accurate analysis.
2. **Create Visuals**:
   - I used various visualizations such as bar charts, line charts, pie charts, and tables to represent the data.
   - I customized each visualization with appropriate labels, titles, and legends.
3. **Dashboard Design**:
   - I arranged the visualizations on a dashboard layout.
   - I used slicers and filters to enable interactive analysis.
   - I ensured the dashboard was user-friendly and visually appealing.
4. **Publish to Power BI Service**:
   - I saved my Power BI report and published it to the Power BI Service.
   - I logged in to my Power BI account and uploaded the report.

#### 5. Sharing the Dashboard
1. **Generate Sharable Link**:
   - After publishing, I went to the Power BI Service.
   - I opened my report and generated a sharable link.
   - I used the link provided to share the dashboard with hiring managers or other stakeholders.
2. **Embed Code**:
   - If I needed to embed the dashboard on a website, I used the embed code provided by Power BI.
   - Example embed code: 
     ```html
     <iframe title="dashboard" width="600" height="373.5" src="https://app.powerbi.com/view?r=eyJrIjoiZjRmNWFmYjAtNmRkYi00YjMwLTljMTQtY2NlMmViZDI4NTU2IiwidCI6ImQwNjlkMjgzLWJmMzQtNDc3My04N2Y2LWFkZWI4ZTE3ZGJmNSIsImMiOjN9" frameborder="0" allowFullScreen="true"></iframe>
     ```

### Final Dashboard
You can view the final dashboard [here](https://app.powerbi.com/view?r=eyJrIjoiZjRmNWFmYjAtNmRkYi00YjMwLTljMTQtY2NlMmViZDI4NTU2IiwidCI6ImQwNjlkMjgzLWJmMzQtNDc3My04N2Y2LWFkZWI4ZTE3ZGJmNSIsImMiOjN9).

### Conclusion
This project demonstrates the end-to-end process of data collection, cleaning, and visualization using GA4, Google Sheets, and Power BI. It provides a comprehensive view of the website traffic data and insightful visualizations that can be used to make informed decisions.

---
