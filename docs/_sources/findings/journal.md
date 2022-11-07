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


|Citation| EC Cites | Journal Mean Cites | % diff mean cites|
|---:|:--:|:--:|:--:|
Yang, C., Q. Huang, Z. Li, K. Liu, and F. Hu, 2016: Big Data and cloud computing: innovation opportunities and challenges. International Journal of Digital Earth, 10, 13–53, https://doi.org/10.1080/17538947.2016.1239771. | 344 | 17 | 1923.53% |
Morlighem, M., and Coauthors, 2017: BedMachine v3: Complete Bed Topography and Ocean Bathymetry Mapping of Greenland From Multibeam Echo Sounding Combined With Mass Conservation. Geophysical Research Letters, 44, https://doi.org/10.1002/2017gl074954. | 336 | 25 | 1244.00% |
Williams, J. W., and Coauthors, 2018: The Neotoma Paleoecology Database, a multiproxy, international, community-curated data resource. Quaternary Research, 89, 156–177, https://doi.org/10.1017/qua.2017.105. | 120 | 10 | 1100.00% |
Abernathey, R. P., and Coauthors, 2021: Cloud-Native Repositories for Big Scientific Data. Computing in Science &amp; Engineering, 23, 26–35, https://doi.org/10.1109/mcse.2021.3059437. | 10 | 1 | 900.00% |
Gil, Y., and Coauthors, 2018: Intelligent systems for geosciences. Communications of the ACM, 62, 76–84, https://doi.org/10.1145/3192335. | 39 | 4 | 875.00% |
Granger, B. E., and F. Perez, 2021: Jupyter: Thinking and Storytelling With Code and Data. Computing in Science &amp; Engineering, 23, 7–14, https://doi.org/10.1109/mcse.2021.3059263. | 8 | 1 | 700.00% |
Schaen, A. J., and Coauthors, 2020: Interpreting and reporting 40Ar/39Ar geochronologic data. GSA Bulletin, 133, 461–487, https://doi.org/10.1130/b35560.1. | 30 | 4 | 650.00% |
Sun, Z., L. Di, and H. Fang, 2018: Using long short-term memory recurrent neural network in land cover classification on Landsat and Cropland data layer time series. International Journal of Remote Sensing, 40, 593–614, https://doi.org/10.1080/01431161.2018.1516313. | 49 | 8 | 512.50% |
Gil, Y., and Coauthors, 2016: Toward the Geoscience Paper of the Future: Best practices for documenting and sharing research from data to software to provenance. Earth and Space Science, 3, 388–415, https://doi.org/10.1002/2015ea000136. | 91 | 15 | 506.67% |
Maidment, D. R., 2016: Conceptual Framework for the National Flood Interoperability Experiment. JAWRA Journal of the American Water Resources Association, 53, 245–257, https://doi.org/10.1111/1752-1688.12474. | 72 | 13 | 453.85% |

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
