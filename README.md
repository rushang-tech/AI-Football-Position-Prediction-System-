# Football Player Position Predictor (AI Coursework)

## Project Overview
This project is a Supervised Machine Learning system designed to classify football players into four distinct roles (Goalkeeper, Defender, Midfielder, Forward) based on quantitative performance metrics from the 2023-2024 season.

## Dataset
The project utilizes the **FBREF** dataset containing 34 columns of performance statistics.
- **Source:** FBREF / Kaggle
- **Preprocessing:** Players with < 450 minutes played were filtered out to reduce noise.

## Methodologies
The system implements and compares three classification algorithms:
1. **K-Nearest Neighbors (KNN):** Distance-based classification.
2. **Support Vector Machine (SVM):** Hyperplane-based classification in high-dimensional space.
3. **Random Forest:** Ensemble learning using decision trees.

## Results
- **Best Model:** [Insert which one worked best, usually Random Forest]
- **Key Challenges:** Handling hybrid player roles (e.g., Attacking Midfielders) and normalizing disparate metrics.

## Usage
1. Install dependencies: `pip install -r requirements.txt`
2. Run the script: `python src/main.py`
