<!-- .slide: data-transition="fade" -->

## How Do Machines Learn?

$$ SalePrice = f(LotArea, TotalBsmtSF, ...) $$

|$$ SalePrice $$|$$ LotArea $$|$$ TotalBsmtSF $$|
|---------|-----------|---------  |
|208500   |8450       |856        |
|181500   |9600       |1262       |
|223500   |11250      |920        |
|140000   |9550       |756        |
|250000   |14260      |1145       |

Note:
- [House prices dataset available on Kaggle](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)
- ~1400 examples like 208500 = f(60, RL, 65, ...)

---

<!-- .slide: data-transition="fade" -->

## In Earlier Terminology

$$ y = f(X) $$

|$$ y $$  |$$ X_1 $$  |$$ X_2 $$  |
|---------|-----------|---------  |
|208500   |8450       |856        |
|181500   |9600       |1262       |
|223500   |11250      |920        |
|140000   |9550       |756        |
|250000   |14260      |1145       |

Note:
- in our earlier y = f(x) syntax
- x is really a list of values - so uppercase X 

---

<!-- .slide: data-transition="fade" -->

## Machine Learning Terms

$$ Target Variable = f(Feature, Feature, ...) $$

|$$ Target Variable $$|$$ Feature $$|$$ Feature $$ |
|---------|-----------|---------  |
|208500   |8450       |856        |
|181500   |9600       |1262       |
|223500   |11250      |920        |
|140000   |9550       |756        |
|250000   |14260      |1145       |

Note:
- Target variable is what we're trying to predict using features
- Features might be raw values as here, more often "feature engineering" will have been done to produce more viable and useful features.

---

## Enter Machine Learning

<img src="images/ml-flow.png" width="100%"/>

Note:
 - Examples are xs and ys that we already have
 - Model is the `f` we learn
 
