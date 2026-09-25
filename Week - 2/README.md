Sample Superstore Data Analysis
📌 Project Overview
This project performs Exploratory Data Analysis (EDA) on the Sample Superstore dataset using Python.

The project analyzes sales, profit, product categories, delivery time, discounts, and relationships between numerical variables using different data visualization techniques.

🛠️ Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Google Colab / Jupyter Notebook
📂 Dataset
The project uses the Sample Superstore dataset.

The dataset is loaded using Pandas:

df = pd.read_csv("/content/samplesuperstore.csv")
🔍 Data Analysis Performed
1. Data Loading
The dataset is loaded into a Pandas DataFrame and basic information is displayed using:

df.head()
df.info()
df.describe()
2. Date Conversion
The Order Date and Ship Date columns are converted into datetime format.

df['Order Date'] = pd.to_datetime(df['Order Date'])
df['Ship Date'] = pd.to_datetime(df['Ship Date'])
3. Delivery Days Calculation
The number of days taken for delivery is calculated using the order date and ship date.

df['Delivery Days'] = (df['Ship Date'] - df['Order Date']).dt.days
4. Category Analysis
The unique product categories are identified and total sales are calculated for each category.

category_sales = df.groupby('Category')['Sales'].sum()
A bar chart is used to visualize Sales by Category.

5. Sales Distribution
A histogram is created to understand the distribution of sales values.

6. Profit Analysis
A bar chart is used to compare Profit by Category.

A boxplot is also used to understand the overall distribution and variation of profit.

7. Sales Distribution by Category
A barplot is created to compare sales values across different product categories.

8. Discount and Profit Analysis
A scatter plot is created to study the relationship between Discount and Profit.

This helps to understand how discounts may affect profitability.

9. Correlation Analysis
Numerical columns are selected and a correlation matrix is calculated.

numeric_df = df.select_dtypes(include="number")
corr = numeric_df.corr()
A correlation heatmap is used to visualize the relationships between numerical variables.

📊 Visualizations
The project contains the following visualizations:

Sales by Category
Sales Distribution
Profit by Category
Sales Distribution by Category
Profit Distribution
Profit Variation Across Categories
Impact of Discount on Profit
Correlation Heatmap
🎯 Objectives
The main objectives of this project are:

To understand the Sample Superstore dataset.
To perform basic data preprocessing.
To calculate delivery days.
To analyze sales and profit by category.
To visualize sales and profit distributions.
To study the relationship between discount and profit.
To identify correlations between numerical variables.
📁 Project Structure
Sample-Superstore-Data-Analysis/
│
├── Task 2.py
├── Task 2.ipynb
├── samplesuperstore.csv
└── README.md
🚀 How to Run
Using Google Colab
Open the Task 2.ipynb file in Google Colab.
Upload samplesuperstore.csv.
Run the cells one by one.
View the generated charts and analysis.
Using Jupyter Notebook
Install the required libraries:

pip install pandas numpy matplotlib seaborn
Then open the notebook and run the cells.


<img width="734" height="560" alt="image" src="https://github.com/user-attachments/assets/a52b9eee-a11f-44d5-8165-f697ecb7417c" />
<img width="712" height="468" alt="image" src="https://github.com/user-attachments/assets/6c1cf47d-54c9-4728-8972-c6de744ea804" />
<img width="573" height="459" alt="image" src="https://github.com/user-attachments/assets/115471e2-c48b-4bc2-b985-8fc02e61aaad" />
<img width="567" height="451" alt="image" src="https://github.com/user-attachments/assets/cf7ca7cb-ad79-430d-8e60-dccd9221952d" />
<img width="593" height="452" alt="image" src="https://github.com/user-attachments/assets/f06ace2a-22f6-4ba1-ad6d-1bbb7b2834a4" />
<img width="589" height="414" alt="image" src="https://github.com/user-attachments/assets/a0e21f28-bb07-462a-982a-aaf4d6de4db0" />
<img width="600" height="503" alt="image" src="https://github.com/user-attachments/assets/2c85fd01-4757-457a-bdd7-f0b7f037bdbd" />
<img width="589" height="453" alt="image" src="https://github.com/user-attachments/assets/4cd69885-a70b-422a-8311-9d74722741bc" />


👨‍💻 Author
Thangarathi A

BCA Student

📌 Conclusion
This project demonstrates how Python libraries can be used to perform exploratory data analysis and visualization on a retail dataset. The analysis provides insights into sales, profit, categories, discounts, delivery time, and correlations among numerical variables.


