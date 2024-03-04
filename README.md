# Unsupervised Sentiment Analisys



***STATUS:*** **Incomplete**


## Project Objectives:

Fred has launched an advertising campaign where, over a period of 20 days, he is checking the number of clicks on links of different colors. In total, Fred has 30 colors, and he wants to know if there is a color that will provide more clicks than blue. It's not that simple, as Fred is not skilled at interpreting results correctly and is unsure about which clicks were intentional and which occurred randomly.

## Business Objectives: 

1. Processing and analysis of data on online clicks.
2. Determining the average number of clicks for each color.
3. Defining the null and alternative hypotheses.
4. Finding the probability of random clicks.

## Research Conclusion:

The analysis revealed that there are two contenders for the title of the most popular color among users: Ultramarine and Navy. However, as Fred points out, there is a possibility of random clicks. Based on this, the following null hypothesis was defined: Ultramarine does not differ from Navy in terms of the number of clicks due to the randomness of such clicks, which, according to the p-value results through the chi-square test (Pearson's Coefficient), exceeded the significance level of 0.05.

<img src="https://i.imgur.com/FnCy1LP.png" alt="p-value"/>

As a result, there is a 25% chance that a large number of clicks are random, and a 95% chance that the result is a consequence of the created conditions. Fred can consider that Ultramarine and Navy colors may be equally good to surpass the Blue color.

## Application of Research Results:

The outcome of the study was an understanding of the concept of p-value, which helped determine whether my hypotheses were correct. The p-value is a frequently encountered measure in practice and serves as a useful tool for determining the probability of obtaining observed results assuming that the null hypothesis is true, or the probability of error in case of rejecting the null hypothesis.

## Technical Features of the Project:

The distribution of the number of clicks was not normal, which is why the algorithm for calculating through the z-score had to be discarded, and the chi-square test, also known as Pearson's Coefficient, had to be used. This coefficient measures the difference between expected and observed values of the experiment, indicating that we are not dependent on the distribution.

## Project Tools

- Python
- Pandas
- Numpy
- scipy.stats
