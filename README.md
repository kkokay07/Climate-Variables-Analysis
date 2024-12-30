
# Environment Hot and Cold Analysis

This notebook analyzes climate data for nine Indian states using various environmental parameters to classify them into hot and cold regions. It includes data visualization and statistical analysis of temperature, rainfall, humidity, elevation, and frost patterns.

## Features

- Temperature and humidity correlation analysis
- Annual rainfall distribution visualization  
- Elevation profile mapping
- Multi-variable radar chart analysis
- Frost days visualization
- Statistical clustering of states based on climate parameters

## Dependencies

The code requires the following Python libraries:
```
pandas 
numpy
scikit-learn
matplotlib
seaborn
```

Install dependencies using:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

## Usage

1. **Data Loading and Preprocessing**
   - The code loads climate data for 9 Indian states
   - Features include temperature, rainfall, humidity, elevation and frost days
   - Data is standardized for analysis

2. **Analysis and Visualization**
   - Creates scatter plots of temperature vs humidity
   - Generates bar charts for rainfall distribution
   - Maps elevation profiles
   - Produces radar charts for multi-variable analysis
   - Visualizes frost day patterns

3. **Outputs**
   - Saves visualizations as PNG files:
     - temperature_humidity_scatter.png
     - rainfall_distribution.png  
     - elevation_profile.png
     - radar_plot.png
     - frost_days.png
   - Exports data to climate_analysis.csv

4. **Classification**
   - Uses K-means clustering to group states
   - Performs PCA for dimensionality reduction
   - Classifies states into hot/cold regions

## Results

The analysis provides insights into:
- Climate patterns across different Indian states
- Temperature and humidity relationships
- Geographical elevation effects
- Rainfall distribution patterns
- Regional frost day occurrences

## Data Sources

The dataset includes climate data for:
- Uttarakhand
- Leh
- Rajasthan
- Gujarat
- Maharashtra
- Jharkhand
- Assam
- Kerala
- Tamil Nadu

## Note

The code is designed for educational and research purposes. Results should be validated against official meteorological data for practical applications.
## About the Author
**Dr. Kanaka K. K., PhD, ARS**  
Scientist  
School of Bioinformatics  
[ICAR-Indian Institute of Agricultural Biotechnology, Ranchi](https://iiab.icar.gov.in/)
> [Be like IIAB!:](https://www.researchgate.net/publication/379512649_ICAR-IIAB_Annual_Report-_2023) IIAB is like yogic center where all the sciences (Plant, Animal, Aquatic,Mibrobiology, IT) meet to address emerging issues in food production.

## 🔎 Spy on me
- [Google Scholar](https://scholar.google.com/citations?hl=en&user=0dQ7Sf8AAAAJ&view_op=list_works&sortby=pubdate)
- [GitHub: kkokay07](https://github.com/kkokay07)
- [ResearchGate](https://www.researchgate.net/profile/Kanaka-K-K/research)
- [Institute Website](https://iiab.icar.gov.in/staff/dr-kanaka-k-k/)
