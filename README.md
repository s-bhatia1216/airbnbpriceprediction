# Predicting Airbnb Listing Prices

This project aims to predict the prices of Airbnb listings in New York City using various machine learning models. The project follows the machine learning life cycle, including data preprocessing, model training, evaluation, and optimization.

## Project Overview

### Data
The dataset used in this project is the Airbnb NYC listings dataset, which contains information about various Airbnb listings, including features such as the description, host information, property details, review scores, and more.

### Objectives
- Predict the price of Airbnb listings.
- Compare the performance of different machine learning models.
- Optimize the models to improve their predictive performance.

### Features
- `name`: Name of the listing
- `description`: Description of the listing
- `neighborhood_overview`: Overview of the neighborhood
- `host_name`: Name of the host
- `host_location`: Location of the host
- `host_about`: Information about the host
- `host_response_rate`: Host's response rate
- `host_acceptance_rate`: Host's acceptance rate
- `host_is_superhost`: Whether the host is a superhost
- `host_listings_count`: Number of listings by the host
- `room_type`: Type of room
- `accommodates`: Number of guests accommodated
- `bathrooms`: Number of bathrooms
- `bedrooms`: Number of bedrooms
- `beds`: Number of beds
- `amenities`: List of amenities
- `price`: Price of the listing (target variable)
- `minimum_nights`: Minimum number of nights
- `maximum_nights`: Maximum number of nights
- `review_scores_rating`: Rating score
- `review_scores_cleanliness`: Cleanliness score
- `review_scores_checkin`: Check-in score
- `review_scores_communication`: Communication score
- `review_scores_location`: Location score
- `review_scores_value`: Value score
- `instant_bookable`: Whether the listing is instantly bookable
- `calculated_host_listings_count`: Calculated host listings count
- `reviews_per_month`: Number of reviews per month

### Models
- **Linear Regression (Ridge Regression)**
- **Decision Tree**
- **Random Forest**

### Results
- **Optimized Ridge Regression**: RMSE: 128.68, R²: 0.13
- **Optimized Decision Tree**: RMSE: 128.70, R²: 0.13
- **Optimized Random Forest**: RMSE: 116.45, R²: 0.29

### Conclusion
The Random Forest model demonstrated the best performance, achieving the lowest RMSE and the highest R² score. 
Future work could involve advanced feature engineering, incorporating additional data sources, and experimenting with other machine learning algorithms to evaluate and resolve the high RMSE and low R^2 values. 

## Repository Structure
- `data/`: Contains the Airbnb NYC listings dataset.
- `notebooks/`: Jupyter notebooks used for data preprocessing, data exploration, model training, and evaluation.
- `README.md`: Project description and overview.

## How to Run
1. Clone the repository.
2. Install the required dependencies.
3. Run the Jupyter notebooks or scripts to train and evaluate the models.

## Dependencies
- Python 3.9
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter

---

For any questions or contributions, please feel free to open an issue or submit a pull request.
