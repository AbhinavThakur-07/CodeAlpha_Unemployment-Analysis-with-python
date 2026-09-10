# Unemployment Analysis Using Python

A data analysis project that explores unemployment and employment trends across Indian states and regions using Python. The project focuses on data cleaning, exploratory data analysis (EDA), aggregation, time-series analysis, and visualization.

## 📌 Project Overview

This project analyzes monthly unemployment statistics in India using two datasets. It examines unemployment rates, employment estimates, labour participation rates, regional differences, monthly trends, and rural vs. urban patterns.

The project also highlights the major unemployment spike during the COVID-19 lockdown period in 2020.

## 🎯 Objectives

- Analyze unemployment rates across Indian states/regions.
- Study monthly unemployment trends.
- Compare employment levels across regions.
- Analyze labour participation rates.
- Compare rural and urban unemployment patterns.
- Identify significant changes and unemployment spikes.
- Visualize unemployment and employment trends.
- Understand patterns during the COVID-19 lockdown period.

## 🛠️ Technologies Used

- **Python**
- **Pandas** — data cleaning, transformation, and analysis
- **NumPy** — numerical operations
- **Matplotlib** — static visualizations
- **Seaborn** — statistical visualizations
- **Plotly** — interactive visualizations
- **Jupyter Notebook** — analysis environment

## 📂 Project Structure

```text
unemployment-analysis/
│
├── Dataset/
│   ├── Unemployment in India.csv
│   └── Unemployment_Rate_upto_11_2020.csv
│
├── Images/
│   ├── image1.png
│   ├── image2.png
│   ├── image3.png
│   ├── image4.png
│   ├── image5.png
│   └── image6.png
│
├── Notebook/
│   └── unemployement.ipynb
│
├── requirements.txt
└── README.md
```

## 📊 Dataset Information

### Main Dataset

`Unemployment in India.csv`

The main dataset contains monthly unemployment information, including:

| Column | Description |
|---|---|
| `Region` | Indian state/region |
| `Date` | Monthly observation date |
| `Frequency` | Observation frequency |
| `Estimated Unemployment Rate (%)` | Estimated unemployment rate |
| `Estimated Employed` | Estimated number of employed people |
| `Estimated Labour Participation Rate (%)` | Labour force participation rate |
| `Area` | Rural or Urban classification |

### Supplementary Dataset

`Unemployment_Rate_upto_11_2020.csv`

The supplementary dataset contains additional 2020 unemployment information, including regional classification, unemployment rate, employment, labour participation rate, and geographic information.

## 🔄 Analysis Workflow

The notebook follows these major steps:

1. Import required Python libraries.
2. Load and explore both datasets.
3. Check dataset structure and information.
4. Clean and preprocess the data.
5. Convert date values into datetime format.
6. Prepare and combine the datasets.
7. Analyze unemployment by region.
8. Analyze unemployment by month.
9. Analyze employment by region.
10. Analyze employment trends by month.
11. Create static and interactive visualizations.
12. Study time-series patterns.
13. Compare rural and urban unemployment.
14. Identify key trends and findings.

## 📈 Key Findings

The analysis highlights several important patterns:

- **Regional disparities:** Tripura, Haryana, and Jharkhand show relatively high unemployment rates in the analyzed data.
- **Monthly patterns:** April and May show particularly high unemployment levels.
- **COVID-19 impact:** A major unemployment spike appears around April 2020 during the COVID-19 lockdown period.
- **Employment and unemployment:** Employment and unemployment do not always move in a perfectly inverse manner because labour-force participation also affects the relationship.
- **Rural vs. urban differences:** Rural and urban areas show different unemployment dynamics.

> **Note:** These are patterns observed in the analyzed datasets and should not be interpreted as causal conclusions without additional statistical and economic analysis.

## 📊 Visualizations

The project includes visualizations for:

- Unemployment by region
- Average unemployment by region
- Monthly unemployment trends
- Employment by region
- Monthly employment trends
- Time-series unemployment patterns
- Rural vs. urban comparisons
- Interactive Plotly charts

Example project images are stored in the `Images/` folder.

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone <your-github-repository-url>
cd unemployment-analysis
```

### 2. Create a virtual environment (recommended)

```bash
python -m venv venv
```

Activate it on macOS/Linux:

```bash
source venv/bin/activate
```

For Windows:

```bash
venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Start Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook from:

```text
Notebook/unemployement.ipynb
```

### 5. Run the notebook

Run the cells from top to bottom to reproduce the analysis and visualizations.

## 📦 Requirements

The required Python packages are listed in `requirements.txt`:

```text
pandas
numpy
matplotlib
seaborn
plotly
ipython
```

## 💡 Skills Demonstrated

- Python Programming
- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Pandas DataFrame Operations
- GroupBy and Aggregation
- Time-Series Analysis
- Data Visualization
- Interactive Visualization with Plotly
- Statistical Descriptive Analysis
- Working with CSV datasets

## 👨‍💻 Author

**Abhinav Kumar**

## 📄 License

This project is intended for educational and portfolio purposes.
