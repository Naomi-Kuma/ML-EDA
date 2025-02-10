# Gen Z Dating App Data

## Overview
This dataset contains information on Gen Z dating app users. It includes demographic details, app preferences, and usage patterns.

## Data Cleaning Steps
- Removed duplicate rows.
- Standardized categorical values (e.g., fixed case inconsistencies).
- Handled missing values (filled categorical with mode, numerical with mean).
- Detected and removed outliers using the IQR method.

## Columns Description
| Column Name | Data Type | Description |
|-------------|-----------|-------------|
| user_id | int | Unique identifier for each user |
| gender | object | Gender of the user (male, female, other) |
| age | int | Age of the user |
| location | object | User city or region |
| dating_app_used | object | Name of the dating app(s) used |
| frequency | int | How often the user engages with dating apps |
| relationship_status | object | User current relationship status |

## Usage
This dataset can be used for:
- Analyzing dating app preferences among Gen Z.
- Identifying trends in dating behavior.
- Predicting engagement with dating apps.

## GitHub Versioning
- Initial dataset uploaded.
- Cleaned dataset committed as `Cleaned_GenZ_DatingApp_Data.csv`.

## Contributors
- Naomi
