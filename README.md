# AtliQ Hospitality Analysis Project

###  Purpose Of Project
The objective of this project is both clear and ambitious: to strengthen **AtliQ Grands**' market share and drive revenue growth through data-driven strategies and actionable insights. The analysis is designed to support smarter decision-making and position AtliQ Grands as a leading player in the luxury business hotel segment.

## Explore the live dashboard here- [Dashboard Link](https://app.powerbi.com/view?r=eyJrIjoiZjk1NzRlZmUtZDE5NC00NWQzLTgwNzgtMjRmMWI1ODA2ODJiIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

---

##  Data Structure & Modeling

### Data Sources
The datasets used for this analysis are provided by the [CodeBasics Bootcamp](https://codebasics.io/).  
The data comprises **Dimension Tables** (static data) and **Fact Tables** (transaction data):

### Data Model: **Star Schema**
The model is designed to simplify analysis and improve query performance.  
![Data Model](https://github.com/nafsheikh/Hospitality-Analysis-Project-Powerbi/blob/main/Modelling%20Page.png?raw=true)

#### Key Tables:
- **`dim_date`**: Stores calendar-related fields used for time intelligence and trend analysis.
- **`dim_hotels`**: Holds information about each hotel property, including location and identifiers.
- **`dim_rooms`**: Contains room type classifications and related attributes.
- **`fact_aggregated_bookings`**: Provides pre-calculated booking summaries for faster reporting.
- **`fact_bookings`**: Captures the granular booking transactions at the individual record level.

---


##  Power BI Dashboard Overview

The Power BI dashboard is divided into four interactive and visually appealing pages:

1. **Performance Page**
   
   Provides a high-level overview of AtliQ Hotels’ performance by showcasing key business metrics.
    Helps stakeholders quickly assess overall business health and identify major trends.
    Enables faster, data-driven decision-making through a clear and concise summary view.
   ![Perforrmance Overview-fotor-](https://github.com/nafsheikh/Hospitality-Analysis-Project-Powerbi/blob/main/Performance%20Page.png?raw=true)
   
2. **Revenue Page**
   
     Analyzes key revenue streams alongside occupancy patterns.
    Helps uncover demand behavior and performance fluctuations across properties.
    Supports strategic decisions by highlighting opportunities to improve revenue and capacity utilization.
    ![Revenue Overview-fotor-](https://github.com/nafsheikh/Hospitality-Analysis-Project-Powerbi/blob/main/Revenue%20Page.png?raw=true)

3. **Rating/Booking Page**
4. 
      Examines booking behavior alongside customer satisfaction ratings.
      Helps identify demand trends and areas impacting the guest experience.
      Enables data-driven improvements to enhance both occupancy performance and customer satisfaction.
    ![Rating,Booking Overview-fotor-](https://github.com/nafsheikh/Hospitality-Analysis-Project-Powerbi/blob/main/Rating,Booking%20Page.png?raw=true)
