# COVID-19 Data Analysis (Python Project)

This project analyzes and visualizes COVID-19 trends in U.S. states using a combination of Python libraries. It reads real-time data from public GitHub repositories and provides both statistical summaries and interactive visualizations.

---

##  Features

- Prompts user input (name and U.S. state)
- Calculates:
  - First day of recorded cases
  - Total and average daily cases and deaths for 2020 and 2021
  - Cumulative total as of the most recent date
- Offers two visualization options:
  - 📈 Four-panel graph (daily and cumulative cases & deaths)
  - 🗺️ Choropleth map by county (case totals using GeoPandas and Folium)

---

## Tools & Libraries Used

- **Python 3.x**
- **Jupyter Notebook**
- **Pandas** – for data cleaning and analysis
- **GeoPandas** – for geographic data and spatial joins
- **Matplotlib** – for plotting trends
- **Folium** – for interactive maps
- **Contextily** – for base maps (optional background tiles)
- **Mapclassify** – for color binning in choropleths
- **fsspec** – for reading remote ZIP shapefiles
- **GitHub-hosted CSV and ZIP shapefiles** – for live data loading

---

## How to Run

1. Open the `project.ipynb` notebook in Jupyter or VS Code
2. Run all cells
3. When prompted:
   - Enter your name
   - Enter the name of any U.S. state (e.g., `Virginia`, `Texas`)
   - Choose between:
     - `1` for charts
     - `2` for choropleth map

---

## Data Sources

- [COVID-19 cases & deaths data (GitHub)](https://github.com/babdelfa/project)
- [County shapefiles (GitHub)](https://github.com/babdelfa/gis)

---

## Example

```bash
Hello. Please enter your name: David
Enter the State: Virginia

COVID-19 in Virginia: Key Statistics

1. View trend charts
2. View a choropleth map of total cases
