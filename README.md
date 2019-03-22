# gov.lk.data.analysis
We analyse data from  http://www.data.gov.lk/  to get some insights for the betterment of the community of Sri Lanka. We provide an analytical report demonstrating our learnings from Data Science course. And along the way we take this as an opportunity to produce something useful for this country.

Specifically following areas are of interest,

1. Crimes per district 2010-2012. (http://www.data.gov.lk/dataset/crime-data-2010-2012)
2. Accomadation for tourists per district. (http://www.data.gov.lk/dataset/accommodation-information-tourists)
3. Population of district 2012. (http://www.data.gov.lk/dataset/population-district-census-years)
4. Employment by industrial sector. (http://www.data.gov.lk/dataset/employees-industrial-sector-2012)


# Hypothesis we proved

Popular tourism cities caused lot of crimes including

 1. Robbery (0.81)
 2. Dangeroud drugs (0.8)
 3. H.B. & Theft (0.74)
 4. Kidnapping (0.75)
 5. Offences with weapons (0.74)
 
Female employment in industrial sector relates to crimes like,

 2. H.B. & Theft (0.77)
 3. Hurt by knife (0.83).

# Techniques Used

 1. Visualization (heatmaps/ Geomaps/ boxplot/ histogram/ bar chart/ scatterplot)
 2. Missing value handling 
        Ex:- Population of Chilaw district
 3. Rollup data/ Feature engineering (Room count each hotels to District level)
 4. Data integration (merge datasets by District)
 5. Normalization (crime data normalized by population)
 6. Correlation analysis
 7. Normalization test
 8. Hypothesis testing (t-test)
 9. Linear regression (Ridge)
 10. Cross validation (K-fold)
