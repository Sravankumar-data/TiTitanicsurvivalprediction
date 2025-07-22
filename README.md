# Titanic Survival Prediction

This repository presents a **machine learning project** to predict passenger survival on the Titanic using historical passenger data.

## Dataset

The dataset used in this project is provided as `Titanic-Dataset.csv`. It contains comprehensive information about each passenger, including:

- **PassengerId**: Unique identifier for each passenger
- **Survived**: Survival outcome (0 = No, 1 = Yes)
- **Pclass**: Passenger class (1st, 2nd, 3rd)
- **Name**: Passenger name
- **Sex**: Gender
- **Age**: Age in years
- **SibSp**: Number of siblings/spouses aboard
- **Parch**: Number of parents/children aboard
- **Ticket**: Ticket number
- **Fare**: Ticket fare
- **Cabin**: Cabin number
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## Project Workflow

- **Data Exploration**  
  Explore distributions, relationships, and patterns among variables that might affect survivability, such as class, gender, age, and family connections.
- **Data Preprocessing**  
  Clean missing values (mainly from Age and Cabin), encode categorical features (Sex, Embarked), and prepare the dataset for modeling.
- **Feature Engineering**  
  Create or transform features to enhance prediction performance (e.g., family size, is_alone features).
- **Modeling**  
  Build a binary classification model (such as logistic regression or decision trees) to predict the `Survived` column.
- **Evaluation**  
  Analyze the model’s accuracy, recall, and feature importance to interpret prediction results.

## How to Use

1. **Clone** this repo.
2. **Install** Python dependencies from `requirements.txt`.
3. Open the Jupyter notebook or relevant script.
4. **Run** the analysis with `Titanic-Dataset.csv` in your working directory.

## Technologies Used

- Python 3
- pandas & numpy
- scikit-learn
- matplotlib & seaborn (for visualization)
- Jupyter Notebook

## Contribution

Contributions are welcome! Please feel free to fork the repository, open issues, or submit pull requests.

## License

This project is for educational purposes and uses public historical data.

