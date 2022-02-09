BlastBioinformatics\_Week3: Sequence Logos
================
Neera Patadia
09/02/2022

## Getting Familiar With R

This is an R Markdown document. Markdown is a simple formatting syntax
for authoring HTML, PDF, and MS Word documents. For more details on
using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that
includes both content as well as the output of any embedded R code
chunks within the document.

### R basics

Before getting into the sequence logo tutorial for this week, lets try
and get a bit familiar with the R programming language\! Lets start off
by printing out text\! To do this, we can use the `print()` command.

``` r
print("Hello World")
```

    ## [1] "Hello World"

Notice that the words we want to print are enclosed in quotation marks\!
This tells R that we are printing out something called a *string*.

Now you try\! Use the `print()` command to print out any phrase you
want\!

``` r
##Write your code here!
```

When programming, A lot of the time, we want the computer to remember a
particular value. We can do this by assigning the value to something
called a *variable*. You may have heard of variables before in your math
classes, were you can say something like `x = 7`. Then if you have an
equation like `x + 5`, we know the answer will be `12` because `7 + 5
= 12`. Lets see this in action in R\!

``` r
x = 7
x + 5
```

    ## [1] 12

When working with computers, *variables* can be more than just numbers.
They could also be a *string* or something more complicated like a
*matrix* or *dataframe*. Practice assigning different values to
variables below.

``` r
##Write your code here!

##variable containing a number 

##variable containing a string
```

In R, we can use the `typeof()` command to see whether what the *type*
of the variable is - that is whether it is a string, a number, a
dataframe and so on\! Try out the command below\!

``` r
##Write your code here!
```

### R Data Manipulation

## Loading In Libraries

This week, we will be working with the **ggSeqLogo** package. A package
can be though of as a bit of code written by another person, we can use
for our own analyses. To use packages in R, we need to first install
them. Once they are installed, they can be loaded into the program.

    ## Warning in register(): Can't find generic `scale_type` in package ggplot2 to
    ## register S3 method.

Note that the `echo = FALSE` parameter was added to the code chunk to
prevent printing of the R code that generated the plot.
