## Is Machine Learning Easy?

<img src="images/survey.jpg" class="fragment" style="height: 200px"/>
<img src="images/cleaning.jpg" class="fragment" style="height: 200px"/>
<img src="images/training.jpg" class="fragment" style="height: 200px"/>

Note:
Getting Data
- Where will you get the data you need?
- Consider privacy and compliance needs

Cleaning Data
- Handling errors, missing data
- Potentially dealing with large datasets (often not)

Training a Model
- What kind of model?
- Feature engineering to suit the model

---

## Simple Model

<!-- .slide: data-transition="fade-out" -->

<img src="images/house_prices_linear_chart_noline.png" width="800px"/>

Note:
- Linear regression fits a line to some data points - eg. learns an 'f' between x and y
- Combine the predictions for different features
- Guess where the best-fit line goes?

---

## Linear Regression?

<!-- .slide: data-transition="fade" -->

$$ SalePrice = 2(LotArea) + 158000 $$

<img src="images/house_prices_linear_chart.png" width="800px"/>

Note:
- Estimated sale price $$ y = 2(lot_area) + 158000 $$
- This is the "best fit" line - average error over all the training data is minimised
- Not where you expected?
- Why? Dense clusters of points in 100-200k sales price range
- Maybe one feature isn't enough

---

## k-Nearest Neighbours?

<!-- .slide: data-transition="fade-out" -->

<img src="images/top_plot_larger_text.png" width="700px"/>

Note:
- Add a second feature - Basement area

---

## k-Nearest Neighbours?

<!-- .slide: data-transition="fade" -->

<img src="images/top_plot_larger_text_knn_example.png" width="700px"/>

Note:
- Hard to visualise linear regression with a second feature...
- ...and want to illustrate a second type of model, so use a k-nearest-neighbours model
- Can see similar shaded points seem to cluster together, average error should be much smaller than the linear regression
- k-NN makes softer assumptions about what's going on than linear regression but it's not practical with large datasets

---

## Is Machine Learning Easy?

<img src="images/survey.jpg" style="height: 200px"/>
<img src="images/cleaning.jpg" style="height: 200px"/>
<img src="images/training.jpg" style="height: 200px"/>
<img src="images/human-robot.jpg" class="fragment" style="height: 200px"/>
<img src="images/bias.jpg" class="fragment" style="height: 200px"/>

Note:
- deploying
  - don't bankrupt or fall over - performance, measuring
  - don't get worse - iterating, evaluating
  - ==============================
  - !!! recommender vs. cancer
- ethics, explaining

---

## Is Machine Learning Easy?

### Ask Microsoft...

<img class="fragment" src="images/taytweets.png" style="width: 650px"/>

Note:
 - March 23rd, 2016
 - 16 hours to takedown

---

## Is Machine Learning Easy?

### Ask Niantic...

<img class="fragment" src="images/pokemon.png" style="width: 650px"/>

Note:
 - 2016 story

---

## Is Machine Learning Easy?

### Ask Amazon...

<img class="fragment" src="images/amazon-hr-ai.png" style="width: 650px"/>

Note:
 - 2018 story

