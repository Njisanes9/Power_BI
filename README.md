# POWER BI

# Introduction

**Microsoft Power BI** is a reporting solution offering data preparation, data visualization, distribution, and management through development tools and an online platform.

Power BI can scale from simple reports using a single ata source to reports requiring complex data modelling and consistent. Use Power BI to create visually stunning, interactive reports to serve as the analytics and decision engine behind group projects, divisions, or entire organizations.

# Primary(Building Blocks) component to Power BI

- **Power BI Desktop** - development tool available to data analysts amd other report creators.
- **Power BI Service** - allows one to organize, manage, and distribute reports and other Power BI items.
- **Power BI Mobile** - Allows consumers to view reports in a mobile-optimized format.

# Building blocks of Power BI

The building blocks of Power BI are **semantic models** and **visualizations**. Create a sementic model and then use visuals to build a report.

# Create a sementic model

A **semantic model** consists of all contected data, transformations, relationships, and calculations. To follow the flow of Power BI, you first connect to data, transform data, and create relationships and calculations to create a sementic model.

Many data sources can be connected to. Then data can be cleaned and tranformed to one needs. Add relationships between tables and calculations to extends the sementatic model. After all, a report can be created.

# Create visualization in a report

When creating a **visualization**(visual) in Power BI, you add it to the **canvas** for a reporting page. Power BI will choose a visual for you.

Interactivity between visuals is one of the most valuable feature of Power BI reports.

# Create a dashboard

With Power BI service, one can also create dashboards after having published a report. Dashboards consit of a single page made of of **files**. Dashboards an excellent way to provide high-level information to consumers.

# Organize items with workspaces

**Workspaces** are the foundation of the Power BI service. When publishing any report, you must choose a work space. To share content with others, **always** create and use a shared workspace.

**Sample Reports** can be accessed in the learn section of the navigation pane.
In a workspace one can create an app, which provides consumers a simplified to access reports and dashboards. When an app is create, the app must be updated after each change to items in the workspace.

# Explore template apps

**Template apps** allows you to find an existing app that suits your needs and then you connect your data. These apps can be a great way to quickly share insights with minimal efforts.

# DISCOVER DATA ANALYSIS

# Overview of Data Analysis

Data analysis is the process of identifying, cleaning, transforming, and modeling data to discover meaningful and useful information. The data is then crafted into a story through reports for analysis to support the critical decision-making process.

To analyze data, core components of analytics are devided into the following categories:

- **Descriptive analytics** - helps answer questions about what has happened based on the historical data. They summarize large semantic models to descibe outcomes to stakeholders.
  
- **Diagnostics analytics** - help answer questions about why events happened. They supplement basic descriptive analytics, and they use the findings from descriptive analytics to discover the cause of these events. This occurs in 3 steps:

  1. Identify anomalies in the data - anomalies may be unexpected changes in a metric or particular market.
  2. Collect data that's related to these anomalies.
  3. Use statistical techniques to discover relationships and trends that explain these anomalies.
 
- **Predictive analyitics** - helps answer questions about what will happen in the future. They use historical data to identify trends and determine if they're likely to recur. The predictive analytical tools provide valuable insight into what might happen in the future. Techniques include a variety of statistical and machine learning techniques such a nearal networks, decision tree, and regression.
  
- **Prescriptive** - help answer questions which actions should be taken to achieve a goal or target. By using insights from prescriptive analytics, organizations can make data-driven decisions. This technique allows businesses to make informed decisions in the face of uncertainty.
  
- **Cognitive analytics** - attempt to draw inferences from existing data and patterns, derive conclusions based on existing knowledge bases, and then add the findings back into the knowledge base for future inferences, a self-learning feedback loop. They help you learn what might happen if circumstances change and determine how you might handle these situations.
  
Inferences are instructured hypotheses that gathered from several sources and expressed with varying degrees of confidence. Effective cognitive analytics depend on machine learning algorithms, and will use several natural language processing concepts to make sense of previously untapped data sources, such as call center conversation logs and product reviews.

# Roles in data

- Business analyst
- Data analyst
- Data engineer
- Data scientist
- Database administrator

# Tasks of a data analyst

- **Prepare** - Data preparation is the process of profiling, cleaning, and transforming you data to get it ready to model and visualize. Data preparation is the process of taking raw data and turning it into information that is trusted and understandable. It involves, among other things, ensuring the integrity of the data, correcting wrong or inaccurate data, identifying missing data, converting data from one structure to another or from one type to another, or even a task as simple as making data more readable.

- **Model** - Data modeling is the process of determining how your tables are related to each other. This process is done by defining and creating relationships between the tables.

- **Visualize** - The data is being brought to life. The ultimate goal of the visualize task is to solve busines problems. By using appropriate visualizations and interactions, you can provide an effective report that guides the reader through the content quickly and effectively, therefore allowing the reader to follow a narrative into the data.

- **Analyze** - this task is the important step of understanding and interpreting the information that is displayed on the report.

- **Manage** - 


# Use tools to optimize Power BI performance

# Understand performance using performance analyzer

The **Performance analyzer** displays and records logs that measure how each of your report elements performs when users interact with them. You can also see which aspects of their performance are most(
or least) resource intensive.

Major subsystems involved in executing a Power BI report:

- **Report Canvas** - provides the user interaface for Power BI reports including hosting visuals and filters, managing user interactions for consuming and authoring reports and retrieving data for display. The **Report Canvas** is written using web technologies and runs in web browsers or web browser component. The **Report Canvas** retrieves data using a high-level, internal, Power BI query known as *Semantic Query*

- **Data Shape Engine** - evaluates Semantic Queries by generating and running one, or more DAX queries against a data model hosted inside Power BI, Power BI Desktop, Azure Analysis Services, or SQL Server Analysis Services.

- **Data Model Engine** -  stores the data model and provides services to reports, such as DAX query evaluation.

