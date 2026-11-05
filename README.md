# Cloud_Platform
# ☁️ Cloud Platform Cost Optimization & Data Analysis

## 📌 Project Overview

This project focuses on analyzing cloud platform usage, resource utilization, and cost optimization using Python. The objective is to explore cloud infrastructure usage patterns, evaluate cost savings, and identify opportunities to improve resource efficiency.

The project follows the **Bronze, Silver, and Gold data architecture** to organize the data processing workflow, from raw data ingestion to data cleaning and visualization.

## 🎯 Project Objectives

- Analyze cloud platform usage and resource consumption.
- Identify missing values and duplicate records.
- Clean and validate the dataset using Python.
- Analyze cloud computing costs before and after optimization.
- Calculate statistical measures such as mean, median, standard deviation, minimum, and maximum.
- Compare cost savings across cloud providers.
- Visualize relationships between computing hours, costs, and resource utilization.

## 🛠️ Technologies & Tools Used

| Technology | Purpose |
|---|---|
| Python | Data analysis and processing |
| Pandas | Data manipulation and cleaning |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Jupyter Notebook | Development and analysis |

## 📂 Project Structure

```text
Cloud-Platform-Analysis/
│
├── Cloud_platform.ipynb
├── cloud_platform_cleaned.csv
├── cloud_platform.csv
│
├── plot1_cost_savings.png
├── plot2_compute_cost.png
├── plot3_correlation_heatmap.png
│
└── README.md
```

## 📊 Dataset Description

The dataset contains **10,000 records and 29 columns** related to cloud platform usage and optimization.

Key attributes include:

- `usage_record_id` – Unique usage record identifier.
- `usage_date` – Date of cloud resource usage.
- `platform` – Cloud platform or service.
- `cloud_provider` – Cloud service provider.
- `service_category` – Category of cloud service.
- `workload_type` – Type of workload.
- `environment` – Deployment environment.
- `region` – Cloud deployment region.
- `compute_hours` – Total computing hours.
- `vcpus` – Number of virtual CPUs.
- `storage_gb` – Storage consumption in GB.
- `data_processed_gb` – Data processed in GB.
- `cost_before_optimization_usd` – Cost before optimization.
- `cost_after_optimization_usd` – Cost after optimization.
- `cost_savings_usd` – Total cost savings.
- `cost_savings_percent` – Percentage of cost savings.
- `resource_utilization_percent` – Resource utilization percentage.
- `optimization_strategy` – Applied optimization technique.

## 🔄 Data Processing Workflow

### 1. Bronze Layer – Raw Data Ingestion

- Import the original cloud platform dataset.
- Load the CSV file using Pandas.
- Examine the initial dataset structure.

### 2. Silver Layer – Data Cleaning & Validation

- Identify missing values.
- Check data quality.
- Examine column formats.
- Format financial values into USD currency.
- Format percentage columns.
- Calculate statistical measurements.

### 3. Gold Layer – Data Analysis & Visualization

Create visualizations to understand cloud usage and cost optimization.

**Visualizations included:**

1. Bar Chart – Average Cost Savings by Cloud Provider.
2. Scatter Plot – Compute Hours vs. Cost After Optimization.
3. Correlation Heatmap – Relationships Between Cloud Usage Variables.

## 📈 Key Analysis Areas

- Cloud provider cost comparison.
- Computing resource utilization.
- Cloud infrastructure consumption.
- Cost savings after optimization.
- Relationships between computing hours and cloud costs.
- Correlation between resource usage variables.

## 🚀 How to Run the Project

**Step 1:** Clone the repository.

```bash
git clone https://github.com/your-username/Cloud-Platform-Analysis.git
```

**Step 2:** Navigate to the project directory.

```bash
cd Cloud-Platform-Analysis
```

**Step 3:** Install the required libraries.

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

**Step 4:** Launch Jupyter Notebook.

```bash
jupyter notebook
```

**Step 5:** Open `Cloud_platform.ipynb` and run the cells sequentially.

Make sure the original `cloud_platform.csv` dataset is available in the project directory before running the notebook.

## 💡 Skills Demonstrated

- Data Cleaning and Validation
- Exploratory Data Analysis (EDA)
- Python Programming
- Statistical Analysis
- Data Visualization
- Cloud Cost Analysis
- Bronze, Silver, and Gold Data Architecture
- Data-Driven Insights

## 👨‍💻 Author

**Lakshmi Triveni Meda**

Aspiring Data Analyst | Python | SQL | Data Visualization

