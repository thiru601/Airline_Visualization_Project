---
title: "Github Test"
output: html_document
---



## R Markdown


```r
Train=sample(1000000,size=50)
hist(Train)
```

![plot of chunk unnamed-chunk-2](figure/unnamed-chunk-2-1.png)

```r
knitr::knit("Github1.Rmd")
```

```
## 
## 
## processing file: Github1.Rmd
```

```
## Error in parse_block(g[-1], g[1], params.src): duplicate label 'setup'
```

