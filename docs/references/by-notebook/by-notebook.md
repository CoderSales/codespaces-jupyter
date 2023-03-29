## histogram_boxplot
Code changed in `def histogram_boxplot(data, feature, figsize=(12, 7), kde=False, bins=None):` :

Edit 1: Swap row and column numbers for 2 pair of plots in each row
```
        nrows=1,  # Number of rows of the subplot grid= 2
        ncols=2,
```
Edit 2: Comment height ratios
```
        # gridspec_kw={"height_ratios": (0.25, 0.75)},
```

ml-model-tuning-3 | MT_MLS2_supermarket_campaign_2_template_pre_quiz.ipynb [MT_MLS2_supermarket_campaign_2_template_pre_quiz.ipynb](https://github.com/CoderSales/ml-model-tuning-3/commit/fa888f7dff3ac00ae77ec912abb8c82442273118)

# issue
TypeError: only integer scalar arrays can be converted to a scalar index

# Solution
## idea
- Text:

```
It turns out I needed to turn weights, a 1D Python list, into a NumPy array before I could apply multi-dimensional NumPy indexing. The code below works:
```

[numpy array TypeError: only integer scalar arrays can be converted to a scalar index](https://stackoverflow.com/questions/46902367/numpy-array-typeerror-only-integer-scalar-arrays-can-be-converted-to-a-scalar-i)

## to_frame()
y_train_over.to_frame()
- `df = s.to_frame(name="Age")` [How to convert series to DataFrame in pandas](https://www.educative.io/answers/how-to-convert-series-to-dataframe-in-pandas)


## XGBClassifier

```

xgb2 = XGBClassifier(
    # random_state=1,
    # eval_metric="logloss",
    # subsample=[0.8,0.9,1],
    # scale_pos_weight=[2,5,10],
    # n_estimators=np.arange(50,150,50),
    # learning_rate=[0.01,0.1,0.2,0.05],
    # gamma=[0,1,3,5],
    random_state=1,
    n_estimators=50,
    scale_pos_weight=10,
    subsample=0.8,
    learning_rate=0.01,
    gamma=0,
    eval_metric="logloss",
    reg_lambda=5,
    max_depth=1,
)## Complete the code with the best parameters obtained from tuning

xgb2.fit(X_train_over, y_train_over) ## Complete the code to fit the model on over sampled data

```

from notebook:
MT_week2_Additional_case_study.ipynb