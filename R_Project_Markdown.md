---
title: "In_Class_9-27"
author: "Amy Pollpeter"
date: "9/27/2019"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

```{r}
getwd()
```

```{r}
read_tsv("fang_et_al_genotypes.txt")
```

```{r}
summary("fang_et_al_genotypes.txt")
```


```{r}
fang_data <- read_tsv("fang_et_al_genotypes.txt")
```