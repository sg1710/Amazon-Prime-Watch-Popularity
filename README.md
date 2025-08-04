# Amazon-Prime-Watch-Popularity
Analyzed Amazon Prime Video data to explore trends in genres and ratings over time. Built a predictive ML model to estimate IMDb scores using genre and release year. Used Python for data cleaning and modeling, and Tableau for interactive dashboards and trend visualization.
This project focuses on analyzing and predicting content trends on Amazon Prime Video using data-driven techniques and visual storytelling. The objective was to explore how genres and release years influence IMDb ratings and to develop a predictive model capable of estimating the expected IMDb score for new or unseen titles.

The dataset included metadata from Amazon Prime Video content such as title, genres, release year, IMDb rating, and other descriptive fields. The project began with a rigorous data cleaning process using Python (Pandas), where missing values were handled, duplicate entries were removed, and genre fields were extracted and standardized. The main genre for each title was isolated to simplify analysis and reduce dimensionality.

For exploratory data analysis (EDA), Tableau was used to build a comprehensive dashboard that highlighted the evolution of content trends over the decades. Key insights included identifying which genres dominated certain periods (e.g., drama and action in the 2000s), how the volume of releases changed year-on-year, and which genres consistently received higher IMDb ratings. These insights were presented visually to help stakeholders quickly grasp the patterns.

To complement the trend analysis, a machine learning pipeline was developed in Jupyter Notebook to predict IMDb scores. The model used release_year and main_genre as features. Categorical variables were transformed using one-hot encoding. Various regression algorithms were tested, and Linear Regression was chosen for its interpretability and reasonable performance. The dataset was split into training and testing sets to evaluate model accuracy, and the predictions were compared with actual scores to validate effectiveness.

The final outputs—predicted scores and analysis results—were exported and visualized in Tableau to create a unified dashboard experience. This integration of EDA and predictive modeling offers both retrospective insights and forward-looking capabilities.

Tools Used: Python (Pandas, NumPy, scikit-learn), Jupyter Notebook, Tableau, Excel
Skills Demonstrated: Data cleaning, trend analysis, feature engineering, regression modeling, data visualization

