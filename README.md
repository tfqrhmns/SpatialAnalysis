# Spatial Analysis of Parking Attendants in Bandung (2021)

This project maps the last known distribution of official parking attendants (juru parkir) in Bandung based on historical data, aiming to support the city’s effort in addressing informal parking issues in 2025.

## Context

As of 2025, the city of Bandung faces increasing challenges due to the rise of informal, unregistered parking attendants. The available data from 2015 to 2021 offers insight into historical hotspots that may remain problematic today.

This analysis provides a spatial baseline for urban authorities to validate ground conditions, improve regulation, and minimize public disruption caused by illegal parking.

# Dataset

- CSV file of parking locations (street names only, 2015–2021)
- Boundary shapefile of Bandung City (2025 administrative zones)
- Results photos

# Tools Used
- ArcMap 10.4
- Microsoft Excel
- Kernel Density Estimation (KDE)

## 🔍 Methodology

1. Cleaned and standardized raw address data
2. Geocoded each location to get latitude & longitude with google earth
3. Projected data to UTM Zone 48S
4. Performed Kernel Density Analysis with a 300-meter search radius
5. Visualized results and interpreted urban clustering

# Findings

- Historical hotspots include Braga, Alun-Alun, and Pasar Baru areas
- Likely targets for informal parking activity in 2025
- Useful for city audits, complaint follow-ups, and traffic planning

# Limitations

- Data only in 2021  
- Cannot distinguish official vs. illegal attendants  
- No temporal or shift-based data available

# Futue Work

- Conduct ground truthing or field verification
- Combine with community complaint data
- Automate live dashboard of parking operations
- 
# Contact
Developed by [Muhamad Taufiq Rahman Somantri]  
For portfolio and public service exploration  
Email: muhamadtaufiqrahmansomantri@gmail.com
