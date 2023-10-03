
<!-- README.md is generated from README.Rmd. Please edit that file -->

# loquiAPI

<!-- badges: start -->
<!-- badges: end -->

The goal of loquiAPI is to empower users to programmatically generate
automated videos from Google Slides or Microsoft PowerPoint slides. By
utilizing the API hosted on Fred Hutch’s servers, accessible at
<https://loquiapi.fredhutch.org/__docs__/> and using R functions like
`generate_from_gs()`, users gain the ability to produce numerous videos
simultaneously from various sets of slides in Google Slides or
PowerPoint.

## Installation

You can install the development version of loquiAPI from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("FredHutch/loquiAPI")
```

## Example

When you want to generate a video of your Google Slides, run
`generate_from_gs(link)` and you should see the output file path to your
video mp4 file.

``` r
library(loquiAPI)

generate_from_gs(link = "https://docs.google.com/presentation/d/1Dw_rBb1hySN_76xh9-x5J2dWF_das9BAUjQigf2fN-E/edit#slide=id.p")
```
