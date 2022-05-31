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


