# Mobile App for Lottery Addiction

A medical institute that aims to prevent and treat gambling addictions wants to build a dedicated mobile app to help lottery addicts better estimate their chances of winning. The institute has a team of engineers that will build the app, but they need me to create the logical core of the app and calculate probabilities.

For the first version of the app, they want us to focus on the [6/49 lottery](https://en.wikipedia.org/wiki/Lotto_6/49) and build functions that enable users to answer questions like:

- What is the probability of winning the big prize with a single ticket?
- What is the probability of winning the big prize if we play 40 different tickets (or any other number)?
- What is the probability of having at least five (or four, or three, or two) winning numbers on a single ticket?

[The data set](https://www.kaggle.com/datascienceai/lottery-dataset) I use comes from the national 6/49 lottery game in Canada. It contains data for 3,665 drawings, dating from 1982 to 2018

### Summary of results

In this project, I have written 4 different functions for calculating the probability of winning the Canada 6/49 lottory, which are:
- one_ticket_probability() — calculates the probability of winning the big prize with a single ticket
- check_historical_occurrence() — checks whether a certain combination has occurred in the - Canada lottery data set
- multi_ticket_probability() — calculates the probability for any number of of tickets between 1 and 13,983,816
- probability_less_6() — calculates the probability of having two, three, four or five winning numbers
