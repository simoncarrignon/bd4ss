# Repository to store the R book describe the class Big Data For Social Scientists

This book can be read at sc.frama.io/bg4ss

To compile the book: 
```r
library(bookdown)
render_book("index.Rmd",output_dir="~/public_html/bd4ss/")
```

and don't forget to update reading right: 
```bash
chmod -R a+r ~/public_html/bd5ss/
```

presentation:

using 
```r
install.packages('xaringan')
```

compile:

```r
rmardown::render("05_network.Rmd")
```

