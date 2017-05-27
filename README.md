# pgfplot-extensions

PGFPlots draws high-qual­ity func­tion plots in nor­mal or log­a­rith­mic scal­ing with a user-friendly in­ter­face di­rectly in TEX. And this rep is responsible for adding hci-lab helwan university extension for it

## [Stem and Leaf](https://github.com/hci-lab/pgfplot-extensions/tree/master/Stem%20and%20Leaf%20plot) plot

A **stem-and-leaf** display is a device for presenting quantitative data in a graphical format, similar to a _histogram_ , to assist in visualizing the shape of a distribution. They evolved from Arthur Bowley's work in the early 1900s, and are useful tools in exploratory data analysis. Stemplots became more commonly used in the 1980s after the publication of John Tukey's book on exploratory data analysis in 1977.

### Basic usage

`\stemNleaf{**data type**}{**data array**}{**fraction**}{**stem color**}{**leaf color**}{**bar color**}`

`\stemNleaf{10}{{1.1,2.2,3,4,5,6,7,8,9,10,11,12,17,20,22,25,29,31,43,50}}{1}{blue}{red}{green}`
![StemAndLeafImage](https://github.com/hci-lab/pgfplot-extensions/blob/master/docImages/StemAndLeaf.PNG)

### API Reference
 `\stemNleaf{**data type**}{**data array**}{**fraction**}{**stem color**}{**leaf color**}{**bar color**}`
 `\fractionalStemNleaf{**data type**}{**data array**}{**stem color**}{**leaf color**}{**bar color**}`
 
 `\partialStemNleaf{**data type**}{**data array**}{**fraction**}`
 
 `\fivePinsStemNleaf{**data type**}{**data array**}{**fraction**}`

* **Data type**
  This parameter specify the data ranges, example: {10} this means the data maybe between 10 and 100 (has 2 digit numbers)
  
* **Data array**
  For this parameter user put his data, in order manner (preferred)
  
* **Fraction**
  Fraction is used when you do not want to round your data array, put **data type** equals _1_ for new stem type
  
* **Stem color**
  Here user specify the stem color it maybe any color he want and the **default** is _Black_

* **Leaf color**
  Here user specify the leaf color it maybe any color he want and the **default** is _Black_

* **Bar color**
  Here user specify the bar color it maybe any color he want and the **default** is _Black_.
  The bar is divide the plot into stem and leaf.
  
### See [Notes and TODO](https://github.com/hci-lab/pgfplot-extensions/blob/master/Stem%20and%20Leaf%20plot/README.md)
