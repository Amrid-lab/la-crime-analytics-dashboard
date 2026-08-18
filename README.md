# 🏙️ Los Angeles Crimes Analysis Application 💥
# An R-Shiny Interactive Dashboard

![R](https://img.shields.io/badge/R-blue) ![Shiny](https://img.shields.io/badge/Shiny-red) ![Data Visualization](https://img.shields.io/badge/DataVisualization-green) ![GitHub](https://img.shields.io/badge/GitHub-rele)

## 📖 About

This application offers an in-depth exploration of crime data in Los Angeles,
providing a comprehensive analysis of trends, variations, and criminal 
patterns prevalent within this metropolis.
Its aim is to deliver a nuanced and contextualized understanding of 
the city's criminal landscape through interactive visualizations and 
data analysis tools.

## 📸 Project Screenshot
![DASHBOARD](https://github.com/doriankari/RshinyApp/assets/146330254/7e148bd2-2c4e-4fac-a900-4d62fbc1d170)

## ✨ Features

- 📊 Interactive data visualization with R-Shiny
- 🎯 Dynamic data filtering and date range selection
- 📈 Comprehensive crime statistics and trends analysis
- 🗺️ Multiple visualization types (charts, maps, histograms)

## 🛠️ Technologies

- R (version 3.6.0 or higher)
- RStudio
- Shiny Framework
- Data Visualization packages (ggplot2, leaflet, etc.)

## 📦 Prerequisites

### Data Source
[Los Angeles Crime Data](https://data.lacity.org/Public-Safety/Crime-Data-from-2020-to-Present/2nrs-mtv8/about_data)

## 🚀 Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/doriankari/RshinyApp.git
   cd RshinyApp
   ```

2. Download the crime dataset from the LA City website

3. Create subfolders:
   ```sh
   mkdir www   # for images
   mkdir data  # for datasets
   ```

4. Install Shiny and required packages:
   ```R
   install.packages(c("shiny", "ggplot2", "dplyr", "shinydashboard", "leaflet"))
   ```

5. Update the data path in `global.r` to point to your data folder

6. Run the application:
   ```R
   shiny::runApp("app.R")
   ``` 

## 📁 Application Structure

- `app.R`: Server and UI definitions
- `global.R`: Global variables and data loading
- `Packages.R`: Dependencies
- `www`: Images and static assets

## 📝 Usage

Navigate through the tabs to access different analyses.
Utilize dropdowns and buttons to customize your data exploration experience.
Note: Please ensure your date range selection falls between 2020-01-01 and 2023-10-30 for accurate statistics.

## 📄 Project Information

- 🎓 Developed as part of a data science project
- 📅 Data covers period from 2020 to present

## 📞 Contact

- 👤 [My LinkedIn](https://www.linkedin.com/in/dorian-amri-8685a2177/)
- 📧 [Email](mailto:amri.dk@hotmail.com)
- 🔗 [Project Repository](https://github.com/doriankari/RshinyApp)

## 📜 License
This project is open source and available for educational purposes.
