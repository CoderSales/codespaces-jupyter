## StackOverflow
- pip install pandas [ImportError: No module named pandas](https://stackoverflow.com/questions/33481974/importerror-no-module-named-pandas)

## pandas DataFrame to Series
### Code:
`X_over1, y_over1 = sm.fit_resample(X1, Y1)`

### Issue:

- red squiggly underline.
- When mouse over:

```

(variable) X_over1: Unknown | DataFrame | Series[Unknown]
Expression with type "tuple[Unknown | DataFrame | Series[Unknown], Unknown | DataFrame | Series[Unknown]] | tuple[Unknown | DataFrame | Series[Unknown], Unknown | DataFrame | Series[Unknown], Unknown]" cannot be assigned to target tuple
  Type "tuple[Unknown | DataFrame | Series[Unknown], Unknown | DataFrame | Series[Unknown], Unknown]" is incompatible with target tuple
    Element size mismatch; expected 2 but received 3PylancereportGeneralTypeIssues

```

### Propsed Solution
convert DataFrame to Series

### Solution source
- `df.squeeze()` [How to Convert Pandas DataFrame to a Series](https://datatofish.com/pandas-dataframe-to-series/)