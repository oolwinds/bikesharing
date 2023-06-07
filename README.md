# Bike Sharing Data Visualization with Tableau

This project was done to analyze the London bike sharing data to reveal trends and patterns in bike usage over time and in response to weather conditions, while exposing myself to more advanced Tableau features. 



https://github.com/oolwinds/bikesharing/assets/130780065/c6bffbb4-fec7-40c6-bf58-bdd47f807235

## Data Acquisition
Dataset : https://www.kaggle.com/datasets/hmavrodiev/london-bike-sharing-dataset

The dataset was procured from Kaggle. The dataset was pulled through Kaggle API then downloaded and unzipped using python.

## Data Manipulation
Before visualizing the data, it was processed and cleaned using the Pandas library in Python. The initial data exploration provided insights into the structure of the dataset and the variables it contained. Any inconsistencies and missing values were dealt with during the manipulation phase, ensuring the final dataset was suitable for further analysis.

The data was then written out to an Excel file named 'London bikes final' to facilitate its use in Tableau for creating the visualizations.

## Dashboard Creation
A comprehensive dashboard was created in Tableau to provide a visual interpretation of the data. The dashboard was composed of several key elements:

**Total number of bike rides**: Displayed in the top-left corner of the dashboard, this provided a quick overview of the dataset's scale.

**Moving average chart**: This was the main visualization on the dashboard. It was constructed using calculated fields to determine the moving average duration and period. A user could modify the moving average period using a parameter, thereby exploring bike usage trends over different time periods.

**Temperature vs Wind speed heat map**: This visualization was placed beneath the moving average chart. It provided an intuitive representation of the relationship between weather conditions (specifically, temperature and wind speed) and bike usage.

Interactive elements: The dashboard incorporated user interactivity via sets and filters. The 'Moving Average Period' set allowed users to focus on specific date ranges. This set was created by identifying the minimum and maximum months within the data and verifying if the chosen date fell within this range. Another feature was the timeline filter, which enabled users to filter data based on the 'Moving Average Period'.

**Tooltip charts**: Additional insights were provided through tooltip charts that became visible when hovering over the moving average chart or the heat map. These tooltip charts depicted the number of bike rides split by weather condition and hour of the day.

**Styling and formatting**: A consistent color scheme and format were applied across the dashboard to ensure readability and aesthetic appeal. This included bold, green fonts, and green borders around key elements.

## Conclusion
The final dashboard served as an effective tool for exploring the London bike sharing data and gleaning insights from it. When data visualization is combined with interactive elements, it allows users to manipulate and view the data in various ways. The completion of this project has significantly contributed to understanding the intricacies of data manipulation and visualization, demonstrating how to efficiently use Python and Tableau to derive actionable insights from complex datasets.
