# Data-Analytics

# CHAPTER 1

1. What the role of a Data Analyst is and the scope of data analytics.

2. The process of data analytics.

3. The techniques of data analytics.

4. The role of data governance.

WHAT IS DATA ANALYTICS

- The ultimate role of a data analyst is to transform raw data into actionable insights that guide decision-making processes within an organization. 

- This involves several key responsibilities and skills.

- A data analyst helps an organization make informed decisions that can improve operational efficiencies, drive business strategies, and create a competitive advantage. 

- The goal is to contribute to the organization's success by turning data into a valuable asset that informs and drives decision-making.

1. Data Collection and Preparation:

 - Sourcing data from various channels, including databases, spreadsheets, and external sources,
 
 - Cleaning and organizing the data to ensure it is accurate, consistent, and ready for analysis.

2. Data Analysis:

 - Employing statistical methods, machine learning techniques, or other analytic tools to interpret data,
 
 - Identifying trends, patterns, and correlations that might not be immediately obvious.

3. Data Visualization and Storytelling:

 - Creating visual representations of the data, such as charts, graphs, and dashboards, to make complex information easily understandable,

4. Decision Support:

 - Making recommendations based on data-driven insights to help guide business decisions,
 
 - Providing context around the data, including potential implications and future trends.

5. Collaboration and Communication:

 - Working closely with other departments, such as marketing, finance, and operations, to understand their data needs and provide insights,
 
 - Effectively communicating complex data findings in a clear and concise manner to non-technical stakeholders,

6. Continuous Learning and Adaptation:

 - Keeping up-to-date with the latest industry trends, tools, and technologies in data analysis.
 
 - Adapting to new types of data and analytical methods as the organization's needs evolve.

 Analytics is made possible by modern data, storage, and computing capabilities.

THE ANALYTICS PROCESS

 Analysts working with data move through a series of different steps as they seek to gain business value from their organization's data. 

-Data Acquisition

-Cleaning and Manipulation

-Analysis

-Visualization

-Reporting and Communication

While we describe the steps of the analytics process as a series of sequential actions.

It is more accurate to think of them as a set of interrelated actions that may be revisited frequently while working with a dataset.

Analytics Techniques:

 Analysts use a variety of techniques to draw conclusions from the data at their disposal.

 Descriptive Analytics

-Descriptive analytics focuses on exploring and interpreting historical data to provide a comprehensive understanding of past events and trends. 

 Predictive Analytics

-Predictive analytics is particularly valuable for businesses when they want to stay ahead of future trends, behaviors, and outcomes.

Prescriptive Analytics

-Prescriptive analytics is most valuable for businesses when they are seeking to predict future outcomes and determine the best course of action to achieve specific objectives. 

DATA GOVERNANCE

-Data governance programs ensure that the organization has high-quality data and is able to effectively control that data.

ANALYTICS TOOLS

-Software helps analysts work through each one of the phases of the analytics process. 

-These tools automate much of the heavy lifting of data analysis, improving the analyst's ability to acquire, clean, manipulate, visualize, and analyze data. 

![image](https://github.com/ZaahidAbdurahman/Data-Analytics/assets/169241347/f09da0c1-e0ba-4ae7-a6e6-d04bd4a18d85)

Data Analytics Excel Spreadsheet



# CHAPTER 2

1. Understand Domain 1.0: Data Concepts and Environments

2. Compare and contrast different data types

3. Compare and contrast common data structures and file formats

EXPLORING DATA TYPES

- A data element is an attribute about a person, place, or thing containing data within a range of values.
- Data elements also describe characteristics of activities, including orders, transactions, and events. 




![Screenshot (1)](https://github.com/ZaahidAbdurahman/Data-Analytics/assets/169241347/936c362a-4aab-4396-961d-2a7cf267163f)





TABULAR DATA

- Tabular data is data organized into a table, made up of columns and rows. 

- A table represents information about a single topic.

- Each column represents a uniquely named field within a table, also called a variable, about a single characteristic. 

- The contents of each column contain values for the data element as defined by the column header.

- Spreadsheets, including Microsoft Excel, Google Sheets, and Apple Numbers, are practical tools for representing tabular data

- A relational database management system (RDMS), commonly called a database, extends the tabular model.

# Structured Data Types

- Structured data is tabular in nature and organized into rows and columns. 

- Structured data is what typically comes to mind when looking at a spreadsheet. With clearly defined column headings, spreadsheets are easy to work with and understand. 

- In a spreadsheet, cells are where columns and rows intersect.
 
![image](https://github.com/ZaahidAbdurahman/Data-Analytics/assets/169241347/83f2a93a-34b5-4530-9ea7-f7de6dd03c4b)

CHARACTER

- The character data type limits data entry to only valid characters. 

- Characters can include the alphabet that you might see on your keyboard, as well as numbers. 

- Depending on your needs, multiple data types are available that can enforce character limits.

Alphanumeric is the most widely used data type for storing character-based data. As the name implies, alphanumeric is appropriate when a data element consists of both numbers and letters.

- The alphanumeric data type is ideal for storing product stock-keeping units (SKUs).

![image](https://github.com/ZaahidAbdurahman/Data-Analytics/assets/169241347/0c408cfc-4acd-4bf6-8006-fd81b071bab9)



Table 2.2: Selected character data types and maximum size


Character Sets

- When considering alphanumeric and text data types, you need to think about the character set you are using to input and store data when using a database. 

- Databases use character sets to map, or encode, data and store it digitally.

Numeric

- When numbers exclusively make up values for a data attribute, numeric becomes the data type of choice.

Whole Number

- The integer, and all its subtypes, are for storing whole numbers. 

Rational Number

- In all its variants, the numeric data type is for rational numbers that include a decimal point.

Date and Time

- Gathered together under the broad category of date, day of year and time of day are data elements that appear with great frequency.

Currency
- Many people use spreadsheets to manage their finances. 

Strong And Weak Typing
- Data types define values placed in columns. 
- Strong typing is when technology rigidly enforces data types. 
- Databases, discussed in Chapter 3, use strong typing. A database column defined as numeric only accepts numerical values. You will get an error if you attempt to enter characters into a numeric column.

# Unstructured Data Types

 While much of the data we use to record transactions is highly structured, most of the world's data is unstructured. 

- Unstructured data is any type of data that does not fit neatly into the tabular model. 

- Examples of unstructured data include digital images, audio recordings, video recordings, and open-ended survey responses. 

- Binary data types are one of the most common data types for storing unstructured data.

- Audio data can come from a variety of sources. 

- Image data can come from a variety of sources.

- Video data is growing at a similar pace to image data.

- Large Text is another data type

  # Categories of Data

- We try to fit data into structured and unstructured categories. 

- The reality is that the world is not black and white, and not all data fits neatly into structured and unstructured categories. 

- Semi-structured data represents the space between structured spreadsheets and unstructured videos.

  Quantitative vs. Qualitative Data

- Quantitative data consists of numeric values. Data elements whose values come from counting or measuring are quantitative.

- Qualitative data consists of frequent text values. Data elements whose values describe characteristics, traits, and attitudes are all qualitative.

  Discrete vs. Continuous Data

  Discrete Data

- Numeric data comes in two different forms: discrete and continuous.

- Discrete data is that it represents measurements that can't be subdivided.

- You may intuitively think of discrete data as using whole numbers,

![image](https://github.com/ZaahidAbdurahman/Data-Analytics/assets/169241347/d2f5c70a-ee86-4e39-8af4-65cadcffe27c)


Continuous Data

- Continuous data refers to data that can be measured.
  
- This data has values that are not fixed and have an infinite number of possible values.

![image](https://github.com/ZaahidAbdurahman/Data-Analytics/assets/169241347/3090ea0c-2670-485e-88d0-064cb0b27503)



Categorical Data 

- In addition to quantitative, numeric data, there is categorical data. 

- Text data with a known, finite number of categories is categorical.

Dimensional Data

- Dimensional modeling is an approach to arranging data to facilitate analysis. 

- Dimensional modeling organizes data into fact tables and dimension tables.

# Common Data Structures

- In order to facilitate analysis, data needs to be stored in a consistent, organized manner.

- When considering structured data, several concepts and standards inform how to organize date.

Structured Data

- Tabular data is structured data, with values stored in a consistent, defined manner, organized into columns and rows. 

- Data is consistent when all entries in a column contain the same type of value.

  ![image](https://github.com/ZaahidAbdurahman/Data-Analytics/assets/169241347/2db99357-14be-49cf-b037-a924694858b0)

  Figure 2.19: Data Entry Error

![image](https://github.com/ZaahidAbdurahman/Data-Analytics/assets/169241347/6f96fe5f-9485-4d98-a4d7-976bbd2af0b4)

Figure 2.20: Data entry error identified in a summary


Unstructured Data

- Unstructured data is qualitative, describing the characteristics of an event or an object. 

- Images, phrases, audio or video recordings, and descriptive text are all examples of unstructured data.

![image](https://github.com/ZaahidAbdurahman/Data-Analytics/assets/169241347/3e198f8c-15fc-4044-8120-1624aade7bd9)

Figure 2.22: Unstructured data: log entry

Semi-Structured Data

- Semi-structured data is data that has structure and that is not tabular. 

- Email is a well-known example of semi-structured data.

- Every email message has structural components, including recipient, sender, subject, date, and time.

# Common File Formats

- Common file formats facilitate data exchange and tool interoperability. 

- Several file formats have emerged as standards and are widely adopted. 

- As a modern data analyst, you will need to recognize all of these formats and be familiar with common use cases for each type.

Text Files

- Text files are one of the most commonly used data file formats.

- As the name implies, they consist of plain text and are limited in scope to alphanumeric data. 

- When a file is comma-delimited, it is known as a comma-separated values (CSV) file. 

- Similarly, when a file is tab-delimited, it is called a tab-separated values (TSV) file.

  ![image](https://github.com/ZaahidAbdurahman/Data-Analytics/assets/169241347/9d13be63-a54c-4de6-93fc-827ea1e2c368)

Figure 2.25: Exporting as CSV or TSV

![image](https://github.com/ZaahidAbdurahman/Data-Analytics/assets/169241347/12e15ede-d994-4efb-928e-4caf88a1fba3)

Figure 2.26: Contents of a CSV file

![image](https://github.com/ZaahidAbdurahman/Data-Analytics/assets/169241347/bf1af23c-2d7c-4368-a588-15277a5620e5)

Figure 2.27: Semi-structured CSV

Fixed-Width Files

- Before it was common to use delimited files with variable-length columns, flat files were fixed-width. 

- As illustrated in Figure 2.28. Fixed-width files are more laborious to create since they require a few extra steps.

  ![image](https://github.com/ZaahidAbdurahman/Data-Analytics/assets/169241347/ab16021e-fbdc-4a63-9f6c-bef7c4ef07c7)

Figure 2.28: Fixed-width file

JavaScript Object Notation

- JavaScript Object Notation (JSON) is an open standard file format, designed to add structure to a text file without incurring significant overhead. 

- One of its design principles is that JSON is easily readable by people and easily parsed by modern programming languages.

![image](https://github.com/ZaahidAbdurahman/Data-Analytics/assets/169241347/0d0808b2-a1db-4985-8a10-50e5917e24af)

Figure 2.29: Pet data JSON example


Extensible Markup Language (XML)

- Extensible Markup Language (XML) is a markup language that facilitates structuring data in a text file. 

- While conceptually similar to JSON, XML incurs more overhead because it makes extensive use of tags. Tags describe a data element and enclose each value for each data element. 

![image](https://github.com/ZaahidAbdurahman/Data-Analytics/assets/169241347/67b83e15-aee6-417f-b808-55e4f9f09663)

Figure 2.32: Representing a single animal in XML

HyperText Markup Language (HTML)

- HyperText Markup Language (HTML) is a markup language for documents designed to be displayed in a web browser. 

- HTML pages serve as the foundation for how people interact with the World Wide Web. Similar to XML, HTML is a tag-based language.

![image](https://github.com/ZaahidAbdurahman/Data-Analytics/assets/169241347/90bd006e-7e77-4559-bd3f-9ded416a504a)

Figure 2.34: HTML table in a browser

Chapter 2 Summary

1. Consider the values of what you will store before selecting data types. 

- Data types are used to store different kinds of values. 

- When dealing with numeric information, the best option is a numeric data type that can accommodate decimals.


2. Know that you can format data after storing it.

- While data types determine how data gets stored, formatting data governs how data will be displayed to a person.


3. Consider the absolute limits of values that you will use before selecting data types.

- When selecting data types, consider the range of values that a data element can contain.


4. Explain the differences between structured and unstructured data

- Individual data elements fall along the structured data continuum. 

- At one end, there is highly structured, rectangular data.


5. Understand the differences in common file formats

- Common file formats make it easy for people to read a file's contents and facilitate interoperability between tools.

- Delimiters separate variable-length fields in a file. 










