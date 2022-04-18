# FinTech_Challenge_3
Bitcoin exchange arbitrage project

The basic idea of this project is to determine whether or not there are aribtrage opportunities between different marketplaces trading the same asset.

We first bring in and clean-up data so that it can be worked on

Next, we map out the data so we can visually see where prices might differ the most on a specific date and to observe trends over time

Then, we use the intra-day prices to calculate out a series of data where we see potential profits to be made that are > 1% to take into account some theoretical fees

Since we don't know what the exact trading fee would be, we calculate potential profit on these trades given no trading fees

Lastly, we map out these profits as a box and line plot for a single day in each of the early, middle, and late sections of the given data.


Technologies
Python 3.7.11 pandas 1.3.4, mathplotlib 0.1.2, CSV

Installation Guide
Make sure you have the dependencies installed

Contributors
Berkeley FinTech Extension Course for the starer code https://bootcamp.berkeley.edu/fintech/
Gabriel Paganin filled in the gaps gpaganin@berkeley.edu www.linkedin.com/in/gabriel-paganin
