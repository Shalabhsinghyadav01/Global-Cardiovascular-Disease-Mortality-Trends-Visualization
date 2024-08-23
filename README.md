
# Global Cardiovascular Disease Mortality Trends Visualization



## Table of Contents
1. [Project Overview](#project-overview)
2. [Importance of the Project](#importance-of-the-project)
3. [Methodology](#methodology)
   - [Data Preparation](#data-preparation)
   - [Technology Stack](#technology-stack)
4. [Visualization Components](#visualization-components)
   - [Interactive World Map](#1-interactive-world-map)
   - [Line Chart](#2-line-chart)
   - [Bubble Chart](#3-bubble-chart)
5. [Tableau Work](#tableau-work)
   - [Tableau Files](#tableau-files)
   - [Key Tableau Visualizations](#key-tableau-visualizations)
   - [How to Access the Tableau Work](#how-to-access-the-tableau-work)
6. [Project Files](#project-files)
7. [Getting Started](#getting-started)
8. [Conclusion](#conclusion)
   - [Future Directions](#future-directions)
9. [License](#license)
10. [Contact](#contact)
## Project Overview
This project offers an interactive exploration of global cardiovascular disease (CVD) mortality trends, spanning from 1990 to 2019. By leveraging advanced data visualization techniques, the project highlights critical insights into age-standardized death rates across countries, presenting the data in a manner that is both informative and engaging.
### Key Features:
- **Interactive World Map**: A global view of cardiovascular disease mortality rates by country, allowing users to explore data over time through an intuitive interface.
- **Dynamic Line Chart**: A detailed analysis tool showing the progression of CVD death rates for selected countries, providing a clear picture of trends over nearly three decades.
- **Comparative Bubble Chart**: A visual comparison of CVD death rates across countries, enabling users to easily identify patterns, outliers, and regional disparities.

## Importance of the Project
Cardiovascular diseases remain the leading cause of death globally, and understanding their impact is vital for public health initiatives. This project seeks to:
- **Raise Awareness**: Illuminate the global burden of cardiovascular diseases, particularly highlighting areas with high mortality rates.
- **Enhance Understanding**: Provide a user-friendly platform for exploring trends and disparities in cardiovascular health across different countries.
- **Support Decision-Making**: Offer valuable insights that can inform public health strategies, policy-making, and further research.

## Methodology
### Data Preparation
The dataset, derived from the **Global Burden of Disease Study**, was meticulously cleaned and formatted to ensure accuracy and relevance. The dataset includes age-standardized cardiovascular disease death rates for various countries from 1990 to 2019.

### Technology Stack
- **HTML & CSS**: For structuring and styling the user interface, ensuring a seamless user experience.
- **D3.js**: Powers the interactive visualizations, offering dynamic and responsive elements.
- **TopoJSON**: Used for rendering geographical data, providing a detailed and accurate world map.

## Visualization Components
### 1. Interactive World Map
- **Purpose**: Visualize age-standardized cardiovascular disease death rates across the globe. Users can explore how these rates have changed over time by interacting with the map.
- **Implementation**: Created using D3.js and TopoJSON, this map includes a time slider and tooltips that provide detailed information for each country.

### 2. Line Chart
- **Purpose**: Analyze the temporal trends of cardiovascular disease mortality rates for selected countries. This chart offers a focused view on how these rates have evolved over time.
- **Implementation**: The line chart dynamically updates based on user interaction with the world map, offering a clear representation of historical trends.

### 3. Bubble Chart
- **Purpose**: Compare cardiovascular disease death rates across countries for a selected year. The size and color of the bubbles provide an immediate visual comparison.
- **Implementation**: The bubble chart is designed for intuitive comparison, making it easy to spot countries with the highest and lowest mortality rates.

## Tableau Work
In addition to the interactive web-based visualizations, this project also includes comprehensive visualizations created using **Tableau**. These Tableau visualizations offer an alternative perspective on the data and are designed to complement the insights gained from the web-based tools.

### Tableau Files
- **cardio vescular desease death rate.twb**: The Tableau workbook containing all the visualizations related to cardiovascular disease death rates.
- **cardiovascular-disease-death-rates.hyper**: The data file used in Tableau, which provides the necessary data for the visualizations.

### Key Tableau Visualizations
- **Global Mortality Dashboard**: An overview dashboard that presents a summary of cardiovascular disease mortality rates globally, with filters to explore specific countries and time periods.
- **Trend Analysis**: A detailed analysis of trends in cardiovascular disease mortality over time, allowing users to track progress or identify areas of concern.
- **Regional Comparisons**: A set of visualizations that compare cardiovascular disease death rates across different regions, highlighting significant disparities and trends.

### How to Access the Tableau Work
1. Open the `.twb` Tableau workbook file in Tableau Desktop.
2. Ensure the `.hyper` data source file is in the same directory as the workbook or correctly linked within Tableau.
3. Explore the dashboards and visualizations to gain additional insights into the global trends in cardiovascular disease mortality.

## Project Files
- **index.html**: The main HTML file, setting up the structure of the web-based visualization.
- **styles.css**: Defines the styling for the entire project, ensuring a professional and cohesive look.
- **script.js**: Contains the D3.js scripts responsible for the interactive elements of the web-based project.
- **cardiovascular-disease-death-rates.csv**: The dataset used for the web-based visualization, containing the age-standardized death rates.
- **Tableau Files**: The `.twb` and `.hyper` files used for creating the Tableau visualizations.

## Getting Started
To explore the web-based visualization:
1. Clone this repository to your local machine.
2. Open the `index.html` file in any web browser.
3. Interact with the visualizations to uncover insights into global cardiovascular disease mortality trends.

To explore the Tableau visualizations:
1. Open the `cardio vescular desease death rate.twb` file in Tableau Desktop.
2. Ensure that the `cardiovascular-disease-death-rates.hyper` file is properly linked as the data source.
3. Navigate through the dashboards and visualizations to explore the data further.

## Conclusion
This project offers a powerful tool for visualizing global trends in cardiovascular disease mortality. By combining interactive web-based visualizations with Tableau dashboards, it provides comprehensive insights that can drive public health strategies and contribute to a deeper understanding of global health challenges.
### Future Directions
- **Enhanced Data Integration**: Incorporating more granular data to provide a deeper analysis.
- **Comparative Analysis**: Expanding the project to include comparisons with other major health indicators.

## License

This project is licensed under the MIT License. Please refer to the [LICENSE](LICENSE) file for more details.



## Contact
If you have any questions or want to discuss the project, feel free to reach out:
- **Name**: Shalabh Singh Yadav
- **Email**: [shalabhsinghyadav@gmail.com](mailto:shalabhsinghyadav@gmail.com)
- **LinkedIn**: [LinkedIn Profile](https://www.linkedin.com/in/shalabh-singh-yadav-66b607204/)
- **Tableau**: [Tableau Profile](https://public.tableau.com/app/profile/shalabh.yadav/vizzes)

---

Explore the global impact of cardiovascular diseases through data-driven insights.