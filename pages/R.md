---
output: 
  html_document:
    before_body: [include_header.html]
---


``` r
library(ggplot2)
ggplot(mpg, aes(x=cty, y=hwy)) + geom_point()
```
