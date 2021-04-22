# AirBnB Price Prediction with Sentiment
## Machine Learning and Neural Network Modelling
---
AirBnB is a unique company in the hospitality industry that has been a major player for travel accommodations, 
allowing anyone in the world to start a business by hosting their homes to short and long term renters.
Ultimately, being an AirBnB host is being a business owner, and businesses want to maximize the revenue being generated. 
However, AirBnB does not have a metric to suggest adjustments in listing price to increase revenue. 
In this project, sentiment is used in prediction models to determine whether the feature is useful in predicting listing prices, 
subsquently answering whether higher sentiment is indicative of higher prices customers pay for accommodation/rent.
Having a feature that is predictive of listing price unrelated to the physical aspects of an AirBnB, such as sentiment, can be useful to:
- Adjust prices to stay competitive on the market
- Increase revenue if perceived value of the listing is higher than similar listings

The goal of this project is to apply Machine Learning and Neural Networks to predict listing price and determine whether sentiment is a useful feature.

---

## Packages & Libraries Used in Project
---
**Fundamentals**
- numpy
- seaborn
- pandas

**Plotting**
- matplotlib
- plotly

**Preprocessing**
- OneHotEncoder
- CountVectorizer
- MinMaxScaler
- StandardScaler
- PCA
- TextBlob (Sentiment Scoring)

**Machine Learning**
- RandomizedSearchCV
- LinearRegression
- RandomForestRegressor
- Pipeline
- cross_val_score

**Neural Network**
- tensorflow & keras
- Layers: Dense, Dropout, Embedding, LSTM, GRU, BatchNormalization
- Optimizers: Adam
- Callbacks: EarlyStopping

**Scoring**
- r2_score
