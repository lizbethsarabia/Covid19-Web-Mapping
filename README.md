# WA COVID-19 Case Rate Map

This project is an interactive web map displaying **cumulative COVID-19 case rates (per 10,000 people)** for every county in Washington State as of **October 25, 2021**. The map is built using **Mapbox GL JS** and uses the dataset provided in class:  
`wa-covid-data-102521.geojson`.

## Features
- Choropleth map colored by **casePer10k**
- Hover interaction displaying county name and case rate
- Custom legend matching the color steps
- Correct zoom and center to show all Washington counties

## Data Attributes
The GeoJSON file includes the following fields:
- **name** — County name  
- **casePer10k** — Cumulative COVID-19 cases per 10k  
- **deathPer10k** — Cumulative COVID-19 deaths per 10k  
- **fullyVaxPer10k** — Fully vaccinated people per 10k  

This map visualizes **casePer10k**.

view by visiting 
[link](https://github.com/lizbethsarabia/Covid19-Web-Mapping/blob/main/index.html)

## Technologies Used
- HTML / CSS  
- JavaScript  
- Mapbox GL JS  
- GeoJSON  

## Credits
- COVID case & death data: The New York Times  
- Vaccination data: Washington State Department of Health  
- Population estimates: Washington State Office of Financial Management  
- County boundaries: U.S. Census Bureau

