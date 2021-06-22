# Automate Plotting 

## Challenge 1 

How can you create the character vector of column names?  

**Answer** In the context of this challenge 

```{r}

names(airquality)

```

## Challenge 2 

How can make `ggplot2()` take strings as x and y variable names? (Hint: Type `?aes_string()`) 

**Answer** 

```{r}
ggplot(aes_string(x = names(airquality)[1], y = names(airquality)[2]))
```

This is soft deprecated, so the modern way going forward is: 

```{r}
ggplot(airquality)+
    geom_point(aes(x = .data[[names(airquality)[1]]], 
    y = .data[[names(airquality)[2]]]))+
    ... # other arguments 
```

The underlying logic works in the same way. We pass in strings to the aes() function. 