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

[🔗 View Dashboard Demo (if applicable)](https://your-dashboard-link.com)

## 👩‍💻 Team & Roles

| Name               | Role                 |
|--------------------|----------------------|
| Camilo Uribe       | Data Engineer / Analyst |
| [Other Members]    | UX / Visual Design   |
| [Other Members]    | Project Manager / Comms |

## 📄 License

This repository is for educational use only. Data is publicly available from DCCEEW.
