# Titanic Survival Prediction

A beginner-friendly machine learning project to predict survival on the Titanic dataset using simple rules.

## Dataset

Dataset used is from the [Kaggle Titanic Competition](https://www.kaggle.com/c/titanic).

## Features Used

- Age
- Sex
- Embarked
- Fare

## How It Works

- Data preprocessing: Filling missing values and encoding categorical variables
- Prediction rule: Predict survival if the passenger is female or under 10 years old

## Project Structure

```
titanic-survival-prediction/
├── data/           # train.csv and test.csv files (not included in repo)
├── src/            # prediction logic
├── outputs/        # generated submission file
```

## Running the Project

1. Place `train.csv` and `test.csv` in the `data/` folder.
2. Run:

```bash
python src/predict.py
```

3. Check `outputs/submission.csv` for results.

## License

This project is licensed under the MIT License.
