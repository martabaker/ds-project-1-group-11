# Group 11: Car Crashes in Monroe County, Indiana
This project is an exploratory data analysis into a Kaggle dataset of car crashes in Monroe County, Indiana for the years 2003 to 2015.

## Questions
1. What days of the week are people more likely to get into accidents? Does this change based on month?
2. What types of injuries are most likely to occur? Are more severe injuries likely to occur in one car accidents or multi-car accidents?
3. What time of day are people most likely to get into accidents?
4. Maps: Where are accidents most likely to occur?
5. Regression: Are there any linear relationships within the data and can we use the data to predict when accidents might occur? 

## Conclusions
- Fridays during the afternoon rush hour (around 3pm) have the most crashes
- Overall, afternoon rush hour (3pm to 5pm) have the most crashes while early morning crashes have the least accidents (before 6 am)
- Most crashes were 2-car collisions and most accidents had no known injuries or no injuries
- The data has limited predictive capabilities, if any

## Future Work
- Analyze the Primary Factor data to determine if there was a relationship between the Primary Factor for accidents and either the injuries sustained or the type of collision
- Compare this dataset with one where people live to determine if people are more likely to get in collisions close to where they live
- Define injury types more granularly
- Adjust the Random Forest Regressor and Test-Train Split to better train the model
- Create a Random Forest Classifier model because that would likely be a better predictor than the Random Forest Regressor given the data available

## Authors
ivan-valverde: Data Cleaning, Lead on presentation\
KBerry01: Data Cleaning, Questions 1 and 2\
MoonSplosion: Data Cleaning, Question 3\
martabaker: Data Cleaning, Map, Regressions

## Works Cited
Harold, Tosin. "Enhancing Correlation Matrix Heatmap Plots with p-values in Python." Medium, 23 Jan. 2020, tosinharold.medium.com/enhancing-correlation-matrix-heatmap-plots-with-p-values-in-python-41bac6a7fd77.\
Jackson, Divakarr. "Car Crash Dataset." Kaggle, Kaggle, www.kaggle.com/datasets/jacksondivakarr/car-crash-dataset/data?select=monroe+county+car+crach+2003-2015.csv.\
Stack Overflow. "LabelEncoder vs OneHot Encoding in Random Forest Regressor." Stack Overflow, 14 Jan. 2021, stackoverflow.com/questions/65749305/labelencoder-vs-onehot-encoding-in-random-forest-regressor.
