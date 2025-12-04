# Better-Impact English Program Dashboard

##  Project Information

- A dynamitc, interactive data visualization that provideds high-level overview of the impact of English Program provided by volunteers for a non-profit local organization since 2020. 

- This dashboard is designed specifically for upper management like Director and Board members to see the increasing scope and impact of local English Program provided by volunteers around the world with drilldown capabiility to focus on different key metrices of quarter, year and class types.  

## Technologies Used

- Power BI Desktop
- Selenium (This is part of ETL process to extract reports from Better Impact Volunteer Management website)
- Python (This is part of ETL process to invoke Selenium and creating email notifications for missing hours to each Volunteer)
  
## Features

- Data Source

	- Over 31k records of Volunteer Reported Hours documented on Better Impact Volunteer Management website
	- ~1k records of Volunteer Feedback reports documented on Better Impact Volunteer Management website
	- Over 4k records of Scheduled English sessions tracked on Better Impact Volunteer Management website

- Features / Highlights
  	- There's no 1:1 relationship between Scheduled Session and Actual Volunteer Sessions which means extra outer join is required
  	- A separate Date dimension was created for proper time intelligence analysis
  	- Sensitive data of both learners and volunteers were anonymized 
- Business Impact & Insights

    - Volunteer Hours Reporting Discrepancy 
	

## Screenshots 

- Main dasbhoard without slicer panel shown
   
![Dashboard Preview](https://github.com/shengl711/Better-Impact-Non-Profit/blob/main/Better_Impact.png).

- Slicer panel to select quarter, year and Class type

![Dashboard Preview](https://github.com/shengl711/Better-Impact-Non-Profit/blob/main/Better_Impact_filter.png).

- Main Dashboard including Missing Hours reported over time and Missing Hours per top volunteer

![Dashboard Preview](https://github.com/shengl711/Better-Impact-Non-Profit/blob/main/Better_Impact_Missing_Hours.png).
