# asuse-multi-year-analysis
Combining and visualizing multi-year ASUSE (Annual Survey of Unincorporated Sector Enterprises) data from MoSPI to explore trends in India's unincorporated sector over time.



# ASUSE Data Explorer

Combining, cleaning, and visualizing data from the **Annual Survey of Unincorporated Sector Enterprises (ASUSE)**, published by India's Ministry of Statistics and Programme Implementation (MoSPI).

## 📌 About

The ASUSE survey covers India's unincorporated non-agricultural enterprises (excluding construction) in manufacturing, trade, and other services. This project brings together multiple years/releases of ASUSE data into a single, clean dataset and generates visualizations to explore trends, sector-wise patterns, and state-wise comparisons.

## 🎯 Goals

- Combine raw ASUSE data files (Excel/CSV/PDF extracts) into one unified dataset
- Clean and standardize columns across different survey years
- Generate exploratory visualizations (trends, sector comparisons, regional breakdowns)
- Keep the analysis reproducible via notebooks and scripts

## 🗂️ Project Structure

```
asuse-data-explorer/
├── data/
│   ├── raw/              # Original/unmodified ASUSE data files
│   └── processed/        # Cleaned & combined datasets
├── notebooks/
│   └── exploration.ipynb # Main exploratory analysis notebook
├── scripts/
│   ├── combine_data.py   # Merges raw files into one dataset
│   └── generate_charts.py# Produces charts from the processed dataset
├── outputs/
│   └── charts/           # Saved graph images
├── requirements.txt
└── README.md
```

## 🛠️ Tech Stack

- Python
- pandas (data wrangling)
- matplotlib / seaborn (visualization)
- Jupyter Notebook

## 🚀 Getting Started

```bash
# Clone the repo
git clone https://github.com/<your-username>/asuse-data-explorer.git
cd asuse-data-explorer

# Install dependencies
pip install -r requirements.txt

# Run the data combination script
python scripts/combine_data.py

# Generate charts
python scripts/generate_charts.py
```

Or explore interactively via `notebooks/exploration.ipynb`.

## 📊 Sample Outputs

_Charts and key findings will be added here as the analysis progresses._

## 📁 Data Source

Data sourced from official MoSPI ASUSE releases: https://www.mospi.gov.in/

## 📝 License

This project is open-sourced under the MIT License.

## 🙋 Status

🚧 Work in progress — data combination and visualization scripts are actively being developed.
