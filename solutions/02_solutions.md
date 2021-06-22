# Automate 2 or 2+ Tasks 

### Challenge 1 

How many parameters do you need to solve the problem below? 

```{r}
# Outer loop for univ variable 
for (univ in c("Berkeley", "Stanford")) {
  # Inner loop for dept variable 
  for (dept in c("waterbenders", "earthbenders", "firebenders", "airbenders")) {
    print(paste("University = ", univ, "|", "Department = ", dept))
  }
}
```
**Answer** Two parameters here (university and department). There are eight total computations that will have to be made. 

### Challenge 2 

Why are we using `rep()` to create input vectors? For instance, for `univ_list` why not just use `c("Berkeley", "Stanford")`?

**Answer** There are 8 total computations. 

### Challenge 3 

Have you noticed that we used a slightly different input for `pmap()` compared to `map()` or `map2()`? What is the difference?

**Answer** `pmap()` allows us to provide any number of arguments in a list. It is the generalization case. 