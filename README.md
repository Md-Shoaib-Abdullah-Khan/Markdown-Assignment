# Assignment 0: Markdown
## You have to write markdown
### Some Math Equation
<p align="center">
  First equation: Y=Xβ+ϵ<sub>y</sub>, ∀X <br>
  Second equation: X=Zγ+ϵ<sub>x</sub> <br>
  f<sub>1</sub>=$\frac{σ^2}{2π}$,ω∈[−π,π]<br>
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
