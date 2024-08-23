# ![R](https://img.shields.io/badge/r-%23276DC3.svg?style=for-the-badge&logo=r&logoColor=white) Data Manipulation Using R

![download (1)](https://github.com/user-attachments/assets/2f970765-0488-4c20-9417-930e0735b7ce)

## Description
This project focuses on analyzing and visualizing renewable energy consumption data across various countries from 1990 to 2019. Using R, the project demonstrates advanced data manipulation techniques, including data cleaning, transformation, and visualization, to uncover trends in renewable energy usage.

The dataset used for this report is the “Renewable energy consumption (% of total final energy consumption)” from the World Bank, which can be found at https://data.worldbank.org/indicator/EG.FEC.RNEW.ZS.

This dataset provides information on renewable energy consumption for each country, expressed as a percentage of total final energy consumption, from 1990 to 2019. The purpose of this report is to visualize the trend of renewable energy consumption across countries, with a focus on the top 20 countries with the highest renewable energy consumption in 2019.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Data Sources](#data-sources)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Visualizations](#visualizations)
- [Contributing](#contributing)

## Installation

### Prerequisites
- R (version X.X.X)
- RStudio (optional but recommended)
- Required R packages: `dplyr`, `ggplot2`, `tidyr`, `sf`, `rnaturalearth`, `rnaturalearthdata`

### Steps
1. **Clone the repository:**
   ```bash
   git clone https://github.com/Kaathihan/Data-Manipulation-Using-R.git
2. **Open the project in RStudio or your preferred R environment.:**
3. **Install the necessary packages:**
   ``` 
   install.packages(c("dplyr", "ggplot2", "tidyr", "sf", "rnaturalearth", "rnaturalearthdata"))
   ```
### Usage
- Load the dataset using the provided R scripts and follow the instructions to clean and transform the data.
- Execute the visualization scripts to generate plots and graphs.

### Features
- Data Cleaning: Handling missing values and data inconsistencies.
- Data Transformation: Aggregating, summarizing, and reshaping data using dplyr and tidyr.
- Data Visualization: Creating insightful plots using ggplot2 and mapping with sf.
  
### Data Sources
- World Bank: "Renewable energy consumption (% of total final energy consumption)" Link

### Project Structure
```
/Data-Manipulation-Using-R
  /data
  /scripts
    data_cleaning.R
    data_transformation.R
    data_visualization.R
  README.md
```
- /data: Contains raw and processed datasets.
- /scripts: Includes R scripts for data manipulation and analysis.
  
### Technologies Used
- Programming Language: R
- Packages: dplyr, ggplot2, tidyr, sf, rnaturalearth, rnaturalearthdata
- Tools: RStudio
  
### Visualizations
- Time Series Plot: Trends of renewable energy consumption for the top 20 countries.
- Bar Chart: Top 10 countries with the highest renewable energy consumption in 2019.
- Geographic Map: Renewable energy consumption by country in 2019.
- Line Chart: Renewable energy consumption in Canada from 1990 to 2019.
- Scatter Plot: Relationship between renewable energy consumption and time in Germany.
  
### Contributing
Contributions are welcome! Please follow these steps:
- Fork the repository.
- Create a new branch: git checkout -b feature/YourFeature
- Commit your changes: git commit -m 'Add some feature'
- Push to the branch: git push origin feature/YourFeature
- Open a pull request.

  
