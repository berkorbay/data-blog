---
layout: post
title: R ve GitHub ile Paket Yapma
---

Bu yazıda adım adım R'da paketleri nasıl yaparsınız GitHub üzerinden nasıl yayınlarsınız onu anlatacağım.

```{r}
install.packages("devtools")
library(devtools)
devtools::install_github("klutometis/roxygen")
library(roxygen2)
```

Veri eklemek için ise (diyelim ki data frameinizin adi data_frame olsun)

```{r}
devtools::add_data(data_frame)
```