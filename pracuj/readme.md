# Dataset from pracuj.pl website

How to install ans use this package?

```
install_github("mi2-warsaw/pracuj/pracuj")

library(pracuj)
short <- get_offers(description=FALSE)
head(short)
long <- get_offers(description=TRUE)
head(long)
```