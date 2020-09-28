
-----

output: github\_document

-----

<!-- README.md is generated from README.Rmd. Please edit that file -->

<a id="top of page"></a>

# pew\_leadr

Motivated by a [Pew Research Center
tweet](https://twitter.com/pewresearch/status/1310060605752119303?s=20),
displaying recent data on countries viewed as the world’s current
leading economic power, I became curious how these estimates compared to
previous administrations of the question.

Using the Pew Research Center [Question Search
interface](https://www.pewresearch.org/global/question-search/), I found
pertinent data available on the website that provided estimates from the
spring 2016 and spring 2019 surveys. My objective was to calculate the
2016 to 2019 change in these estimates in order to provide some
longitudinal context for interpreting the estimates presented in the
aforementioned tweet.

The source data for this analysis come from the Pew Global Attitudes &
Trends Question Database; Question: [Today, which ONE of the following
do you think is the world’s leading economic
power?](https://www.pewresearch.org/global/question-search/?qid=1284&cntIDs=&stdIDs=).

A .csv file of the exported table of data can be found at
[data-raw/pew\_leading\_economic\_power\_data.csv](https://github.com/MarkLaVenia/pew_leadr/blob/master/data-raw/pew_leading_economic_power_data.csv)

All `R` code required for this analysis can be found in
[R/pew\_leadr.Rmd](https://github.com/MarkLaVenia/pew_leadr/blob/master/R/pew_leadr.Rmd).

Analyses made use of the `tidyverse` and `zoo` `R` packages. Steps to
this project were to clean and restructure the file to prepare it for
analysis; calculate summary statistics for 2016 to 2019 change in
response by country; and identify countries that demonstrated the
largest increase or decrease over the 2016-2019 period.

## acknowledgement

I want to thank The Pew Research Center for making these data freely
available and thank their communications teams for their role in
disseminating these results and promoting public discourse on the
findings.
