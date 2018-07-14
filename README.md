# helping.funders
Helping funders and researchers by creating a list of a researcher's publication output using R and shiny.

The main file is `orcid.R`, which takes an ORCID ID and creates the publiction data. See `global.R` for a list of required R packages. The key R package is `rocrid`.

My wishlist of additions:
* Get the Google Scholar version working on a publicly available shiny server (see https://github.com/agbarnett/scholar.shiny)
* Add a plot of cumulative paper numbers over time, perhaps with a comparison of "similar" researchers
* Add in data from Mendeley and CiteULike on what papers are being read
* Add in data from altmetric on papers that are getting attention on twitter, blogs, etc
