## Why Functional Programming Solutions 

### Challenge 1

Explain why this solution is not very efficient. (e.g., If `df$a[df$a == -99] <- NA` has an error, how are you going to fix it?) 

**Answer** A solution is not scalable if it's not automatable and, thus, scalable.

### Challenge 2 

Why is using function more efficient than 100% copying and pasting? Can you think about a way we can automate the process?

**Answer** There are multiple reasons. Functions use less code overall, reducing the amount we type and have to debug. Functions can be reused, allowing us to scale and automate a process. 

### Challenge 3 

If you run the code below, what's going to be the data type of the output?


```{r}

map_chr(df, fix_missing)

```

**Answer** The code will return a named character vector of NAs


