- Code:

```

with open('readme.txt') as f:
    lines = f.readlines()

```

[Python Read Text File](https://www.pythontutorial.net/python-basics/python-read-text-file/)

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

------------------

- Code & Text:

```

You can slice twice and join them.

listing[0:3] + listing[4:5]

```

[How to extract multiple slices in an array?](https://stackoverflow.com/questions/38895781/how-to-extract-multiple-slices-in-an-array)