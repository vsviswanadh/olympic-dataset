🏅 Olympics Dataset Analysis
This project performs exploratory data analysis (EDA) on an Olympics dataset containing information about 70,000 athlete entries from 1896 to 2016.

📂 Project Structure
dataset_olympics.csv — The raw dataset containing details like Athlete Name, Age, Sex, Height, Weight, Team, Year, City, Sport, Event, and Medal.

olympic_dataset.ipynb — The Jupyter Notebook where data cleaning, visualization, and preliminary analysis are performed.

📊 Dataset Information
Rows: 70,000

Columns: 15

Key Features:

Athlete Info: Name, Sex, Age, Height, Weight

Event Details: Sport, Event, Team, Year, City, Season

Medal Info: Medal type (Gold, Silver, Bronze)

🔥 Analysis Performed
Data Loading
Loaded the CSV file into a Pandas DataFrame.

Data Cleaning

Checked and displayed missing values.

Dropped duplicate entries.

Basic Exploration

Descriptive statistics for numeric and categorical columns.

Visualizations

Gender Distribution
Used a countplot to show the number of male vs female athletes.

Age Distribution
Used a histogram to analyze the spread of athletes' ages.

📈 Libraries Used
Pandas — Data manipulation

Seaborn — Data visualization

Matplotlib — Plotting graphs

🚀 How to Run
Clone the repository (or download the files).

Open olympic_dataset.ipynb in Jupyter Notebook.

Run the cells step-by-step to reproduce the analysis and visualizations.

bash
Copy
Edit
pip install pandas matplotlib seaborn
📌 Future Work
Handle missing data more systematically (imputation or removal).

Perform medal analysis across countries and years.

Explore athlete performance based on age, weight, and height.

Build predictive models (optional).

🙌 Acknowledgments
The dataset used for this analysis is inspired by real Olympics data available in public repositories.

