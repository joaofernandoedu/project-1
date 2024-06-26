# Visualisation (Dashboard Report)

This section llustrates the step-by-step creation of a dashboard report using Power BI.

<img src="../../media/dashboard/load_data.png">

Elected MySQL as the data source and entered user credentials to access the respective host, database, and tables.

<img src="../../media/dashboard/transform.png">
<img src="../../media/dashboard/loaded.png">

Used Power Query to verify data types remain consistent with the database. Checked for any blank or duplicate values prior to loading into Power Pivot.

<img src="../../media/dashboard/dax.png">

Established a distinct "calendar" table housing date-related fields like years, months, and weekdays, utilising DAX to automatically generate a date range and parse it into relevant columns.

<img src="../../media/dashboard/model.png">

Confirmed that all relationships were established according to the database schema. Added a relationship between the calendar table and the factual table, validating their functionality through visual representations.

<img src="../../media/dashboard/measures.png">

Formulated measures to summarise data, including total sessions, registrations, average load time, and average duration. Due to the absence of historical data, implementing DAX time intelligence functions for year-over-year, month-over-month, or day-over-day comparisons was not possible.

<img src="../../media/dashboard/figma.png">
<img src="../../media/dashboard/canvas.png">


Before adding visuals, I utilised Figma tools to layout and design the dashboard. I prioritised important elements and emphasied key data points. My design approach focused on simplicity, minimalism, and readability. I explored designs on Dribbble and Freepik websites, which helped me choose an appropriate colour scheme, typography, and overall design.

<img src="../../media/dashboard/dashboard.png">

Constructed the final version of the dashboard, refining graph and chart content to spotlight essential data and eliminate clutter.