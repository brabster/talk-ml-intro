## Classification

Cat or Turnip?

<img src="images/shelby.jpg" width="500px"/>

Note:
- two basic kinds of machine learning task
- classification - is it a picture of a cat or a turnip?

---

## Regression

How much is it worth?

<div style="display: flex; justify-content: center">
    <img src="images/tiny_house.jpg" width="300px">
    <img src="images/mansion.jpg" width="300px">
</div>

Note:
- the other kind of task, regression
- predict a number, like a house sale price
- Tiny house photo by <a href="https://unsplash.com/@larulls">Romain Rullaud</a> on Unsplash
- Mansion photo by <a href="https://unsplash.com/@dannybarness">Daniel Barnes</a> on Unsplash

---

<!-- .slide: data-transition="fade" -->

## How Do Machines Learn?

$$ SalePrice = f(LotArea, TotalBsmtSF, ...) $$

|$$ SalePrice $$|$$ LotArea $$|$$ TotalBsmtSF $$|
|:-----------:|----------:|----------:|
|**208500**   |8450       |856        |
|**181500**   |9600       |1262       |
|**223500**   |11250      |920        |

Note:
- [House prices dataset available on Kaggle](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)
- It's just a spreadsheet
- ML training typically uses matrices - which are like spreadsheets where every value must be a number
- Dataset actually has over 70 columns - domain knowledge to pick these two

---

<!-- .slide: data-transition="fade" -->

## In Earlier Terminology

$$ y = f(X) $$

|$$ y $$  |$$ X_1 $$  |$$ X_2 $$  |
|:-----------:|----------:|----------:|
|**208500**   |8450       |856        |
|**181500**   |9600       |1262       |
|**223500**   |11250      |920        |

Note:
- in our earlier y = f(x) syntax
- x is really a list of values - so uppercase X 

---

<!-- .slide: data-transition="fade" -->

## Machine Learning Terms

$$ Target Variable = f(Feature, Feature, ...) $$

|$$ Target Variable $$|$$ Feature $$|$$ Feature $$ |
|:-----------:|----------:|----------:|
|**208500**   |8450       |856        |
|**181500**   |9600       |1262       |
|**223500**   |11250      |920        |

Note:
- Target variable is what we're trying to predict using features.
- Features might be raw values as here, more often "feature engineering" will have been done to produce more viable and useful features.
- Rows may be referred to as "examples".

---

## Machine Learning Workflow

<img src="images/ml-flow.png" width="100%"/>

Note:
- Examples are xs and ys that we already have
- Model is the `f` we learn
 
