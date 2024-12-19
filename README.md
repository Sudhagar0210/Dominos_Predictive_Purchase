# Dominos - Predictive Purchase Order System

## Project Overview
The **Dominos - Predictive Purchase Order System** aims to optimize the ingredient ordering process by accurately predicting future sales. By leveraging historical sales data and ingredient information, this project develops a predictive model that helps Dominos ensure optimal stock levels, minimizes waste, and prevents stockouts.

## Table of Contents
- [Skills Acquired](#skills-acquired)
- [Problem Statement](#problem-statement)
- [Business Use Cases](#business-use-cases)
- [Approach](#approach)
- [Results](#results)
- [Installation](#installation)

## Skills Acquired
- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- Time series forecasting
- Predictive modeling
- Business decision making
- Real-world application of data science

## Problem Statement
Dominos aims to optimize the process of ordering ingredients by predicting future sales, ensuring that it has the right amount of ingredients in stock, minimizing waste, and preventing stockouts.

## Business Use Cases
- **Inventory Management**: Ensuring optimal stock levels to meet future demand without overstocking.
- **Cost Reduction**: Minimizing waste and reducing costs associated with expired or excess inventory.
- **Sales Forecasting**: Accurately predicting sales trends to inform business strategies and promotions.
- **Supply Chain Optimization**: Streamlining the ordering process to align with predicted sales and avoid disruptions.

## Approach
1. **Data Preprocessing and Exploration**
   - Data Cleaning
   - Exploratory Data Analysis (EDA)
2. **Sales Prediction**
   - Feature Engineering
   - Model Selection
   - Model Training
   - Model Evaluation
3. **Purchase Order Generation**
   - Sales Forecasting
   - Ingredient Calculation
   - Purchase Order Creation

## Results
- **Accurate Sales Predictions**: The model ARIMA successfully predicted pizza sales for the upcoming week, with a Mean Absolute Percentage Error (MAPE) of **[1.8163972880345898]**.
- **Comprehensive Purchase Order**: A detailed purchase order was generated, listing the required quantities of each ingredient based on the predicted sales.

### Purchase Order(This is for one week forecast prediction)
| Ingredient                               | Quantity        | Unit   |
|------------------------------------------|-----------------|--------|
| Barbecued Chicken                        | 5404.165210     | grams  |
| Red Peppers                              | 11341.551998    | grams  |
| Green Peppers                            | 8030.393870     | grams  |
| Tomatoes                                 | 34984.718341    | grams  |
| Red Onions                               | 54797.556512    | grams  |
| Barbecue Sauce                           | 1801.388403     | grams  |
| Bacon                                    | 19992.004764    | grams  |
| Pepperoni                                | 24192.916429    | grams  |
| Italian Sausage                          | 343.954622      | grams  |
| Chorizo Sausage                          | 1719.773109     | grams  |
| Brie Carre Cheese                        | 260.292444      | grams  |
| Prosciutto                               | 260.292444      | grams  |
| Caramelized Onions                       | No Need         | grams  |
| Pears                                    | 86.764148       | grams  |
| Thyme                                    | 43.382074       | grams  |
| Garlic                                   | 17939.075392    | grams  |
| 'Nduja Salami                            | 1586.898271     | grams  |
| Pancetta                                 | 2380.347406     | grams  |
| Friggitello Peppers                      | 396.724568      | grams  |
| Chicken                                  | 44707.738829    | grams  |
| Artichokes                               | 8194.256191     | grams  |
| Spinach                                  | 21045.422036    | grams  |
| Jalapeno Peppers                         | 3770.816452     | grams  |
| Fontina Cheese                           | 3919.292301     | grams  |
| Gouda Cheese                             | 2940.000000     | grams  |
| Mushrooms                                | 26131.595750    | grams  |
| Asiago Cheese                            | 4170.001706    | grams  |
| Alfredo Sauce                            | 932.350127      | grams  |
| Pesto Sauce                              | 3897.174211     | grams  |
| Mozzarella Cheese                        | 10227.712828    | grams  |
| Provolone Cheese                         | 759.896595      | grams  |
| Smoked Gouda Cheese                      | 759.896595      | grams  |
| Romano Cheese                            | 759.896595      | grams  |
| Blue Cheese                              | 759.896595      | grams  |
| Ricotta Cheese                           | 3985.003095     | grams  |
| Gorgonzola Piccante Cheese              | 3188.002476     | grams  |
| Parmigiano Reggiano Cheese              | 7970.006190     | grams  |
| Kalamata Olives                          | 2242.598080     | grams  |
| Feta Cheese                              | 7530.556884     | grams  |
| Beef Chuck Roast                         | 7980.000000     | grams  |
| Green Olives                             | 3263.109241     | grams  |
| Sliced Ham                               | No Need         | grams  |
| Pineapple                                | 4641.998311     | grams  |
| Capocollo                                | 50316.976159    | grams  |
| Goat Cheese                              | 11504.280161    | grams  |
| Oregano                                  | 1463.200337     | grams  |
| Calabrese Salami                         | 11121.934742    | grams  |
| Eggplant                                 | 2212.228830     | grams  |
| Zucchini                                 | 4630.572932     | grams  |
| Sun-dried Tomatoes                       | 1606.910550     | grams  |
| Plum Tomatoes                            | 3090.392321     | grams  |
| Cilantro                                 | 2300.816452     | grams  |
| Corn                                     | 15338.776347    | grams  |
| Chipotle Sauce                           | 4601.632904     | grams  |
| Anchovies                                | 2943.868861     | grams  |
| Genoa Salami                             | 6260.604609     | grams  |
| Prosciutto di San Daniele                | 1959.417096     | grams  |
| Arugula                                  | 839.750184      | grams  |
| Coarse Sicilian Salami                   | 5535.225825     | grams  |
| Luganega Sausage                         | 2767.612913     | grams  |
| Onions                                   | 1383.806456     | grams  |
| Soppressata Salami                       | 4896.461505     | grams  |
| Peperoncini verdi                        | 1412.869703     | grams  |
| Thai Sweet Chilli Sauce                  | 1260.000000     | grams  |

## Installation
To run this project, ensure you have Python installed. You can install the required libraries using pip:

