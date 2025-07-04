# World-Carbon-Emission-Analysis-using-Clustering

## Objective
To identify country clusters based on CO₂ emissions, CO₂ productivity, and renewable energy supply, and assess the relationship between cluster patterns and the presence of carbon trading systems — in alignment with global climate goals and the Paris Agreement.

## Dataset
All dataset were sorced from the Organisation for Economic Co-operation and Development (OECD) https://www.oecd.org/. The following variables were used in the clustering analysis: 
- **REF_AREA :** Country code in 3-letter uppercase format
- **Reference Area :**	Country name
- **TIME_PERIOD :**	Year of the data
- **productivity :**	Real GDP generated per unit of CO₂ emission (USD/kg)
- **emissions :**	Total CO₂ emissions (in million metric tons)
- **renewable_supply :**	Portion of renewable sources in Total Energy Supply (TES)


## Tools & Methods
**Language & Tools:**
- Python (Google Colaboratory)
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

**Clustering Methods Applied:**
- K-Means Clustering  
- Agglomerative Hierarchical Clustering  
- DBSCAN  
- Gaussian Mixture Model (GMM)
