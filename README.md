# IBM Data Science Capstone Project

## Project Overview

In this capstone project, we aim to predict whether the Falcon 9 first stage will land successfully. SpaceX advertises its Falcon 9 rocket launches on its website, with a launch cost of $62 million. In comparison, other providers charge upwards of $165 million per launch. A significant part of the cost savings comes from SpaceX's ability to reuse the first stage of the Falcon 9.

By predicting the success of a Falcon 9 first stage landing, we can estimate the cost of a launch and help potential competitors evaluate whether they can bid against SpaceX for rocket launches. This project focuses on collecting and preparing data from an API to build a reliable prediction model.

## Objectives

- Collect data related to Falcon 9 rocket launches.
- Clean and preprocess the data to make it ready for analysis.
- Build a predictive model to determine if a Falcon 9 first stage will land successfully.
- Analyze and visualize the key features affecting the landing success.

## Tools and Technologies Used

- **Python**: For data analysis and model building.
- **Pandas**: For data manipulation and cleaning.
- **Scikit-learn**: For machine learning model building.
- **Matplotlib and Seaborn**: For data visualization.
- **Folium**: For map visualizations (if applicable).
- **Dash**: For building interactive web applications (if applicable).
- **Plotly**: For creating interactive visualizations.

## Data

The data used for this project is collected from SpaceX's publicly available rocket launch data. The key features of the dataset include:

- `FlightNumber`: The identifier for the launch.
- `LaunchSite`: The site where the rocket was launched.
- `LandingPad`: The location where the rocket was intended to land.
- `PayloadMass`: The mass of the payload.
- `Orbit`: The orbit type for the mission.
- `Class`: The outcome of the landing (1 = success, 0 = failure).
- `Date`: The date of the launch.

## Approach

1. **Data Collection**: Data is retrieved from SpaceX's API and preprocessed.
2. **Data Cleaning**: Missing values are handled, and unnecessary columns are dropped.
3. **Exploratory Data Analysis (EDA)**: Visualizations are created to identify patterns and relationships in the data.
4. **Feature Engineering**: Key features are selected for model building.
5. **Model Building**: Machine learning models (such as Logistic Regression, Random Forest) are built and evaluated for predicting landing success.
6. **Model Evaluation**: The model's performance is evaluated using metrics such as accuracy, precision, recall, and F1-score.


## Results

The results of the model will indicate how well we can predict the success of Falcon 9 first stage landings. The analysis includes insights into which features have the most impact on the landing success, as well as visualizations of the launch data and predictions.

## Conclusion

This project showcases the ability to build a predictive model using historical data to estimate the outcome of future Falcon 9 rocket launches. The insights gained can be used to help companies decide if they can competitively bid against SpaceX for rocket launches.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
