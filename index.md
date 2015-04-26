---
title       : Shiny App of Examples!
subtitle    : Slidifiy is R's version of Interactive "PowerPoint"
author      : Happy Data Science Student 1
job         : Improving my skills
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Shiny Apps!
This shiny app is designed to be an example of interactive code with R.  The app page contains 3 tabs, 3 seperate examples
of elegant data analysis possibilites with shiny.  

Here is the link to my shiny app!
https://sdaniel1.shinyapps.io/assignment/   

and the git hub repo:
https://github.com/dsiever/shinyApps

My objective here, just like in the shiny app, is to show some examples of data presentation.  The course requirement was
for just 5 slides, I know there are 6 here -- I could not figure out how to remove the last blank slide.

By the way, this presentation is done in SLIDIFY which, it too has many elegant features, including the ablility to 
interact with R and write markdown.

$$\frac{-b \pm \sqrt{b^2 - 4 a c}}{2a}$$

"Shiny apps and slidify are the new normal in data presentation" 
<cite> by: Me</cite>

Use an empty line followed by three dashes to separate slides! 

--- .class #id 


## Interact with R!
1. Code up in R, display code, or not, your choice and display a plot.


```r
y <- rnorm(100); x <- rnorm(100)       
plot(x,y)
```

![plot of chunk block2](assets/fig/block2-1.png) 

2. When plotting, be aware of the size of the plot.  Adjust size by adding fig.width, and 
fig.height to the r code chunk.



--- .class #id 

## Another example of interaction with R!
1.  Create anothe simple plot!

```r
require(ggplot2)
```

```
## Warning: package 'ggplot2' was built under R version 3.1.2
```

```r
qplot(wt, mpg, data = mtcars)
```

<img src="assets/fig/simple-plot-1.png" title="plot of chunk simple-plot" alt="plot of chunk simple-plot" style="display: block; margin: auto;" />

--- .class #id 

## Final Points

1. Slidify makes interactive presenations a breeze.  The shiny app shown in the links above is the new normal in the way 
data will be and should be presented now, and in the future.
2. Incorporate R code, and charts and be on your way to a professional presenation that will help you deliver a confident message and a wonderful experience for your audience.

--- .class #id 
