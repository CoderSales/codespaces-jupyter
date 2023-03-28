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