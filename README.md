# Google Play Store Data Analysis (EDA)

## Project Overview

This project performs Exploratory Data Analysis (EDA) on the Google Play Store dataset to uncover trends in app categories, ratings, installs, pricing models, and user behavior.

The objective is to clean real-world messy data and extract meaningful business insights from it.

---

## Dataset Information

* Source: Google Play Store public dataset
* Records: 10,000+ apps
* Features include:

  * App Name
  * Category
  * Rating
  * Reviews
  * Size
  * Installs
  * Type (Free/Paid)
  * Price
  * Content Rating
  * Android Version

---

## Data Cleaning & Preprocessing

The dataset contained multiple inconsistencies:

* Removed duplicate records
* Converted `Installs` column to numerical format
* Cleaned `Size` column (handled MB/K variations)
* Processed `Price` column (removed `$` symbol and converted to float)
* Handled missing values logically
* Cleaned Android version ranges

---

## Exploratory Data Analysis

The following analyses were performed:

### Category Analysis

* Distribution of apps across categories
* Category-wise total installs
* Average rating per category

### Rating Analysis

* Rating distribution
* Outlier detection using boxplots
* Relationship between rating and installs

### Free vs Paid Apps

* Comparison of installs
* Price vs rating relationship
* Market share distribution

### Content Rating Analysis

* Target audience segmentation
* Popularity trends by age group

---

## Key Insights

* Free apps dominate total installs compared to paid apps.
* Game category has the highest number of installs.
* Most apps are targeted toward "Everyone" content rating.
* Higher-priced apps do not necessarily guarantee higher ratings.
* Majority of apps fall in the 4.0–4.5 rating range.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Conclusion

This project demonstrates real-world data cleaning, feature transformation, and business-oriented data analysis.
It highlights how exploratory analysis can uncover market trends and user behavior patterns in mobile applications.

