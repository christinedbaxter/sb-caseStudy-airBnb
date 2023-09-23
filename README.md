
# Airbnb New York City Data Analysis

## Project Overview

This project involves an in-depth analysis of Airbnb listings in New York City. The dataset contains various attributes such as listing ID, name, host ID, host name, neighborhood group, neighborhood, latitude, longitude, room type, price, minimum nights, number of reviews, last review, and reviews per month. The main objective is to uncover insights related to revenue generation by neighborhood and room type.

![Jupyter Notebook](./Airbnb_Exercise_Student_Facing_170221.ipynb)

## Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn

## Tasks and Analysis

### Data Preprocessing

- Loaded the Airbnb dataset into a Pandas DataFrame.
- Explored the dataset to understand its structure and the type of data it contains.

### Exploratory Data Analysis

#### Count of Listings by Neighborhood Group

- Calculated the number of Airbnb listings in each of the five Neighborhood Groups (Manhattan, Brooklyn, Queens, Bronx, Staten Island).

#### Percentage Distribution of Listings

- Computed the percentage distribution of listings across the Neighborhood Groups.

#### Revenue Calculation

- Created a new field named "Revenue," calculated as the product of the "Price" and "Number_Of_Reviews" columns.

#### Average Revenue by Neighborhood Group

- Plotted a bar chart to show which Neighborhood Group has the highest average revenues.

#### Top Revenue-Generating Neighborhoods

- Filtered the dataset to include only listings from Manhattan, Brooklyn, and Queens.
- Identified the top 3 revenue-generating neighborhoods in these three Neighborhood Groups.

#### Top Revenue-Generating Room Types

- Further filtered the dataset to include only the top 3 neighborhoods in each of the three main Neighborhood Groups.
- Identified the top average revenue-generating room type in each of these neighborhoods and visualized this using a bar chart.

## Key Insights

- Manhattan has the highest number of Airbnb listings and also generates the highest average revenue.
- Entire homes/apartments are generally the top revenue-generating room types across most neighborhoods.
- Among the neighborhoods analyzed, Williamsburg in Brooklyn and Harlem in Manhattan are the top revenue generators.

## Future Work

This analysis can be extended to include time-series data to understand seasonal trends, as well as incorporating additional data such as property amenities, host ratings, and guest reviews for a more comprehensive analysis.

## Author

Christine Baxter

## Acknowledgements

Data for this project was sourced from Airbnb listings in New York City.

## Version Control Workflow with Git/GitHub

The project leveraged Git and GitHub for version control, ensuring a systematic and collaborative approach to code development. The version control strategy is outlined below:

### Branching Strategy

1. **Initialization**: Created an initial `develop` branch as the base for development.
2. **Feature Branches**: For each major stage of the project (Initial Setup, Data Loading, Exploratory Data Analysis), a dedicated feature branch was created off of the `develop` branch.

### Commit and Merge Workflow

1. **Commit Changes**: After the completion of each stage, all changes were committed to the respective feature branch, encapsulating the progress in a version-controlled manner.
2. **Code Reviews and Merges**: The feature branch was then merged into the `develop` branch post-review. This ensures that the `develop` branch always contains the most recent, stable version of the project.
3. **Creating New Feature Branches**: A new feature branch was created from the updated `develop` branch for the next stage of the project.
4. **Final Merge**: Upon completion of all stages, the `develop` branch was merged into the `main` branch, signifying the conclusion of the project.

### Documentation

- Comprehensive comments were added at each stage for clarity and future reference.

By adhering to this workflow, the project maintained a high level of code integrity, streamlined collaboration, and enabled seamless tracking of project milestones.
