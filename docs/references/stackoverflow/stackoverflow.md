- .tolist()[How to unpack a Series of tuples in Pandas?](https://stackoverflow.com/questions/22799300/how-to-unpack-a-series-of-tuples-in-pandas)

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

- `list[:10]` [Fetch first 10 results from a list in Python](https://stackoverflow.com/questions/10897339/fetch-first-10-results-from-a-list-in-python)