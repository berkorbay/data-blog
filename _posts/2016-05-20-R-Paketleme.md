---
layout: post
title: R ve GitHub ile Paket Yapma
---

Bu yazıda adım adım R'da paketleri nasıl yaparsınız GitHub üzerinden nasıl yayınlarsınız onu anlatacağım.

```{r}
library("devtools")
devtools::install_github("klutometis/roxygen")
library(roxygen2)
```