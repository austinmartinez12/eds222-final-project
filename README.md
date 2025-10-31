---
editor_options: 
  markdown: 
    wrap: 72
---

# eds222-final-project

## What is the question you're going to investigate? What predictor and response variables will be relevant?

I have 2 questions I am considering:

1.  Are countries with a higher renewable energy percentage less
    affected by extreme weather events?

-   response: Extreme_Weather_Events - \# of recorded extreme weather
    events
-   predictor: Renewable_Energy_pct - renewable energy consumption

2.  Do countries that maintain or increase their forest area experience
    fewer weather disasters over time?

-   response: Extreme_Weather_Events - \# of recorded extreme weather
    events
-   predictor: Forest_Area_pct - percentage of land covered by forests

## Describe the dataset you're proposing to use. What is it? Where did you find it? What does each observation represent? If you're combining multiple datasets, how will you connect them? \*

link: <https://www.kaggle.com/datasets/adilshamim8/temperature/data>

My data set is from kaggle. It tracks environmental trends globally by
country from 2000-2024. It is designed to support analyses that explore
the interplay between climate variables, human activities, and
environmental changes. I am not combining data sets.

## Which statistical model do you propose to use? Refer to the descriptions on the [course website](https://eds-222-stats-f25.github.io/final-project.html#model-and-response-options). How does your response variable from above fit with the response characteristics of the statistical model? If the data need to be transformed, how would you do that? \*

I will use a Negative Binomial for both of them. Extreme_Weather_Events
works as the response because it is counts. I don't need to transform
it.
