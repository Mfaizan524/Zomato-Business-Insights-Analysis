**Zomato Business Insights Analysis - Power BI Project**

**Overview**

This project analyzes Zomato's business data to uncover anomalies and generate actionable insights through an interactive Power BI dashboard. The dashboard provides details on restaurant performance, customer ratings, and geographical data, fulfilling the business requirements outlined below.
________________________________________
**High-Level Business Requirements**
The Power BI dashboard allows users to:
1.	Analyze the total number of restaurants by continent, country, and city.
2.	View data at a global level and drill down to granular levels.
3.	Identify top-performing restaurants by average customer ratings and cost.
4.	Filter restaurants based on:
o	Geographic dimensions (continent, country, city).
o	Services (online delivery, table booking).
o	Rating color (denoting average ratings).
5.	Rank restaurants by the number of cuisines served.
6.	Access the dashboard via web browsers and mobile devices.
________________________________________
****Project Steps**

**1. Data Import****
•	Imported Excel files containing restaurant data for different continents and a fact table.
Files:
o	Africa
o	Asia
o	Country-Code
o	Europe
o	North America (NAM)
o	South America (SAM)
o	Oceania
o	Fact Table

**2. Data Transformations**

•	Corrected city names (e.g., "ÛÁstanbul" to "Istanbul").
•	Removed unused columns for cleaner datasets.
•	Split "Restaurant Name" and "Restaurant Address" into separate columns.
•	Created a separate table for cuisines served by each restaurant.
•	Ensured the "Country-Code" table contained unique, non-blank values.

**3. Data Modeling**

•	Established relationships with appropriate cardinality and cross-filter direction to ensure accurate aggregations.
•	Categorized geographic columns and created a user-defined hierarchy for continents, countries, and cities.

**4. Using DAX**

•	Created a Rating Color column based on average ratings:
o	Dark Green: Above 4.5
o	Green: 4.0 to 4.4
o	Yellow: 3.5 to 3.9
o	Orange: 2.5 to 3.4
o	Red: 1.8 to 2.4
o	White: 0 to 1.7
•	Developed measures:
o	Restaurant Count
o	Average Cost
o	Average Rating
o	Cuisine Count
•	Added a Continent column to the "Country Code" table based on predefined mappings.

**5. Data Visualization**

•	Created visuals including:
o	Cards: Average Cost, Average Rating, Restaurant Count.
o	Maps: Displaying restaurants by geographical hierarchy.
o	Infographics: Top 5 restaurants by average cost and rating.
o	Slicers: For filtering by rating color, countries, and cities.
o	Grids and Gauges: Showing restaurant details, cuisines, and ratings.
•	Published the report to Power BI Service with both web and mobile views.
________________________________________
**Deliverables**

1.	Power BI (.pbix) file containing the completed project.
2.	Public URL for accessing the dashboard via a web browser.
3.	Screenshots showcasing different dashboard features.
________________________________________
**Result Validation**

The project is deemed successful if it meets the following:
•	All files are imported and transformed as required.
•	Data modeling is correct and supports reporting needs.
•	All visuals, filters, and navigation menus are implemented correctly.
•	Values match the expected output.
•	Both web and mobile views are functional.
________________________________________
**Usage Instructions**
1.	Clone the repository:
bash
Copy Edit

2.git clone https://github.com/Mfaizan524/zomato-insights-powerbi.git  
3.	Open the .pbix file in Power BI Desktop.
4.	Explore the interactive dashboard or use the provided public URL to view the report online.
________________________________________
**Connect**

Feel free to reach out for questions or collaborations:

•	LinkedIn: https://www.linkedin.com/in/contact-mohd-faizan/

