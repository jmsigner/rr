% A sample report
% The author
% `r date()`

<!-- Setting up R -->
`ro warning=FALSE, dev="png", fig.cap="", cache=FALSE or`

<!-- read external r code -->
```{r reading, echo=FALSE}
read_chunk("script.r")
```

# The first part of my R script
Here I can generate my data
```{r}
<<gen-dat>>
```

# Results
An now the reults are plotted
```{r plot-fig, result="asis"}
<<plot>>
```

# More
Of course I can use inline elemtnts: 3 + 3 = `r 3+3`.


