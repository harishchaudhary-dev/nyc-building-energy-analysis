# NYC Building Energy & Water Efficiency Analytics

An exploratory data analysis (EDA) and predictive modeling pipeline using New York City's Local Law 84 (LL84) benchmarking data. This project inspects energy metrics, water usage intensity, and building features to understand urban resource consumption and predict building efficiency ratings.

## 📊 Dataset Overview
The project processes the **Energy and Water Data Disclosure for Local Law 84**, capturing metrics from thousands of properties across NYC boroughs. Key features analyzed include:
*   **Target Variables:** `ENERGY STAR Score`, `Site EUI (kBtu/ft²)`, `Source EUI`
*   **Building Attributes:** `Primary Property Type`, `Gross Floor Area (ft²)`, `Year Built`
*   **Resource Consumption:** Water Use Intensity, Natural Gas, Electricity, and various Fuel Oil indices.

## 🛠️ Tech Stack & Libraries
*   **Language:** Python
*   **Data Manipulation:** Pandas, NumPy
*   **Data Visualization:** Matplotlib, Seaborn
*   **Machine Learning (Setup):** Scikit-Learn

## 🚀 Key Steps Implemented
1. **Data Ingestion:** Reading large-scale urban infrastructure datasets safely with mixed data type handling.
2. **Data Cleaning:** Mapping legacy missing indicators (`"Not Available"`) to standardized null values (`NaN`).
3. **Automated Type Casting:** Programmatically converting unit-based text columns (`ft²`, `kBtu`, `gal`, `Score`) into optimized numeric data types for evaluation.
4. **Statistical Summarization:** Describing distribution constraints across 140+ active metrics.

## 📦 How to Run the Project

1. Clone the repository:
   ```bash
   git clone [https://github.com/harishchaudhary-dev/nyc-building-energy-analysis.git](https://github.com/harishchaudhary-dev/nyc-building-energy-analysis.git)
