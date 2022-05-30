# Assignment 0: Markdown
## You have to write markdown
### Some Math Equation
<p align="center">
  First equation: $Y=Xβ+ϵ_y, ∀X $ <br>
  Second equation: $X=Zγ+ϵ_x$ <br>
  f_{1}(ω)=$\frac{σ^2}{2π}$,ω∈[−π,π]<br>
</p>
1. First item a. first sub-item A) first sub-sub-item b. second sub-item <br>
2. Second item <br>
3. Third item a. second sub item <br>
4. Fourth Item <br><br>

- First Item <br>
- Second Item <br>
  - first sub-item <br>
     - first sub-sub-item <br>
  - second sub-item <br><br>

![Cute Cat](cat.png)

library(tidyverse) <br>
library(mdsr) <br>
SAT_2010 %>% ggplot(aes(write,..density..)) + geom_histogram() + <br>
geom_density() + theme_minimal() + labs(title = "SAT Writing Scores") <br>

# Table with allignment
You can align text in the columns to the left, right, or center by adding a colon (:) to the left,
right, or on both side of the hyphens within the header row.

| Syntax   | Description | Test       |
|:--------  |:-----------:|-------:|
|Header    |    Title    | Here's this|
|Paragraph |    Text     | And more   |

# Instructions
6.S191 software labs are designed to be completed at your own pace. At the end of each
of the labs, there will be instructions on how you can submit your notebook for grade.
Additionally, if you would like to submit your lab as part of the 6.S191 lab competitions,
instructions regarding what information must be submitted is also provided at the end of
each lab. <br>

# License
All code in this repository is copyright 2022 [MIT 6.S191 Introduction to Deep Learning][MIT Link]. All
Rights Reserved.


Licensed under the MIT License. You may not use this file except in compliance with the
License. Use and/or modification of this code outside of 6.S191 must reference:

> © MIT 6.S191: Introduction to Deep Learning <br>
> [http://introtodeeplearning.com][MIT Link]
[MIT Link]: http://introtodeeplearning.com
