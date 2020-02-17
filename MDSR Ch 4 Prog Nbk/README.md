# MDSR Chapter 04 Programming Notebook

## Instructions

- change the .Rmd file name to include your name (e.g., "04-mdsr-Beckman.Rmd")
- update your name in the document
- program through Chapter 04 of the Modern Data Science with R (MDSR) textbook
    - Use Rmd headings corresponding to the section (`## 4.3`) and subsection (`### 4.3.1`), 
    - Include all section headings even if there is no programming required.
    - add a new code chunk corresponding to each new code chunk in the book
    - each code chunk must begin with a comment to indicate the corresponding page number in MDSR
    - the finished document should show all code and corresponding results (tables, figures, output) that appear in the textbook
    - *Exceptions*: where a table or figure in the book is NOT accompanied by code, you do NOT need to create the code (unless explicitly instructed to do so).  For example: 
        - Table 5.1 on page 93 would **NOT** be required because the code is not shown in the chapter
        - Table 5.2 on page 94 **WOULD** be required.
        - Figure 3.19 on page 48 would **NOT** be required because the code is not shown in the chapter.
    - all code is expected to follow the [Required programming style guide for STAT 380 (html)](https://mdbeckman.github.io/PSU-STAT-380/2019 Spring/STAT380-R-Style-Guide.nb.html)
        - You will have to clean up code from the book 
        - Common issues include: 
            - line breaks needed after chain operators (i.e. `%>%` for `dplyr`, and `+` for `ggplot2`), 
            - expanding "nested" syntax,
            - document organization
        - All packages used, user-defined functions, and data intake should be included in the "front-matter".  For example, the book often uses data sets from various packages without loading them into the R environment; you should include these in the front-matter with a `data()` function and specify the source package with an inline comment.
- submit your finished **R Notebook** (e.g., "04-mdsr-Beckman.nb.html") to Canvas
    - R Notebooks include access to the source code, so 
    - If the R Notebook fails to compile, you may submit an Rmd file for partial credit

## MDSR Textbook Error(s)

- p. 81: there are 178 airports in Pacific Time Zone

