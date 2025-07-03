#  Breast Cancer Dataset Visualisation

**Visual Exploratory Data Analysis (EDA) of Breast Cancer Diagnostic Features**

##  Description

This project provides a clear and intuitive visual exploration of the **Breast Cancer Wisconsin Dataset**. 
It focuses on uncovering patterns and relationships between diagnostic features using descriptive statistics and correlation-based visualizations. 
Through a series of charts and heatmaps, it aims to assist in understanding tumor characteristics and their relationship to benign and malignant outcomes.

##  Features

*  Load the classic Breast Cancer Wisconsin dataset via scikit-learn
*  Convert dataset into a Pandas DataFrame and append the target labels
*  Compute descriptive statistics for all diagnostic features
*  Select key features for targeted correlation analysis
*  Generate a heatmap for selected diagnostic features
*  Visualize a full-feature correlation heatmap for comprehensive analysis
* Plot a class distribution bar chart (benign vs malignant)

##  Technologies Used

* Python 3
* scikit-learn
* pandas
* matplotlib
* seaborn
* Jupyter Notebook

##  Folder Structure

Breast\_Cancer\_Visualisation/
├── Breast\_Cancer\_Visualisation.ipynb
├── images/
│   ├── class\_distribution.png
│   ├── selected\_features\_heatmap.png
│   ├── full\_correlation\_heatmap.png
│   └── data\_flow\_diagram.png
├── README.md
├── requirements.txt
└── LICENSE

## 📦 Dependencies

Below packages are required to run this project:

* pandas
* numpy
* scikit-learn
* matplotlib
* seaborn
* jupyter 

To install them, run:

`pip install -r requirements.txt`

Or directly:

`pip install pandas numpy scikit-learn matplotlib seaborn jupyter`

## 📈 Data Flow Diagram

![93013844-e310-4b09-ad84-10d6b2f210b0](https://github.com/user-attachments/assets/2ff0aa4e-f1cc-46cf-a143-5caec24fa3ed)


A visual representation of the workflow:

1.  **Load Dataset**
2.  **Convert to DataFrame**
3.  **Descriptive Statistics**
4.  **Feature Selection**
5.  **Correlation Heatmap (Selected Features)**
6.  **Full Feature Heatmap**
7.  **Class Distribution Bar Chart**

1.Data Info
![1](https://github.com/user-attachments/assets/a3f8f53f-78d3-4b72-83ac-36e50ffd56f9)


2.Correlation Heatmap of Selected Features
![2](https://github.com/user-attachments/assets/7aad39f9-add8-46b9-b1b1-6e60acc68f41)


3.Correlation Heatmap of Breast Cancer Features
![download](https://github.com/user-attachments/assets/4235f9ac-8d33-4701-87ac-2473d67aeca4)


4.Pairplot of Selected Features
![download (1)](https://github.com/user-attachments/assets/086c699b-5666-48da-b06b-473c39d35367)


5.Distribution of {feature} for Malignant Cases
![download (2)](https://github.com/user-attachments/assets/fc718732-9ed7-4228-b085-7d9ecd2568f7)


6.Boxplot
![download (3)](https://github.com/user-attachments/assets/b6f0fcc0-90f3-42d9-b189-1eb45b2370fc)


7.Scatterplot: Mean Radius vs Mean Texture
![download (4)](https://github.com/user-attachments/assets/9a5ae379-1144-4d61-bb3d-a3a3e78fdc42)


8.Scatterplot: Mean Area vs Mean Smoothness
![download (5)](https://github.com/user-attachments/assets/16bc6bdc-0fa9-4af8-bb97-5e667ee68939)


9.Iterations


![dz](https://github.com/user-attachments/assets/e28f33bd-7679-4286-b039-3e1939ba93cd)





##  How to Run

1. **Clone the repository**

`git clone https://github.com/yourusername/Breast_Cancer_Visualisation.git`
`cd Breast_Cancer_Visualisation`

2. **Install dependencies**

`pip install -r requirements.txt`

3. **Run the notebook**

`jupyter notebook Breast_Cancer_Visualisation.ipynb`

4. **View generated visualisations in the notebook output .**

##  Learning Outcomes

* Applied real-world biomedical data for exploratory data analysis (EDA)
* Practiced data wrangling and preprocessing using pandas
* Developed multi-variable visualisations with seaborn and matplotlib
* Created clear, workflow-oriented visual documentation
* Strengthened skills in dataset interpretation and feature correlation analysis

##  License

This project is licensed under the [MIT License](Liscence).

##  Author

**Rishita Verma **
[GitHub Profile](https://github.com/Rishita-112001)

---


