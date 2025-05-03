# 🎬 Netflix Data Analysis

## 🧩 Project Overview

This project explores and analyzes a dataset of Netflix content with the goal of uncovering trends and insights related to movies and TV shows.  
The analysis covers production trends, duration, ratings, content distribution by country, and international collaborations.  
Geospatial components were also integrated using country coordinate data to enhance the visual representation of global distributions.

This work was completed as part of an academic exercise in data science and exploratory data analysis (EDA).

## 📊 Dataset

The following datasets are used:

- `netflix_titles.csv`: contains metadata for Netflix movies and TV shows
- `country_coordinates_cache.csv`: a helper file with country coordinate mappings used for geographic plotting

Key fields in the dataset:
- Title, director, cast
- Type (Movie or TV Show)
- Country of production
- Date added and release year
- Rating and duration
- Genre(s)
- Description

The data was cleaned, and additional features were added:
- `duration_minutes`
- `year_added`
- `month_name_added`

## 🔍 Performed Analyses

The main notebook (`progetto.ipynb`) includes:

- 📈 **Production trends** by release year and date added to Netflix
- 🕒 **Duration distribution** over time
- 🌍 **Content distribution by country and hemisphere**
- 🌐 **Map visualizations** using country coordinates
- 🤝 **Top countries and collaborations** in co-productions
- 🎞️ **TV show vs movie rating distributions**
- 📅 **Monthly release trends** with geographic overlays

## 🛠️ Technologies Used

- **Python 3**
- **Pandas** – data manipulation
- **Matplotlib / Seaborn / Plotly** – visualization
- **Jupyter Notebook** – interactive data analysis
- **Geopandas / pycountry / geopy** – for country mapping (if used)

## 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/antoniomarroffino/netflix-data-analysis.git
   cd netflix-data-analysis
   ```

2. Open the notebook:
   ```bash
   jupyter notebook progetto.ipynb
   ```

3. Make sure to have the required libraries installed:
   ```bash
   pip install pandas matplotlib seaborn plotly geopandas pycountry geopy
   ```

> Some libraries such as `geopandas` may require additional system dependencies.

## ✅ Project Status

✔️ Completed in 2024  
🔒 No further development planned

## 👤 Author

**Antonio Marroffino**
- GitHub: [github.com/antoniomarroffino](https://github.com/antoniomarroffino)
- LinkedIn: [linkedin.com/in/antonio-marroffino](https://www.linkedin.com/in/antoniomarroffino)
