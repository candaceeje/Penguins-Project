# Penguin Feature Selection with Machine Learning
This project explores feature selection techniques in machine learning using datasets of penguins from Antarctica. The goal is to identify the most significant features for classification tasks, improving model performance and interpretability.

## Project Structure
- *`data/`* – Contains the dataset of penguins
- *`notebooks/`* –  Jupyter notebooks with exploratory data analysis and model training
- *`models/`* – Saved machine learning models
- *`src/ `* – Python scripts for feature selection and model training

## Installation
Clone the repository and install dependencies:
`git clone https://github.com/your-username/your-repo.git
cd your-repo
pip install -r requirements.txt`

## Dataset
The dataset includes penguin species, culmen length/width, flipper length, and body mass, collected from different Antarctic islands.

## Feature Selection Methods
- **Filter Methods**: Correlation, Mutual Information
- **Wrapper Methods**: Recursive Feature Elimination (RFE)
- **Embedded Methods**: Lasso Regression, Tree-based Selection



## Usage
Run the main script for feature selection:
`python src/feature_selection.py`

## License
This project is licensed under the MIT License.

