# Hazard-Prediction-System-NEO
# 🚀 Near Earth Objects (NEO) Data Analysis — Sprint 1

## 📌 Project Overview

This project focuses on analyzing **Near Earth Objects (NEOs)** using Python for data cleaning, preprocessing, and exploratory data analysis (EDA). The goal is to understand asteroid characteristics, detect patterns, identify hazardous objects, and prepare the dataset for future machine learning tasks.

The project was completed as part of **Sprint 1** of the data analytics workflow.

---

## 📂 Dataset Information

The dataset contains information about Near Earth Objects collected from NASA-related sources.

### Features Used

Some of the key columns include:

* `id` — Unique asteroid ID
* `name` — Asteroid name
* `absolute_magnitude` — Brightness measurement
* `estimated_diameter_min`
* `estimated_diameter_max`
* `relative_velocity`
* `miss_distance`
* `orbiting_body`
* `hazardous` — Whether the asteroid is potentially hazardous

---

## 🛠️ Technologies & Libraries

The project was built using:

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## 📊 Project Workflow

### 1️⃣ Data Collection & Loading

* Imported the dataset using Pandas
* Loaded CSV data into a DataFrame
* Verified dataset structure

### 2️⃣ Initial Data Inspection

Performed:

* Shape analysis
* Data type checking
* Missing value detection
* Duplicate value analysis
* Statistical summaries

### 3️⃣ Data Cleaning

Cleaning steps included:

* Handling missing values
* Removing duplicates
* Fixing inconsistent data types
* Preparing clean analytical dataset

### 4️⃣ Exploratory Data Analysis (EDA)

EDA was performed to understand:

* Feature distributions
* Relationships between variables
* Hazardous vs non-hazardous objects
* Correlations between numerical features

Visualizations used:

* Histograms
* Box plots
* Scatter plots
* Correlation heatmaps
* Pairplots

### 5️⃣ Outlier Detection & Treatment

* Identified extreme values
* Applied outlier handling techniques
* Improved data consistency

### 6️⃣ Feature Scaling

Applied scaling techniques for:

* Better model performance
* Standardized numerical features

### 7️⃣ Train-Test Split

Prepared the dataset for machine learning:

* Feature selection
* Target separation
* Splitting training and testing data

---

## 📈 Key Insights

* Most asteroid-related numerical features are highly right-skewed.
* Hazardous objects form a smaller percentage of the dataset.
* Strong correlations exist between diameter-related features.
* Data preprocessing significantly improves dataset quality.

---

## 📁 Project Structure

```bash
├── NEO_Sprint1.ipynb   # Main Jupyter Notebook
├── sprint1.csv         # Dataset file
└── README.md           # Project documentation
```

---

## ▶️ How to Run the Project

### Clone the Repository

```bash
git clone https://github.com/your-username/neo-data-analysis.git
cd neo-data-analysis
```

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Run the Notebook

```bash
jupyter notebook
```

Open `NEO_Sprint1.ipynb` and run all cells.

---

## 📌 Future Improvements

* Build machine learning models for hazard prediction
* Perform advanced feature engineering
* Create interactive dashboards using Plotly or Power BI
* Deploy the project as a web application

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome.
Feel free to fork the repository and submit a pull request.

---

## 📜 License

This project is for educational and learning purposes.

---

## ⭐ Support

If you found this project helpful, give it a ⭐ on GitHub!
