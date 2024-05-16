# Power-BI


<details>
 <summary> Get Started with Power BI </summary>
  
  # Introduction to Power BI

  * Microsoft Power BI is a complete reporting solution that offers data preparation, data visualization, distribution, and management through development tools and an online platform.
  * Use Power BI to create visually stunning, interactive reports to serve as the analytics and decision engine behind group projects, divisions, or entire organizations.
  * Power BI is an essential tool to data analysts and their organization; however, all data professionals benefit from understanding how Power BI works to explore and present data insights within organizations.

# There are three primary components to Power BI:

* Power BI Desktop (desktop application)
* Power BI service (online platform)
* Power BI Mobile (cross-platform mobile app)

* Power BI Desktop is the development tool available to data analysts and other report creators.
* While the Power BI service allows you to organize, manage, and distribute your reports and other Power BI items.
* Power BI Desktop is available to download for free either through the Windows store or directly online.

# The flow of Power BI is:

1. Connect to data with Power BI Desktop.
2. Transform and model data with Power BI Desktop.
3. Create visualizations and reports with Power BI Desktop.
4. Publish report to Power BI service.
5. Distribute and manage reports in the Power BI service.

* The Power BI service also allows you to create high-level dashboards that drill down to reports, and apps to easily group related reports to users in a simple format.

# Building blocks of Power BI

* The building blocks of Power BI are semantic models and visualizations.
* Create a semantic model and then use visuals to build a report. Let's explore these items in more detail and how they relate to the flow of Power BI.

# Create a semantic model

* A semantic model consists of all connected data, transformations, relationships, and calculations.
* To follow the flow of Power BI, you first connect to data, transform data, and create relationships and calculations to create a semantic model.
* First, connect to as many data sources you need.
* Then clean and transform the data to your needs. Add relationships between tables and calculations to extend the semantic model.

# Create visualizations in a report

* In Power BI Desktop, when you create a visualization (also called visual), you add it to the canvas for a report page.
* Power BI is a low-code solution, which means that you can "drag and drop" data field directly onto the canvas.
* Power BI will choose a visual for your data field.
* You can easily change between visuals for the same fields, and add or remove data fields to the visual.
* One of the most valuable features of Power BI reports is the interactivity between visuals.
* Consumers can select different data points in the visual and see how that affects the other visuals.
* Depending on your design, they can also drillthrough from one visual to more detail or filter based on different fields in the report.

# Create a dashboard

* In the Power BI service, you can also create dashboards after you've published a report.
* Dashboards consist of a single page made up of tiles.
* Add tiles to a dashboard by pinning a visual in a report to the dashboard.
* Dashboards are an excellent way to provide high-level information to consumers.


</details>

<details>
 <summary> Get and Tranform data with Power BI </summary>

# Get data from files

* Organizations often export and store data in files. One possible file format is a flat file.
* A flat file is a type of file that has only one data table and every row of data is in the same structure.
* The file doesn't contain hierarchies. Likely, you're familiar with the most common types of flat files, which are comma-separated values (.csv) files, delimited text (.txt) files, and fixed width files.

# Flat file location

* Local - You can import data from a local file into Power BI. The file isn't moved into Power BI, and a link doesn't remain to it. Instead, a new semantic model is created in Power BI, and data from the Excel file is loaded into it. Accordingly, changes to the original Excel file aren't reflected in your Power BI semantic model. You can use local data import for data that doesn't change.

* OneDrive for Business - You can pull data from OneDrive for Business into Power BI. This method is effective in keeping an Excel file and your semantic model, reports, and dashboards in Power BI synchronized. Power BI connects regularly to your file on OneDrive. If any changes are found, your semantic model, reports, and dashboards are automatically updated in Power BI.

* OneDrive - Personal - You can use data from files on a personal OneDrive account, and get many of the same benefits that you would with OneDrive for Business. However, you'll need to sign in with your personal OneDrive account, and select the Keep me signed in option. Check with your system administrator to determine whether this type of connection is allowed in your organization.

* SharePoint - Team Sites - Saving your Power BI Desktop files to SharePoint Team Sites is similar to saving to OneDrive for Business. The main difference is how you connect to the file from Power BI. You can specify a URL or connect to the root folder.

# Change the source file

* You might have to change the location of a source file for a data source during development, or if a file storage location changes.
* To keep your reports up to date, you'll need to update your file connection paths in Power BI.
  
# Power Query provides many ways for you to accomplish this task, so that you can make this type of change when needed.

1. Data source settings
2. Query settings
3. dvanced Editor

# Get data from Azure Analysis Services

* Azure Analysis Services is a fully managed platform as a service (PaaS) that provides enterprise-grade semantic models in the cloud.
* You can use advanced mashup and modeling features to combine data from multiple data sources, define metrics, and secure your data in a single, trusted tabular semantic model.
* The semantic model provides an easier and faster way for users to perform ad hoc data analysis using tools like Power BI.
* You’ve been asked to compare this data with actual sales data in a different database.
* Getting data from Azure Analysis Services server is similar to getting data from SQL Server, in that you can

1. Authenticate to the server.
2. Pick the model you want to use.
3. Select which tables you need.

# Notable differences between Azure Analysis Services and SQL Server are: 

1. Analysis Services models have calculations already created.
2. If you don’t need an entire table, you can query the data directly. Instead of using Transact-SQL (T-SQL) to query the data, like you would in SQL Server, you can use multi-dimensional expressions (MDX) or data analysis expressions (DAX).

# Unpivot columns

* Unpivoting is a useful feature of Power BI. You can use this feature with data from any data source, but you would most often use it when importing data from Excel.

  ![image](https://github.com/mesuli95/Power-BI/assets/162970734/56955c97-74db-4ae1-b64b-c3aac5ade321)

* Though the data might initially make sense, it would be difficult to create a total of all sales combined from 2018 and 2019.
* Your goal would then be to use this data in Power BI with three columns: Month, Year, and SalesAmount.

* When you import the data into Power Query, it will look like the following image.

![image](https://github.com/mesuli95/Power-BI/assets/162970734/a3f5502d-19fe-49bb-b260-242a197157d2)







</details>

