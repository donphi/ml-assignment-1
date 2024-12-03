# Assessment 1: Data Mining and Machine Learning (Python Programming)
## Data Mining & Machine Learning (7BUIS008W)
### University of Westminster

**Submission Date:** 3rd December 2024  
**Student Name:** Donald Philp

---

👋 Welcome to my repository for Assessment 1 of the Data Mining & Machine Learning module, part of the MSc Artificial Intelligence and Digital Health program at the University of Westminster! This project focuses on building and evaluating machine learning models for breast cancer mortality and survival prediction, using data mining techniques to address a real-world healthcare problem. Below, you'll find details about the repository's structure and contents. Enjoy exploring! 🚀

## 📂 Contents
- **File Structure**
  - **Data**: Raw data files used for the assignment
  - **Notebooks**: Python notebooks used for analysis and model building
  - **Reports**: Final report and supporting documents
- **Assignment Overview**
- **Learning Outcomes**
- **Notes**

## 🗂️ File Structure
This repository is organized as follows:

```
├── assignment_brief
│   ├── 7BUIS008.1_DataMiningMachineLearning_CW1_Project_24-25.docx  # Assignment brief (Word)
│   ├── 7BUIS008.1_DataMiningMachineLearning_CW1_Project_24-25.pdf   # Assignment brief (PDF)
├── data
│   └── raw
│       ├── Breast_Cancer_Mortality_Survival_Dataset.csv             # Dataset for mortality and survival prediction
├── docker
│   ├── Dockerfile                                                   # Docker environment configuration
│   ├── env.example                                                  # Environment variable template
│   └── requirements.txt                                             # Required Python packages
├── .gitignore                                                       # Ignore unnecessary files
├── notebooks
│   └── Assignment 1.ipynb                                           # Jupyter notebook for the assignment 💻
├── README.md                                                        # This file 📖
├── references
│   ├── final
│   │   ├── Optimal training and test sets design for machine learning.pdf   # Reference material
│   │   ├── peerj-cs-10-2245.pdf                                            # Reference material
│   │   ├── s40009-022-01131-9.pdf                                          # Reference material
│   │   └── s41598-024-57740-5.pdf                                          # Reference material
├── reports
│   ├── Donald Philp - Assignment 1 - DM & ML.docx                   # Word version for submission 📝
│   ├── Donald Philp - Assignment 1 - DM & ML.pdf                    # Final report (PDF) 📁
│   ├── figures
│   │   ├── decision_tree_yellow_manual.png                          # Visual representation of the decision tree
│   │   ├── decision_tree.png                                        # Decision tree diagram
│   │   ├── distribution_plot.png                                    # Data distribution plot
│   │   ├── Precision-Recall Curve.png                               # Precision-recall curve plot
│   │   └── Tables.xlsx                                              # Supporting table data
```

## 📊 Data
The `data/raw` directory contains the datasets used for the assignment:

- **breast_cancer_data.csv**: Dataset for building models to predict breast cancer mortality and survival.
- **data_dictionary.pdf**: Document explaining the attributes within the dataset.

## 📓 Notebooks
The `notebooks` directory contains the Jupyter notebook used for this assignment:

- **Assignment1.ipynb**: The Jupyter notebook containing all the Python code used to solve the assignment tasks, from data preprocessing to building machine learning models. This notebook is well-documented and follows good programming practices. 🖋️

## 📑 Reports
The `reports` directory contains documents related to this assessment:

- **Assessment 1 Data Mining ML - Donald Philp.pdf**: The final compiled report submitted for assessment. 📁
- **Assessment 1 Data Mining ML - Donald Philp.docx**: Word document version for submission requirements.
- **DMML-Coursework-Assessment1.pdf**: The assignment questions and guidelines provided by the module leader.

## 🚀 Usage
To run the Python code:

1. Clone the repository to your local machine:
   ```
   git clone [repository URL]
   ```
2. Navigate to the notebooks directory:
   ```
   cd notebooks
   ```
3. Open `Assignment1.ipynb` in Jupyter Notebook or any compatible IDE. Make sure the working directory is set correctly:
   ```python
   import os
   os.chdir("path/to/repository")
   ```
4. Install the required packages as specified at the top of the notebook.

5. Run the cells to reproduce the analyses and results! 🎉

## 📋 Assignment Overview
The assignment required us to:

- Apply machine learning to predict breast cancer mortality and survival rates. 💉
- Use data mining techniques to clean, preprocess, and analyze the data.
- Develop predictive models using Python, following CRISP-DM methodology.
- Evaluate the models' performances and provide critical insights.

## 🎓 Learning Outcomes
Through this assignment, I was able to:

- **Understand Data Mining and Machine Learning Techniques**: Learn how to apply ML algorithms for real-world healthcare challenges.
- **Data Manipulation and Analysis**: Use Python to manipulate and analyze data effectively.
- **Model Building and Evaluation**: Implement various machine learning models and evaluate their performance using appropriate metrics.
- **Good Programming Practices**: Write modular, clean, and well-documented code. ✨
- **Communicate Results**: Document the entire process effectively in a structured report.

## 📝 Notes
- The `.gitignore` file ensures that unnecessary files are not added to the repository.
- The `indesign` directory contains InDesign files used to compile the final report (optional for running the code).
- A duplicate of the final report PDF is provided in the root directory for easy access.
- All datasets are included in the `data/raw` directory; no external data sources are required.

## 📧 Contact
Disclaimer: This repository is for educational purposes to showcase the work completed for the Data Mining & Machine Learning assignment. Please do not plagiarize or directly copy any part of this work. 🤓✌️

Thank you for taking the time to explore my work! 🧠💡 I hope this helps you understand the data analysis and machine learning process in the healthcare domain. 🚑✨
