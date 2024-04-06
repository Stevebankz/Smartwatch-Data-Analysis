# Smartwatch Data Analysis using Python 📊⌚️

There is a lot of competition among the brands in the smartwatch industry. Smartwatches are preferred by people who like to take care of their fitness. Analyzing the data collected on your fitness is one of the use cases of Data Science in healthcare. So if you want to learn how to analyze smartwatch fitness data, this article is for you. In this article, I will take you through the task of Smartwatch Data Analysis using Python.

## Dataset Information 📑

The dataset I am using for Smartwatch data analysis is publicly available on Kaggle. This dataset was initially collected from 30 female users of the Fitbit smartwatch. You can download the dataset from [here](insert_link_here).

## Let’s Analyze the Smartwatch Data ⌚️

The dataset has a “Calories” column; it contains the data about the number of calories burned in a day. Let’s have a look at the relationship between calories burned and the total steps walked in a day.

You can see that there is a linear relationship between the total number of steps and the number of calories burned in a day. Now let’s look at the average total number of active minutes in a day:

### Observations:

- 81.3% of Total inactive minutes in a day
- 15.8% of Lightly active minutes in a day
- On an average, only 21 minutes (1.74%) were very active
- and 1.11% (13 minutes) of fairly active minutes in a day

We transformed the data type of the ActivityDate column to the datetime column above. Let’s use it to find the weekdays of the records and add a new column to this dataset as “Day”.

## Conclusion 📝

So this is how you can analyze the data collected by a smartwatch about fitness using Python. Smartwatches are preferred by people who like to take care of their fitness. Analyzing the data collected on your fitness is one of the use cases of Data Science in healthcare. I hope you liked this article on Smartwatch data analysis using Python. Feel free to ask valuable questions in the comments section below.
