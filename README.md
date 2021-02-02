# STA 199: Data wrangling I

**Date**: Wednesday, February 3<br>

## Learning objectives

- Core functions from package `dplyr`
- Tidy data and tibbles
- Extract meaning through data wrangling
- Comparison and logical operators

## Key Resources

- [dplyr cheatsheet](https://rstudio.com/wp-content/uploads/2015/02/data-wrangling-cheatsheet.pdf)

## `dplyr` functions

Common single data frame functions / verbs:

| Function                       | Description                          |
|--------------------------------|--------------------------------------|
| `filter()`                     | pick rows matching criteria          |
| `slice()`                      | pick rows using indices              |
| `select()`                     | pick columns by name                 |
| `pull()`                       | grab a column as a vector            |
| `rename()`                     | rename specific columns              |
| `arrange()`                    | reorder rows                         |
| `mutate()`                     | add new variables                    |
| `transmute()`                  | create new data frame with variables |
| `distinct()`                   | filter for unique rows               |
| `sample_n()` / `sample_frac()` | randomly sample rows                 |
| `summarise()`                  | reduce variables to values           |

## Comparison and logical operators

| Operator      | Definition                   |
|---------------|------------------------------|
| `<           `| is less than?                |
| `<=          `| is less than or equal to?    |
| `>           `| is greater than?             |
| `>=          `| is greater than or equal to? |
| `==          `| is exactly equal to?         |
| `!=          `| is not equal to?             |
| `x & y       `| is x AND y?                  |
| `x \| y      `| is x OR y?                   |
| `is.na(x)    `| is x NA?                     |
| `!is.na(x)   `| is x not NA?                 |
| `x %in% y    `| is x in y?                   |
| `!(x %in% y) `| is x not in y?               |
| `!x          `| is not x?                    |