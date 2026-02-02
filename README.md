# Battery Charging-Swapping Station Capacity Survey Dataset

## 📖 Overview
This repository contains survey data regarding the battery inventory capacity of **69 operating battery swapping stations** in Shenzhen, China.

The dataset was collected on **February 2, 2026**, to investigate the real-world infrastructure scale and to validate the representativeness of simulation parameters used in our research on **Heterogeneous-Battery Hybrid Energy Storage Systems (HB-HESS)**.

## 📊 Key Statistics
- **Survey Scope:** 69 Stations across major urban districts in Shenzhen (e.g., Nanshan, Futian, Guangming).
- **Total Battery Inventory:** 753 Units.
- **Average Capacity:** **10.91 Batteries per Station**.

## 💡 Key Finding
The statistical analysis reveals the actual distribution of battery slots in commercial operation. The data supports the rationality of using a **10-battery model** as a representative and conservative baseline for simulation studies in dense urban scenarios.

## 📂 Data Description
The dataset is provided in the `data/` directory (e.g., `CSS_in_China_Shenzhen.xlsx`).

| Column Name | Description | Example |
| :--- | :--- | :--- |
| `ID` | Index number of the record. | 1 |
| `District` | The administrative district where the station is located. | Guangming |
| `Station Name` | The specific name of the battery swapping station. | Kelu |
| `Total Units` | The total number of battery slots available at the station. | 10 |

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
