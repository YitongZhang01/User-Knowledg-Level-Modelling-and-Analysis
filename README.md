# Using classification and clustering strategies to model and analyze the degree at which various factors impact user knowledge
## Our question
By modeling and analyzing factors that impact user knowledge, which factors can be used to most accurately predict knowledge levels of users?

## Methods
We created scatterplots of attribute pairings to visualize their relationships and determine which attributes impact UNS the most. Our next step will be to create a model using training data, using KNN (classification) and possibly k-means clustering if it is more effective. Then, we will use testing data to verify our model and test our chosen attributes.

We have chosen to analyze attributes PEG and LPR, which are both related to user exam performance. Although we initially thought attributes related directly to course materials would be the most useful attributes for prediction, we realized that PEG and LPR are nicely correlated and will provide a solid foundation for our model.

We will use a histogram to visualize our end results, as we expect our data points will form clusters on a scatterplot; a histogram will display the overlaps in cluster formation clearly.

## Expected Outcomes And Significance
We predict that PEG and LPR will create an accurate model for predicting knowledge levels of users. Since PEG and LPR are both related to user exam performance, our findings will place importance on maximizing user exam grades. This will involve strengthening user study strategies.

Our expected outcomes pose the following questions:

How is exam performance impacted by its own attributes?
With strengthened study strategies, can we expect user exam grades to improve at a specific rate?
Can class distribution help us consider outliers (eg. a student that studies well and receives a bad grade or one that doesn’t study well and receives a good grade) in further modeling?
