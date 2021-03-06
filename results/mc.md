---
title: "Analysis of methods comparison"
output:
  html_document:
    keep_md: yes
    number_sections: yes
    toc: yes
  html_notebook: 
    number_sections: yes
    toc: yes
---




```
## Loading required package: nlme
```

# Methods

Deming regression + Pearson r/R².

Note: Null Titration values were excluded.

# Results

![Figure xx: Methods comparison between Titration and qPCR. Lines represent the Deming regression line for each experiment.](../figures/mc.png)


|    MOI    |  Virus  |    R    |    R2    |
|:---------:|:-------:|:-------:|:--------:|
| MOI 0.01  | Measles | 0.9369  |  0.8778  |
| MOI 0.01  |  Mumps  | 0.07548 | 0.005698 |
| MOI 0.001 | Measles | 0.9261  |  0.8577  |
| MOI 0.001 |  Mumps  | 0.6883  |  0.4737  |

Table: Table xx: R and R² statistics for Methods Comparison between Titration x qPCR

