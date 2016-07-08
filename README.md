# diffexpSAMR

# first run analysis
# assume data has already been downloaded and formated

# define groups to be compared
comp <- c(rep(1,44), rep(2,44)
gn <- row.names(eset)

data <- list(x=eset,y=comp, geneid=gn, genenames=gn)

