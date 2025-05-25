Breast Cancer Data Analysis
This project provides an exploratory data analysis (EDA) of a breast cancer dataset. It leverages Python libraries like pandas, matplotlib, seaborn, and plotly to visualize patterns and correlations within the dataset.
Dataset
The dataset contains various features computed from digitized images of breast masses and is commonly used for breast cancer classification tasks.
Columns Include:
•	mean radius
•	mean texture
•	mean perimeter
•	mean area
•	mean smoothness
•	... (and other related statistical metrics)
•	target: 0 for malignant, 1 for benign
Steps Performed
•	Load and Preview Data: Loaded data using pandas and displayed the first five rows.
•	Scatter plot of mean area vs mean smoothness, color-coded by class.
•	Count plot showing the number of samples in each class.
•	Scatter matrix of selected features: mean radius, mean texture, mean area, mean perimeter, mean smoothness.
•	Heatmap showing the correlation between all features with annotations.
Libraries Used
•	Python 3.x
•	pandas
•	seaborn
•	matplotlib
•	plotly
How to Run
1. Clone the repository:
git clone https://github.com/PragmaticDevMyk/Seaborn_Visualization.git
cd Seaborn_Visualization
2. Install required packages:
pip install pandas matplotlib seaborn plotly
3. Run the analysis script
   
Future Work
•	Apply machine learning models (e.g., logistic regression, SVM).
•	Add interactive dashboards using Plotly Dash or Streamlit.
•	Perform feature selection and dimensionality reduction.
License
This project is open source and available under the MIT License.
