# Airbnb-Munich-Seattle
Analysis of Airbnb data as of July 2019

## Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

The code should run smoothly using Python versions 3.*. The libraries I used are all distributed via Anaconda. 

## Project Motivation<a name="motivation"></a>

For this project, I was interested in using Airbnb data from July 2019 on Airbnbs in Munich and Seattle to answer the following questions:

1. What is the impact of the Oktoberfest on Airbnb prices in Munich?

2. Which factors are the most relevant to explain the diffences in price between listings? Based on the listings' features is there a model that could be used to determine prices which are approximately the same as the acutal prices set by humans. (If yes, this model could be used for setting the prices of new listings.)

3. Do the review scores help in expaining the differences between prices?

4. Why is there so little explanatory value in the review scores? What do their distributions look like? Is there a systematic difference in customer ratings in different parts of the world (Munich vs. Seattle)?

5. Do customers evaluate the review categories independently or are the review scores highly correlated? Is there a systematic difference in customer ratings in different parts of the world (Munich vs. Seattle)?

## File Description <a name="files"></a>

There is one notebook available which includes the analysis I have performed.  The notebook also contains a function which can be used to clean, impute and engineer Airbnb data.

## Results<a name="results"></a>

My main findings are available in a [blog post](https://medium.com/@christian_sauka/airbnb-the-oktoberfest-and-other-very-unfunny-relationships-b3bcaaa2a75e) on Medium.

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Many thanks to Inside Airbnb Data for providing the data which enabled me to do this project! The data can be accessed [here](http://insideairbnb.com/get-the-data.html).
