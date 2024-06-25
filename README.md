> [!TIP]
> Read this first. 

# A Permutation Test to assess the statistical significance of food consumption differences using Python :test_tube:

Permutation tests are non-parametric statistical tests that assess the significance of an observed effect by comparing it to the distribution of effects generated by randomly shuffling the data.

## The dataset

`food_consumption.csv` contains data on several countries' food consumption per food category and their respective CO2 emissions. We are interested in average consumption per food category.

## The case study 

In this case study, we observed that the average **consumption** of poultry (21.22) across all countries (130 in this dataset) seems to be higher than the average consumption of fish (17.29). 

But is this observed result **statistically significant**? A **permutation test** will help us assess it.

*H0 = avg poultry consumption = avg fish consumption*
*H1 = avg poultry consumption > avg fish consumption*

## The results :mag:

- Through the permutation test, we are able to **reject the null hypothesis** that the average poultry consumption is equal to the average fish consumption.

- This means that the **our initially observed result (average poultry consumption is higher than fish consumption) is statistically significant**.