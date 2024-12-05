# Data Dictionary

This document provides detailed descriptions of the variables used in the project.

## User Information

| Variable Name       | Data Type   | Description                                    | Possible Values/Units          |
|---------------------|-------------|------------------------------------------------|--------------------------------|
| `user_id`           | Integer     | Unique identifier for the user                | Unique ID (e.g., 1, 2, 3)      |
| `name`              | String      | Name of the user                              | Any text                       |
| `sex`               | Categorical | Biological sex of the user                    | `Male`, `Female`, `Other`      |
| `birthdate`         | Date        | User's date of birth                          | `YYYY-MM-DD` format            |
| `age`               | Integer     | Age of the user (calculated from birthdate)   | Positive integers (e.g., 18)   |
| `weight`            | Float       | Weight of the user                            | Kilograms (e.g., 65.5)         |
| `height`            | Float       | Height of the user                            | Centimeters (e.g., 170.0)      |
| `bmi`               | Float       | Body Mass Index of the user (calculated)      | Numeric value (e.g., 22.5)     |

## Product Information

| Variable Name       | Data Type   | Description                                    | Possible Values/Units          |
|---------------------|-------------|------------------------------------------------|--------------------------------|
| `upc`               | Integer     | Unique product code (barcode)                 | Numeric (e.g., 1234567890)     |
| `product_name`      | String      | Name of the product                           | Any text (e.g., "Snack Bar")   |
| `calories_per_serving` | Float    | Calories in one serving                       | Kilocalories (e.g., 150.0)     |
| `sugars`            | Float       | Sugar content in one serving                  | Grams (e.g., 12.0)             |
| `sodium`            | Float       | Sodium content in one serving                 | Milligrams (e.g., 200.0)       |

---

## Model Outputs

| Variable Name       | Data Type   | Description                                    | Possible Values/Units          |
|---------------------|-------------|------------------------------------------------|--------------------------------|
| `predicted_bmi`     | Float       | Predicted BMI for the user                    | Numeric value (e.g., 22.5)     |
| `recommended_products` | List[String] | List of recommended products for the user   | List of product names          |
