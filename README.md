# model_best_crops_Datacamp

### Create a multi-class classification model to predict the type of "crop" and identify the single most importance feature for predictive performance


### Problem description:
Measuring essential soil metrics such as nitrogen, phosphorous, potassium levels, and pH value is an important aspect of assessing soil condition. However, it can be an expensive and time-consuming process, which can cause farmers to prioritize which metrics to measure based on their budget constraints.

Farmers have various options when it comes to deciding which crop to plant each season. Their primary objective is to maximize the yield of their crops, taking into account different factors. One crucial factor that affects crop growth is the condition of the soil in the field, which can be assessed by measuring basic elements such as nitrogen and potassium levels. Each crop has an ideal soil condition that ensures optimal growth and maximum yield.

There is a need to build a model that identify the type of crop and the most important feature. The focus in the project is on logistic regression and assessing performance with F1 score.

### Data 
The data was provided in Datacamp and was added to this repository.


### Motivation
Via this project I wanted to practice my understanding of logistic regression model.


### Thought process
- I examined the dataframe and in particular the target column due to the number of classes
- I examined what interia would suit best for the data set
- I looped over each feature column and collected the F1 scores
- I visualised my results
