
# Global Terrorism Data Visualization

## Overview

The project aims to analyze and visualize global terrorism patterns from 1970 to 2017 using the Global Terrorism Database (GTD). The GTD is an open-source database containing detailed information on terrorist incidents worldwide, maintained by the National Consortium for the Study of Terrorism and Responses to Terrorism (START) at the University of Maryland. This analysis seeks to uncover trends, patterns, and insights into terrorist activities globally, thereby assisting in understanding the scope and impact of terrorism.

## Table of Contents

- [Introduction](#introduction)
- [Dataset Description](#dataset-description)
- [Methodology](#methodology)
- [Data Preprocessing](#data-preprocessing)
- [Visualizations](#visualizations)
- [Technologies Used](#technologies-used)
- [How to Run](#how-to-run)
- [Contributors](#contributors)
- [References](#references)
- [License](#license)

## Introduction

Terrorism remains a significant global threat impacting numerous nations and communities. This project explores the global patterns of terrorism by analyzing the GTD data from 1970 to 2017. Through various visualizations, this project provides insights into the temporal, spatial, and tactical aspects of terrorism, helping policymakers, researchers, and analysts understand and combat terrorism more effectively.

## Dataset Description

The Global Terrorism Database (GTD) is an extensive dataset with over 180,000 records of terrorist incidents. Key features of the dataset include:

- **Event Identification and Date Variables**: Unique identifiers for incidents, including dates and approximate dates when precise dates are unknown.
- **Location Variables**: Geographic details of incidents, such as country, region, city, and province.
- **Attack Information Variables**: Types of attacks, weapons used, and detailed descriptions of incidents.
- **Target and Perpetrator Variables**: Information on the target type and the groups or individuals responsible for the attacks.
- **Casualties and Consequences Variables**: Data on the number of casualties, both killed and wounded, and economic damage estimates.
- **Additional Information Variables**: Qualitative context such as motives, additional notes, and sources.

## Methodology

Our analysis involves a thorough exploration of the GTD dataset, including:

1. **Data Exploration**: Understanding the dataset's structure and identifying key variables for analysis.
2. **Data Cleaning and Preprocessing**: Handling missing values, outliers, and ensuring data consistency.
3. **Data Visualization**: Utilizing various visualizations to uncover patterns and trends in terrorism data.

## Data Preprocessing

Key preprocessing steps include:

- Dropping columns with excessive missing values to reduce noise.
- Imputing missing values based on similar observations to preserve data.
- Handling outliers to ensure robust and accurate insights.
- Data normalization and encoding to maintain consistency across the dataset.

## Visualizations

The project includes several visualizations to represent the data effectively:

1. **Choropleth Maps**: Display the geographic distribution of terrorism-induced casualties globally.
2. **Hive Plots**: Show connections between attack types and regions.
3. **Heatmaps**: Visualize the frequency of various target types in terrorist attacks across different regions.
4. **Line Charts**: Depict trends in global terrorist incidents over time.
5. **Parallel Coordinates Plot**: Illustrate relationships between factors affecting the success of terrorist attacks.
6. **Radar Charts, Treemaps, and Network Graphs**: Provide insights into specific terrorist groups, their alliances, and their target preferences.

## Technologies Used

- **Python**: For data manipulation, analysis, and visualization (Pandas, NumPy, Matplotlib, Seaborn, Plotly).
- **PySpark**: For big data processing and handling large datasets efficiently.
- **Plotly and Dash**: For interactive visualizations and dashboards.

## How to Run

1. Clone the repository from GitHub.
2. Install the necessary Python libraries using `pip install -r requirements.txt`.
3. Run the Jupyter Notebook or Python scripts to load the data, preprocess it, and generate visualizations.
4. For interactive plots, use `Dash` to run the web app locally.

## Contributors

- **Aashish Acharya**: [GitHub Profile](https://github.com/Acharya-jyu)
- **Dennish Karki**: [GitHub Profile](https://github.com/karki-dennis)
- **Liraj Maharjan**: [GitHub Profile](https://github.com/leeraaz)

## References

- Institute for Economics & Peace (2024). "Global Terrorism Index 2024."
- START, University of Maryland (2024). "Global Terrorism Database."
- Other scholarly articles and official reports cited within the report.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
