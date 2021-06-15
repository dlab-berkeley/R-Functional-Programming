# Automate Binding?

## Challenge 1 

Why is the above solution is not efficient?

**Answer** We're duplicating typing. As you can see, `bind_rows()` is called twice. An alternative to this workflow is to use reduce. The Map/Reduce paradigm is one of the hallmarks of functional programming. 