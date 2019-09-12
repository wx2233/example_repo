Simple Document
================
Weijia Xiong
2019-09-12

I’m an R Markdown document\!

# Section 1

Here’s a **code chunk** that samples from a *normal
    distribution*:

    ## ── Attaching packages ────────────────────────────────────────────────────────── tidyverse 1.2.1 ──

    ## ✔ ggplot2 3.2.1     ✔ purrr   0.3.2
    ## ✔ tibble  2.1.3     ✔ dplyr   0.8.3
    ## ✔ tidyr   0.8.3     ✔ stringr 1.4.0
    ## ✔ readr   1.3.1     ✔ forcats 0.4.0

    ## ── Conflicts ───────────────────────────────────────────────────────────── tidyverse_conflicts() ──
    ## ✖ dplyr::filter() masks stats::filter()
    ## ✖ dplyr::lag()    masks stats::lag()

    ## [1] 100

# Section 2

I can take the mean of the sample, too\! The mean is -0.0497358.

    ## [1] -0.04973585

the number of rows in `plot_df` is
100

![](template_rmd_files/figure-gfm/learning%20assessment%201-1.png)<!-- -->

    ## `stat_bin()` using `bins = 30`. Pick better value with `binwidth`.

![](template_rmd_files/figure-gfm/learning%20assessment%201-2.png)<!-- -->

The median of the variable containing absolute values is 1.04.

## Text formatting

*italic* or *italic* **bold** or **bold** `code` superscript<sup>2</sup>
and subscript<sub>2</sub>

## Headings

# 1st Level Header

## 2nd Level Header

### 3rd Level Header

## Lists

  - Bulleted list item 1

  - Item 2
    
      - Item 2a
    
      - Item 2b

<!-- end list -->

1.  Numbered list item 1

2.  Item 2. The numbers are incremented automatically in the output.

## Tables

| First Header | Second Header |
| ------------ | ------------- |
| Content Cell | Content Cell  |
| Content Cell | Content Cell  |

  - The mean of the sample is 1.0468884.
  - The median of the sample is is 1.0384175.
  - The standard deviation of the sample is is 1.029708.
