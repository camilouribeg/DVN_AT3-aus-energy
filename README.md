# DVN_AT3 - Australian Energy Storytelling Dashboard

This project is part of a university data visualization assignment focused on building a compelling and human-centered data narrative using real-world datasets. We explore Australia’s renewable energy trends, consumption patterns, and industry-specific behaviors across states and time periods.

## 📊 Project Objective

To create an interactive dashboard that highlights:
- The evolution and distribution of **renewable energy** in Australia.
- **State-by-state comparisons** of energy generation and consumption.
- **Industry-level insights** showing who consumes what type of energy—and how that’s shifting.

## 🗂️ Dataset Source

All datasets are sourced from the [Australian Energy Statistics 2024](https://www.energy.gov.au/publications/australian-energy-update-2024) published by the Department of Climate Change, Energy, the Environment and Water (DCCEEW).

## 📁 Folder Structure


DVN_AT3-aus-energy/
├── data/
│   ├── raw/            <- Original Excel files from the government release
│   └── processed/      <- Cleaned CSVs used for analysis and visualization
├── scripts/
│   └── data_transf.ipynb <- All Python data cleaning and transformation logic
├── assets/             <- Diagrams and presentation figures
└── dashboard/          <- Final dashboard code and visual outputs




## 🔧 Data Processing

All transformation scripts are written in **Python** using `pandas`. Key operations included:
- Cleaning and standardizing units
- Melting multi-header tables
- Merging multi-sheet state tables
- Manual tagging of fuel types and industry categories

See the notebook [`data_transf.ipynb`](./scripts/data_transf.ipynb) for full transformation logic.

## ✅ Tables Processed

| Table | Description |
|-------|-------------|
| A     | Australian energy supply and consumption |
| B     | Population, GDP, and energy consumption by state |
| C     | Energy consumption by fuel |
| D     | Detailed consumption by fuel and state |
| E     | Consumption by industry and state |
| H     | Total final energy consumption (industry + fuel) |
| O     | Electricity generation by fuel and state |
| R     | Renewable consumption by fuel, industry, and activity |

These datasets are saved in the `data/processed/` folder and used for final visualization.

## 📈 Dashboard & Visualizations

The final dashboard presents:
- Heatmaps of renewable usage by state
- Line plots of generation trends
- Industry vs fuel consumption bars
- Clear visual storytelling guided by UX principles

[🔗 View Dashboard Demo (https://public.tableau.com/app/profile/siqi.zhang2285/viz/AustraliasEnergyConsumptionTransition/Dashboard2)

This repository is for educational use only. Data is publicly available from DCCEEW.
