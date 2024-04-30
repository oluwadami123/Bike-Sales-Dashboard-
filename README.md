# Bike-Sales-Dashboard

## Project Overview 

The purpose of this project is to uncover insights and trend of cutomer behaviours on the purchasing power of bikes based on their Monthly Income, Commute Distances, and Age. All these factors can be very useful in uncovering insights of how and why cutomers purchased a bike or not. We can also filter such factors  based on their Marital Status, Education, and Region.

## Data Sources

The dataset used was from kaggle, [click]() here to access it. The dataset contain one sheet with 14 fields and over 1000 records. 

You can view this image below:

![Initial column](https://github.com/oluwadami123/Bike-Sales-Dashboard-/assets/105118910/d15fd394-12da-439f-9018-0aad09cc5c15)

After:
![Columns](https://github.com/oluwadami123/Bike-Sales-Dashboard-/assets/105118910/c384ccd9-8b37-4b2b-96db-bc32022a1505)


## Tools 

Excel was used for the data preparation, analysis, and for the dashboard. I created a new column(Age Brackets) from the initial Age column using the IFs formula, 

I classified the ages into three category which are:
1. Adolescence( 0 years - 29 years)
2. Middle Age( 30 years - 49 years)
3. Old( 50 years and above)

``` Excel
=IF(L2>=50,"Old",IF(L2>=30,"Middle Age",IF(L2<30,"Adolescence","Invalid")))
```

I replaced the single letters in the Marital Status( S - Single, and M- Married), and changed the single letters in the Gender column( F- Female, and M- Male) for 

better readability.

You can view the image below:

![Columns](https://github.com/oluwadami123/Bike-Sales-Dashboard-/assets/105118910/197908af-5a9d-4c57-9d14-fc983accf165)


## Data Cleaning/Preparation

For Data cleaning and preparation.
1. Data Loading and Preparation
2. Handled Missing Values
3. Checked for Duplicates
4. Data Formatting

## Explortatory Data Analysis (EDA)

1. The Average Income per Purchase( This is to check the customers with high income and low income if they actually purchased a bike or not).
2. Commute Distances(This is to check for those who live very far from work or school or from their respective places if they actually purchased a bike ).
3. Customers Age Brackets(This is to check the classified age group that purchased more bikes)


## Result/Findings

The Average Income per Purchase:

![Income Per Purchase](https://github.com/oluwadami123/Bike-Sales-Dashboard-/assets/105118910/0a71e79b-cc73-4da7-b493-b3b6ae1d0566)

From this image, we could see that the females and males with the highest income purchased more bikes than those with lower income.

Commute Distance:

![Customer Commute](https://github.com/oluwadami123/Bike-Sales-Dashboard-/assets/105118910/d749d79d-f44f-4976-a4a8-934f8f00e8ff)

From the chart, it is clear that those who lived close purchased more bikes than those who lived far.

Customers Age Brackets:

![Customer Age](https://github.com/oluwadami123/Bike-Sales-Dashboard-/assets/105118910/e3674864-35ce-4fee-8444-cceb15d5ab6d)

From this chart, customers within the middle age group purchased more bikes that the other age group

The Dashboard:

![Bike Sales Dashboard](https://github.com/oluwadami123/Bike-Sales-Dashboard-/assets/105118910/6b87db36-526f-4987-9ad7-676233965d0f)


