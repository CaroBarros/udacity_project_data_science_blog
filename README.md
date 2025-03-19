# udacity_project_data_science_blog
This repository contains the project submission for the "Data Science Blog" exercise as part of Udacity’s Data Scientist Nanodegree. 
The project explores factors influencing developer salaries using data from the 2024 Stack Overflow Developer Survey and implements predictive machine learning models to estimate salaries based on various features.

## 📌 Project Overview
The goal of this project is to analyze key factors that impact developer salaries and build machine learning models to predict salaries based on education level, geographical location, work experience, technology stack, organization size, and other relevant features.

## 🎯 Motivation
Understanding the factors that influence developer salaries is crucial for both job seekers and organizations. 
This project was motivated by:
- The opportunity to apply **machine learning models** in salary prediction and assess their effectiveness.  
- Identifying gaps in the dataset and potential additional features that could enhance salary predictions.  

## 💂‍ Repository Structure
This repository is organized as follows:

```
📁 project-root/
│── 📄 README.md                              # Project documentation
│── 📄 requirements.txt                       # List of dependencies
│── 📁 data/                                  # Contains raw and processed data
│   │── dataset.csv                            # Dataset used for analysis
│── 📁 notebook/                              # Jupyter Notebooks for data processing and analysis 
│   │── data_preparation.ipynb                # Dataset preprocessing script in Jupyter Notebook
│   │── data_science_exercise.ipynb           # Main analysisand modeling script in Jupyter Notebook
│  
```

## 🛠️ **Installation & Requirements**

To set up this project on your local machine, follow these steps:  

1. Clone this repository:  
   ```bash
   git clone https://github.com/'your_username'/udacity_project_data_science_blog.git  
   cd udacity_project_data_science_blog  


2. Install required dependencies:
```bash
pip install -r requirements.txt
```

Libraries:
- Pandas  
- NumPy  
- Matplotlib
- Seaborn
- Scikit-learn  

## 📊 Key Findings & Insights

- **Geography is the strongest salary predictor**: Developers based in **North America** have the highest salaries, followed by those in **Europe**. This suggests that location is a major factor influencing compensation.  
- **Work Experience has a strong correlation with salary**, particularly in the **Random Forest model**, where it was one of the most influential factors.  
- **Organization Size has a notable impact on salary**, with larger organizations generally offering higher compensation.  
- **The role of Education Level and Cloud Platform experience in salary prediction was minimal**, suggesting that other factors, such as **skills, job role, and industry,** might play a more significant role.  
- **Both models (Linear Regression and Random Forest)** showed relatively low predictive power (R² ~0.49-0.51), indicating that additional factors should be considered to improve salary predictions.
- **Model performance indicates room for improvement**—with Mean Absolute Errors (MAE) around $27,000, the predictions are not highly precise, and further optimization is needed.  
- A blog post in medium was created to present the results to a non technical audience: [blog post][def]

## 🙌 Acknowledgments
This project was completed as part of the **Udacity Data Scientist Nanodegree** program.  

Special thanks to:  
- The **Udacity team** for their guidance and curriculum.  
- The creators of the **2024 Stack Overflow Developer Survey dataset** for providing valuable data.  
- The **open-source community** for their contributions to the libraries used in this project.  




[def]: https://medium.com/@carolina.barros.ds/what-really-drives-developer-salaries-a-data-driven-exploration-eb7d45bcc295