# Topic / Title: push() and pop()

2023-01-08
21:46


# Notes
By default any transformations will affect the global matrix/coorindate system which can make transforming individual shapes hard/impossible as all transformations will compound on one another by default. To get around this there are the `push()` and `pop()` functions which will apply transformations on their own matrix/coordinate system.

First you write `push()` which will let processing know that any following transformations should be applied to their own matrix then at the end you type 

# Keywords/Questions

# Summary

Related:
Tags: 