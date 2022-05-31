# Markdown0
### Some Math Equation
<p align="center">
First equation: $Y=X\beta+\epsilon y,\forall X$ <br>
Second equation: $X=Z\gamma+\epsilon x$ <br><br>

$$f_1(\omega)=\frac{\sigma^2}{2\pi}\,\omega\in[-\pi,\pi]$$

1. First item a. first sub-item A) first sub-sub-item b. second sub-item
2. Second item
3. Third item a. second sub item
4. Fourth Item
-  First Item
-  Second Item
     - first sub-item
          - first sub-sub-item
     - second sub-item

<img src = "https://github.com/sbfrusho/ratake/blob/master/Screenshot%20from%202022-05-30%2022-47-17.png" alt = "picture" width = "200" height = "200">

```

library(tidyverse)
library(mdsr)
SAT_2010 %>% ggplot(aes(write,..density..)) + geom_histogram() +
geom_density() + theme_minimal() + labs(title = "SAT Writing Scores")
```
# Table with alingment

You can align text in the columns to the left, right, or center by adding a colon (:) to the left,
right, or on both side of the hyphens within the header row.

|Syntex   |Description |Test Text  |
|:-------:|:----------:|:---------:|
|Header   |Titles      |Here's this| 
|Paragraph|Text        |And more   | 

# Instructions

6.S191 software labs are designed to be completed at your own pace. At the end of each
of the labs, there will be instructions on how you can submit your notebook for grade.
Additionally, if you would like to submit your lab as part of the 6.S191 lab competitions,
instructions regarding what information must be submitted is also provided at the end of
each lab.  

### License

All code in this repository is copyright 2022 [MIT 6.S191 Introduction to Deep Learning](http://introtodeeplearning.com/). All
Rights Reserved.
Licensed under the MIT License. You may not use this file except in compliance with the
License. Use and/or modification of this code outside of 6.S191 must reference:

