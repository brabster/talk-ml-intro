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
- Do you need to explain decisions? (eg. finance, medicine)
- Feature engineering to suit the model

---

## Linear Regression?

<!-- .slide: data-transition="fade-out" -->

<img src="images/house_prices_linear_chart_noline.png" height="400px"/>

$$ SalePrice = f(LotArea)$$

Note:
- Linear regression fits a line to some data points - eg. learns an 'f' between x and y
- Combine the predictions for different features
- Guess where the best-fit line goes?

---

## Linear Regression?

<!-- .slide: data-transition="fade" -->

<img src="images/house_prices_linear_chart.png" height="400px"/>

$$ SalePrice = 2(LotArea) + 158000 $$

Note:
- Estimated sale price $$ y = 2(lot_area) + 158000 $$
- This is the "best fit" line - average error over all the training data is minimised
- Not where you expected?
- Why? Dense clusters of points in 100-200k sales price range
- Is this a good solution for a sale price prediction product?
- Maybe one feature isn't enough

---

## k-Nearest Neighbours?

<!-- .slide: data-transition="fade-out" -->

<img src="images/top_plot_larger_text.png" height="500px"/>

Note:
- Add a second feature - Basement area
- Hard to visualise linear regression with a second feature...
- ...and want to illustrate a second type of model, so use a k-nearest-neighbours model


---

## k-Nearest Neighbours?

<!-- .slide: data-transition="fade" -->

<img src="images/top_plot_larger_text_knn_example.png" height="500px"/>

Note:
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
- ethics, explainability

---

## Music Recommender (Poll)

<img src="images/listening_to_music.jpg" height="300"/>

When confidence is low...

<ul>
  <li>Play it anyway?</li>
  <li>Stop?</li>
<ul>

Note:
- You are building an intelligent track autoplay feature
- Each next track prediction has a high or low confidence
- If confidence is low, should the service play it anyway or stop and let the user choose? 
- Photo by [Muhammadtaha Ibrahim Ma'aji](https://unsplash.com/@planeteelevene) on Unsplash

---

## Cancer Screener (Poll)

<img src="images/x-ray.jpg" height="300"/>

When confidence is low...

<ul>
  <li>Diagnose?</li>
  <li>Defer to human expert?</li>
<ul>

Note:
- You are building an cancer detector for screening
- Each cancer/not-cancer prediction has a high or low confidence
- What should happen when the prediction is cancer and confidence is low? (potential false positive)
- What should happen when the prediction is not cancer and confidence is low? (potential false negative)
- What to do depends on context, especially with respect to potential errors
- Photo by [Owen Beard](https://unsplash.com/@owenbeard) on Unsplash

---

## Is Machine Learning Easy?

### Ask Microsoft...

<img class="fragment" src="images/taytweets.png" style="height: 400px"/>

Note:
- March 23rd, 2016
- 16 hours to takedown

---

## Is Machine Learning Easy?

### Ask Niantic...

<img class="fragment" src="images/pokemon.png" style="height: 400px"/>

Note:
- 2016 story

---

## Is Machine Learning Easy?

### Ask Amazon...

<img class="fragment" src="images/amazon-hr-ai.png" style="height: 400px"/>

Note:
- 2018 story
