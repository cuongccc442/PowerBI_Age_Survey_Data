In this project, i:

Import the survey data into Power BI.

Perform data cleaning and transformation as needed.

Combine the data from the three survey years into one dataset.

Adjust and modify the data types to ensure compatibility.

Transform the "Male Population" and "Female Population" columns using the "Unpivot" feature to create two new columns: one for "Population" and one for "Gender".

Rename the "Gender" values to "Male" and "Female".
Create a Dim_Date table using the CALENDAR function.

Define the following measures:

Total_Pop: Total population.
Male_Population: Total male population (using the CALCULATE function with a gender filter).
Female_Population: Total female population.
Design the dashboard with the following visualizations:

Two Cards: Display the total male and female population.
Line Chart: Show population trends over the years.
Column Chart: Display population by region.
Stacked Column Chart: Display population by region, split by gender.
Pie Chart: Show the population distribution by year.
Bar Chart: Display the population distribution by country, highlighting the top 5 countries with the highest population.
