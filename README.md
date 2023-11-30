# Tokyo Olympic azure data engineering project

## Overview
This dataset contains comprehensive information regarding the Tokyo Olympics. It encompasses various aspects such as athlete details, event specifics, medal tallies, and more. The dataset is sourced from Kaggle and serves as a valuable resource for analyzing the Tokyo Olympic Games.

### Source
The original dataset can be found on Kaggle at [Link to Kaggle Dataset](insert_link_here). Ensure you abide by Kaggle's terms and conditions for usage.

## Data Description
- **File Format**: CSV (Comma-Separated Values)
- **Data Fields**: The dataset includes fields such as Athlete Name, Country, Sport, Event, Medal Won, etc. Detailed descriptions of fields can be found in the dataset documentation.

## Data Engineering Process
### Transformations
The dataset undergoes several transformations to suit our project's data model and requirements:
- **Cleaning**: Handle missing or erroneous data points.
- **Normalization**: Ensure consistency in data format and encoding.
- **Data Enrichment**: Include additional relevant information if necessary.
- **Aggregation**: Aggregate data for specific analyses if required.

### Loading
The transformed dataset is loaded into our project's data storage. We use [insert_storage_solution] to store and manage the Tokyo Olympic data.

### Schema
The schema for the final transformed dataset might include tables such as:
- `athletes`: Contains details about athletes participating in various events.
- `events`: Includes information on Olympic events, categories, and timings.
- `medals`: Records medal tallies for each country or athlete.

## Usage
The transformed and loaded dataset is readily available for use within our data engineering project. It serves as a fundamental resource for:
- Statistical analysis of medal distribution.
- Athlete performance assessments.
- Country-wise medal counts and trends.

## Acknowledgments
- Kaggle community for providing the original dataset.
- Contributors who gathered and curated the data.

## Contributing
If you wish to contribute, feel free to submit pull requests or contact the project maintainers.

## License
This dataset is available under the terms specified by Kaggle. Please refer to the original dataset source for licensing details.

## Project Architecture

![Diagram](https://github.com/JahirMullick/Olympic-Dataset/assets/60438343/4a7f93e4-f2c7-4769-860b-ce4f4f0fd66b)
