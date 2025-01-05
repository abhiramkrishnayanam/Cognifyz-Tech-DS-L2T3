# Cognifyz-Tech-DS-L2T3
# Feature Extraction and Creation for Restaurant Data

## Project Overview

This project focuses on enhancing the dataset by extracting additional features and creating new features that can improve the performance of machine learning models. The enhancements involve deriving useful information from existing columns, such as the length of the restaurant's name or address, as well as encoding categorical variables into new features such as "Has Table Booking" and "Has Online Delivery."

## Features Extracted and Created

### 1. **Length of Restaurant Name**
   - Extracted the length of the restaurant name as a new feature.
   - This feature provides additional context, which can be useful for machine learning algorithms to understand relationships between the restaurant's name length and other target variables.

### 2. **Length of Restaurant Address**
   - Extracted the length of the restaurant address as a new feature.
   - Similar to the restaurant name length, this feature might help models identify any relationship between the address length and restaurant popularity or other factors.

### 3. **Has Table Booking**
   - Created a binary feature to indicate whether a restaurant offers table booking.
   - Categorical variable encoding is used to mark whether the restaurant has table booking available (`1` for yes, `0` for no).
   - This feature may improve model predictions based on the availability of table booking.

### 4. **Has Online Delivery**
   - Created a binary feature to indicate whether the restaurant offers online delivery.
   - Categorical variable encoding is used to mark whether the restaurant offers online delivery services (`1` for yes, `0` for no).
   - This feature could reveal patterns related to restaurant popularity, especially with the growing trend of online food ordering.


## Conclusion

The newly created features provide additional insights that could enhance the performance of regression models or classification tasks. By encoding categorical variables and extracting numerical information from text columns, the dataset is now richer and better suited for predictive analysis.



