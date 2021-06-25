# HBD Resale Prices Prediction Model App

<!-- ABOUT THE PROJECT -->

## About The Project
The goal of the project is to analyse resale housing prices (Singapore HDB) with the relationship of features and amenities available in a 2km radius. A linear regression and random forest were used to looked at the drivers of HDB resale prices.

The size of the unit, lease date, and location appear to be consistently the most important drivers of HDB resale prices.

### Future Considerations:
- Some of the amenities might not have been built when the flat were sold. A more accurate method is to account the nearest distance to amenities and the number of amenities at the year it is built.
- Account for number of BTOs/ New Flats offered each year

## Built With
 - sklearn
 - SHAP
 - streamlit

## Data
Data.gov.sg
- HDB resale prices
- Parks
- Supermarkets
- Hawkers
- MRT

Wiki (web scrape)
- Schools
- Shopping Malls

OneMap.sg
- Map coordinates


## Quick Start

Run steamlit app locally
```
// Install streamlit
pip install streamlit

// Run App
streamlit run prediction_app.py
```

## Future Development Ideas
- More features
- Private housing prediction

## Credit is where credit due
- https://medium.com/@michael.wy.ong/web-scrape-geospatial-data-analyse-singapores-property-price-part-i-276caba320b
- https://medium.com/@seinchyi/machine-learning-for-singapore-resale-hdb-pt-1-data-preparation-8cdc2df8e24f
