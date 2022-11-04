# Journal Outcomes 

Comparison of actual accumulated citations with expected citations is often an import metric to understand impact.

The analysis of journals requires metadata from two sources, one of which is a paid source (Web of Science), thus the analysis here is limited in scope, and _fixed_ against snapshots from WOS and crossref.  

Because the scope of WOS index, while large, is limited, there is a significant diminution of dataset size and scope.  However, the value of this analysis is still important when assessing the _quality_ of the publications as measured by peer publications and frequent journals.

## Highlights
```{admonition} Journal Highlights
* the most frequently published journal was [The Astrophysical Journal](https://iopscience.iop.org/journal/0004-637X) with 12 publications
* the highest mean citations were accomplished in [Science](https://www.science.org/journal/science), with an average of 106.5 cites
* 88 papers in the analysis set (of 150) had 2 or more publications in a single journal (out of 27 distinct journals)
* 47 of those papers equalled or beat the expected journal citation mean
* of single-publication journals, EarthCube papers bested the average mean cites of 16.37 by nearly double at 32.39 cites
* of all journals analyzed, EC papers bested the mean cites of 14.96 by 61% bringing in a mean of 24.17
```

## Tables

* project/publication counts: {download}`[csv (download)]</analysis/outputs/ec_journals_top_pct_delta.csv>`

|   Journal Mean Cites |   Publication Year | Journal Title                                             |   EC Cites | EC Publiaation DOI                                                                         |   % diff mean cites |
|---------------------:|-------------------:|:----------------------------------------------------------|-----------:|:-------------------------------------------------------------------------------------------|--------------------:|
|                   17 |               2017 | International Journal of Digital Earth                    |        344 | [10.1080/17538947.2016.1239771](https://doi.org/10.1080/17538947.2016.1239771)             |            1923.53  |
|                   25 |               2017 | Geophysical Research Letters                              |        336 | [10.1002/2017gl074954](https://doi.org/10.1002/2017gl074954)                               |            1244     |
|                   10 |               2018 | Quaternary Research                                       |        120 | [10.1017/qua.2017.105](https://doi.org/10.1017/qua.2017.105)                               |            1100     |
|                    1 |               2021 | Computing in Science &amp; Engineering                    |         10 | [10.1109/mcse.2021.3059437](https://doi.org/10.1109/mcse.2021.3059437)                     |             900     |
|                    4 |               2019 | Communications of the ACM                                 |         39 | [10.1145/3192335](https://doi.org/10.1145/3192335)                                         |             875     |
|                    1 |               2021 | Computing in Science &amp; Engineering                    |          8 | [10.1109/mcse.2021.3059263](https://doi.org/10.1109/mcse.2021.3059263)                     |             700     |
|                    4 |               2021 | GSA Bulletin                                              |         30 | [10.1130/b35560.1](https://doi.org/10.1130/b35560.1)                                       |             650     |
|                    8 |               2019 | International Journal of Remote Sensing                   |         49 | [10.1080/01431161.2018.1516313](https://doi.org/10.1080/01431161.2018.1516313)             |             512.5   |
|                   15 |               2016 | Earth and Space Science                                   |         91 | [10.1002/2015ea000136](https://doi.org/10.1002/2015ea000136)                               |             506.667 |
|                   13 |               2017 | JAWRA Journal of the American Water Resources Association |         72 | [10.1111/1752-1688.12474](https://doi.org/10.1111/1752-1688.12474)                         |             453.846 |
|                    5 |               2017 | Journal of Visualized Experiments                         |         25 | [10.3791/54660](https://doi.org/10.3791/54660)                                             |             400     |
|                    8 |               2020 | Data Intelligence                                         |         40 | [10.1162/dint_a_00033](https://doi.org/10.1162/dint_a_00033)                               |             400     |
|                    3 |               2018 | AI Magazine                                               |         13 | [10.1609/aimag.v39i3.2816](https://doi.org/10.1609/aimag.v39i3.2816)                       |             333.333 |
|                   39 |               2017 | Scientific Data                                           |        167 | [10.1038/sdata.2017.88](https://doi.org/10.1038/sdata.2017.88)                             |             328.205 |
|                   19 |               2018 | BioScience                                                |         77 | [10.1093/biosci/biy068](https://doi.org/10.1093/biosci/biy068)                             |             305.263 |
|                    1 |               2021 | Geophysical Journal International                         |          4 | [10.1093/gji/ggab238](https://doi.org/10.1093/gji/ggab238)                                 |             300     |
|                   27 |               2017 | Computers, Environment and Urban Systems                  |        108 | [10.1016/j.compenvurbsys.2016.10.010](https://doi.org/10.1016/j.compenvurbsys.2016.10.010) |             300     |
|                    1 |               2021 | Concurrency and Computation: Practice and Experience      |          4 | [10.1002/cpe.6099](https://doi.org/10.1002/cpe.6099)                                       |             300     |
|                   32 |               2017 | Renewable Energy                                          |        127 | [10.1016/j.renene.2017.02.052](https://doi.org/10.1016/j.renene.2017.02.052)               |             296.875 |
|                   12 |               2019 | Journal of Proteome Research                              |         44 | [10.1021/acs.jproteome.8b00761](https://doi.org/10.1021/acs.jproteome.8b00761)             |             266.667 |

## Charts and Graphs
* no charts or graphs have been produced for this section

## Interpretation
It is anticipated that high impact journals such as Nature get cited more, so it is not unexpected that publications in those journals do well.  In smaller journals this may not always be the case, but when cites in smaller journals beat the average by large margins, this may indicate that the publication struck a chord within the targeted community, and this often suggests greater impact as these communities tend to be smaller, thus highly cited papers there are desirable.

## Methodology 
The methodology use for this analysis required different tools and approaches to reach a final outcome.  The basic steps and process are explained below:

* For each journal in which EC authors published at least one article, we used the Web of Science to find an average citation rate for the year(s) in which EC articles were published.

* To get the average citation count in the Web of Science, we did a search for the journal via the "publications title" search, and date-limited the search by using the "Add Date Range" option in the Web of Science search. Selecting the “Custom” date option allows you to add a specific data range, such as 2019-01-01 and 2019-12-31. This allowed us to limit the search to be from Jan 1 and Dec 31 for the specific journal and year of interest.

* Journals that were not indexed in the Web of Science return an error message for this search. For journals that were indexed, the search results return all papers published in the given journal and year. 

* Once results were returned, we clicked on the "Citation Report" button toward the top right of the search results page. This returns a variety of metrics for the search results, but also shows an "Average per item" citation metric.

* We compiled these metrics for all journals and years in which EC articles were published. We then compared the actual citation counts for the EC articles with these average citation counts for their associated journal and year.

Journal average citation counts were compiled in Aug. 2022

## Analysis Notebooks

* [01_basic_journal_analysis.ipynb](../analysis/notebooks/01_basic_journal_analysis.ipynb)
