# Power BI Hospital Patient Analytics Dashboard

## Project Overview

This repository contains a Power BI dashboard project focused on analyzing hospital patient data. The dashboard provides insights into patient demographics, medical conditions, treatment costs, readmission rates, satisfaction scores, and more. It was built using a CSV dataset with attributes like Age, Gender, Condition, Length of Stay, and Total Cost.

The goal is to support hospital decision-making, such as identifying common conditions, regional trends, and cost efficiencies. This is part of a larger project divided into data visualization (Power BI) and machine learning (predictive modeling).

## Features

- **Interactive Visualizations**: 10+ charts covering key metrics, including bar charts for condition distributions, maps for patient states, line charts for trends over time, and more.
- **Key Insights**:
  - Patient distribution by condition and gender.
  - Geographic admissions across Indian states.
  - Trends in length of stay and costs by year.
  - Readmission breakdowns and satisfaction scores.
  - Cost analysis by condition and medication.
- **Data Source**: Synthetic hospital patient dataset (Hospital-Patient.csv) with ~984 rows.
- **Tools Used**: Power BI Desktop for visualization.

## Files in This Repository

- `Nomulas-Hospital-Dashboard.pbix`: The main Power BI file containing the dashboard.
- `Hospital-Patient.csv`: The source dataset (optional; ensure you have permissions to share if sensitive).
- `Dashboard.jpg`: A screenshot preview of the dashboard.
- `README.md`: This file (project documentation).

## Getting Started

### Prerequisites
- Power BI Desktop (free download from Microsoft).
- Basic knowledge of Power BI for loading and interacting with the dashboard.

### How to Use
1. Download the `Nomulas-Hospital-Dashboard.pbix` file from this repository.
2. Open it in Power BI Desktop.
3. If prompted, connect to the dataset (import `Hospital-Patient.csv` if needed).
4. Interact with the visuals: Use slicers (e.g., by Year or Condition) to filter data.
5. Refresh the data if you update the CSV.

For best results, ensure your Power BI version is up to date (e.g., August 2025 or later).

## Dashboard Preview

![Dashboard Preview](Nomula'sDashboard.png)

*Sample dashboard showing key visuals like Condition by Total Cost, Year of Admission Trends, Readmission by Gender, and more.*

## Insights and Analysis
- **Top Conditions**: Heart Disease and Cancer dominate with higher costs and longer stays.
- **Demographics**: Balanced gender distribution, with elderly patients (>60) having longer stays.
- **Trends**: Readmissions higher for chronic conditions; satisfaction averages ~3.6/5.
- **Geographic**: Most patients from states like Kerala and Punjab.

For full details, explore the PBIX file.

## Credits
- Created by [Nomula Sathwik] as part of a hospital patient data project.
- Inspired by standard Power BI best practices and healthcare analytics templates.
- Dataset: Synthetic/generated for this project.

If you have questions or suggestions, feel free to open an issue or contact me!

---

*Last updated: August 2025. Licensed under MIT (or your preferred license).*
