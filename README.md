# PRODIGY_DS_02
# Titanic Survival Prediction

This repository hosts my second task as a Data Science Intern at [Prodigy Infotech](https://www.prodigyinfotech.com/). The project focuses on the classic Titanic dataset to perform data cleaning, exploratory data analysis (EDA), and lay the groundwork for a survival prediction model.

## Project Overview

The Titanic dataset is widely used for beginners in machine learning and data science. It contains information about passengers on the ill-fated RMS Titanic, including their age, gender, passenger class, and whether they survived.

This project aims to:
1.  **Load and inspect** the `train.csv` and `test.csv` datasets.
2.  **Perform data cleaning** by handling missing values in key columns.
3.  **Conduct Exploratory Data Analysis (EDA)** to understand the distribution of passenger ages and the survival rates based on gender and passenger class.

## Files in this Repository

* `task2.ipynb`: The main Jupyter Notebook containing all the Python code for data loading, cleaning, and EDA.
* `train.csv`: The training dataset for the Titanic survival prediction challenge. (You'll need to source this from platforms like Kaggle if not already included in your download).
* `test.csv`: The test dataset for the Titanic survival prediction challenge. (You'll need to source this from platforms like Kaggle if not already included in your download).

## Technologies Used

* Python 3.x
* Pandas (for data manipulation and analysis)
* Matplotlib (for basic plotting)
* Seaborn (for enhanced statistical data visualization)

## Setup and Installation

To run this project on your local machine, please follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YourUsername/YourRepositoryName.git](https://github.com/YourUsername/YourRepositoryName.git)
    cd YourRepositoryName
    ```
    (Remember to replace `YourUsername` and `YourRepositoryName` with your actual GitHub username and repository name.)

2.  **Create a virtual environment (recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3.  **Install the required libraries:**
    ```bash
    pip install pandas matplotlib seaborn
    ```

4.  **Download the datasets:**
    This project requires `train.csv` and `test.csv`. These datasets are commonly found on Kaggle (e.g., [Titanic - Machine Learning from Disaster](https://www.kaggle.com/c/titanic/data)). Download these files and place them in the root directory of your cloned repository.

5.  **Run the Jupyter Notebook:**
    ```bash
    jupyter notebook task2.ipynb
    ```
    This command will open the Jupyter Notebook in your web browser, where you can execute the cells to see the data cleaning steps and visualizations.

## Exploratory Data Analysis Highlights

The notebook includes visualizations that reveal interesting patterns in the Titanic data:

* **Age Distribution:** A histogram showing the distribution of passenger ages.
* **Survival by Sex:** A bar plot illustrating survival counts broken down by gender, highlighting the higher survival rate among females.
* **Survival by Pclass:** A bar plot demonstrating survival rates across different passenger classes (1st, 2nd, and 3rd), indicating the impact of class on survival.

## Usage

Simply open and run the `task2.ipynb` notebook in a Jupyter environment. The comments within the notebook guide you through each step of the data loading, cleaning, and visualization process.

## Contribution

Feel free to fork this repository, open issues, or submit pull requests. Any suggestions for further analysis or model building are welcome!

## License

This project is open-sourced under the MIT License. See the `LICENSE` file for more details.
