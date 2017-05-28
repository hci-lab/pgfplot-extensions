# pgfplot-extensions

PGFPlots draws high-quality function plots in normal or logarithmic scaling with a user-friendly interface directly in TEX. And this rep is responsible for adding hci-lab helwan university extension for it

These project created by hci-lab students under [Dr. waleed a. yousef](https://github.com/DrWaleedAYousef) supervision.

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

### Created By
 * [Hisham Elamir](https://github.com/HishamElamir)
 * [Mahmoud Hamdy](https://github.com/mamhoud)


## [Utility Functions](https://github.com/hci-lab/pgfplot-extensions/tree/master/utility%20functions)
 
 Some computational functions that helps _LATEX_ user to perform well with any _pgf_-extension

### Basic usage

`\arrayLength{{1,2,3,4,5,6}}`

### API Reference
 * **Number of Existance**
 Gets number of any element existance in given data array
 `\numOfExistance{3}{{1,3,3,4,5}}`
 
 * **Max**
 Gets the maximum value of given two elements.
 `\maxe{10}{13}`
 
 * **Min**
 Gets the minimum value of given two elements.
 `\mine{10}{13}`
 
 * **Maximum for All**
 Gets the maximum value in the given array using natural order.
 `\maxForAll{{1,2,3,4,5}}`
 
 * **Minimum for All**
 Gets the minimum value in the given array using natural order.
 `\minForAll{{1,2,3,4,5}}`
 
 * **Is Unique**
 Check if the given number is exist in array and it's unqiue or not
 `\isunique{1}{{1,2,3,4,5}}`
 
 * **Array Length**
 It gets the given array length
 `\arrayLength{{1,2,3,4,5,6}}`
 
 * **Divide and Print Once**
 It takes array data, divide it by number and print each number exist in it once and only once
 `\printOnce{{10,11,20,22,30,33,34}}{10}`
 
 * **Divide and Check**
 Checks if 2 values results division(with the same dominator) are equals or not (1 if equals/ 0 if not) **means** _(A / C == B / C) or not_, it checks of first two element and the third is the dominator used for division
 `\devNck{20}{10}{10}`
 
 * **Mod and Check**
 Checks if 2 values results of modulas(with the same dominator) are equals or not (1 if equals/ 0 if not) **means** _(A % C == B % C) or not_, it checks of first two element and the third is the modulas
 `\modNck{10}{20}{4}`
 
 **There's more docs will comme, stay tuned**
### Created By
 * [Hisham Elamir](https://github.com/HishamElamir)


## [Parallel Coordinates](https://github.com/hci-lab/pgfplot-extensions/tree/master/Parallel%20Coordinates) plot
Docs are comming soon!!!
