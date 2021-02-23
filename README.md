# Machine Learning ‘on the rocks’ 🥃

[Whiskey Dataset ~ K-Means Clustering, Logistic Regression & EDA]

## Introduction

The project’s domain relies on the most popular liquor in the world —  **Whiskey**. A dark spirit coming from a great variety of grains, distilled throughout the world and arriving at quite a number of styles (Irish, Scotch, Bourbon etc) [1]. Scotland, Ireland, Canada & Japan are among the famous exporters and on an international scale, the global production almost reaches the level of $95m revenue [2].

## Scope
The main scope, hereof, is to introduce in a… ‘companionable’ way, how helpful can the **Clustering Algorithms** prove to be, anytime we need to find patterns in a (large) dataset. Apart from being a powerful expansion of the standard Exploratory Data Analysis (EDA), it is often very beneficial to try, before using Supervised Machine Learning (ML) models. A predictive case of the latter (**Logistic Regression**) is also implemented at the end.

## Scenario

The Data Corp I work for, accepted a new project: assisting a renowned Whiskey Vendor to diversify. That is, to bring in light which whiskey varieties are better sold and with that in mind, make the appropriate mergers / acquisitions, to boost sales contextually. The main handicap, though, is that the Vendor does not possess any Sales data from the competitors (aka prospective acquisition targets). But:

*How about using whiskey-related data including any attributes (i.e. age, taste, type, price and so on), categorising them in a meaningful for the Vendor way and finally guide them on what specific bottles they should invest in?*

## Roadmap

1. Set up the **environment** to run the code.
2. Perform **EDA** using Numpy, Pandas & a number of additional Python libraries.
3. Reveal additional data patterns, by fitting a **K-Means Clustering** algorithm to the dataset. 
4. Using the now labeled dataset (clusters = labels), implement a Multiclassification technique — **Logistic Regression** — to make predictions on new listings (whiskies).

## Profound Findings

#1: The Vendor may choose to boost the sales of the Blended Malts. That way, they may achieve bigger sales, due to the popularity of this whiskey type and as a result enjoy higher profits. Yet, a basic condition is violated - preserve the whiskey variety and not just sell specific bottles.

#2: So, instead of recommending Blended (and only) bottles and by applying K-Means Clustering Algortithms, we revealed a clearer indication of what whiskey types foster the `rating` (and sales, as well).

* The new Clusters distinguish themselves better.
* Cluster #1 is way better when it comes to terms of `rating`, while also including Single Malt Scotch {#321}, Blended Scotch Whisky {#33} and Blended Malt Scotch Whisky {#9} —  thus, variety guaranteed!
* The analysis takes into account more features (`rating`, `alcohol`, `age`) than the initially attempted (`rating`), proving the point that clustering promotes a more comprehensive separation of data, deriving from signals of more components.



<img src="/Users/gerasimosplegas/Desktop/Machine-Learning-Whiskey-Dataset/Plots/scatter_plot3d@2x.png" style="zoom:50%;" />

<img src="/Users/gerasimosplegas/Desktop/Machine-Learning-Whiskey-Dataset/Plots/scatter_plot@2x.png" alt="mk" style="zoom:50%;" />

## Additional Analysis
There is quite a number of additional analyses to be performed, expanding this one. You are welcome to extend and shape yours in any direction you may prefer. For instance, you can additionally try and fit a different Supervised ML model and predict either the same independent variable (`cluster`) or another one (i.e. `price`).

[*It stands as an independent analysis in an effort to enhance my ability to communicate results, reason about data statistically and stay motivated to continuously implement newly aquired skills & capabilities, so as to enrich my portfolio of data science-oriented projects*]