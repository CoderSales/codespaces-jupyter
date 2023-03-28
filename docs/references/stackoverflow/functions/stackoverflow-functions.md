- Code:

```

def display_full(x):
    with pd.option_context('display.max_rows', None,
                           'display.max_columns', None,
                           'display.width', 2000,
                           'display.float_format', '{:20,.2f}'.format,
                           'display.max_colwidth', None):
        display(x)

```

[How can I display full (non-truncated) dataframe information in HTML when converting from Pandas dataframe to HTML?](https://stackoverflow.com/questions/25351968/how-can-i-display-full-non-truncated-dataframe-information-in-html-when-conver)
- [CoderSales/machine-learning-classification](https://github.com/CoderSales/machine-learning-classification)