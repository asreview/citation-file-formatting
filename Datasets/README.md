# Datasets
A collection of datasets to illustrate the export capabilities of the tools and software described in this repository.

As you might have found out for yourself already, file formats are not created equal. Many of them are not standardised, allowing for unnecessary confusion in importing and exporting your work. That is why we are collecting these datasets and information here in an open repository...

...to work together as a community and work towards a common understanding of file formats in the field of scientific review. Effectively, to work towards a standardised future.

In case you are interested in supporting the effort, please refer to our [guide for contributing](#contributing).


## Baseline
Below, you can find the baseline files which should represent the file as close to the official specific standard as possible. *[Description of the file formats](#file-formats)*.

| Format | Baseline |
| --- | --- |
| CSV | [_baseline.csv](CSV/_baseline.csv) |
| RIS | [_baseline.ris](RIS/_baseline.ris) |
| TSV | [_baseline.tsv](TSV/_baseline.tsv) |
| XLSX | [_baseline.xlsx](XLSX/_baseline.xlsx) |

The files were collected from [Lens.org](https://link.lens.org/cpUG60v0The) into a collection. This collection was then exported. Unfortunately, some of the the [export features for Lens.org are broken](https://twitter.com/TheLensOrg/status/1412911995930611713), so we decided to comprise the baseline files manually from the exported files from Lens.org.

* First, the RIS file was uploaded;
* second,[the obvious encoding errors were fixed](https://github.com/asreview/citation-file-formatting/commit/fc27c7946244112a01033411a5c473579a208dc9), namely the "�" was replaced with proper symbols;
* third, [some numerical encoding errors were fixed](https://github.com/asreview/citation-file-formatting/commit/974e69398ffdad0a65ebb5ed56cb27f39ff18af9);
* fourth, [fixed some additional missing encoding](https://github.com/asreview/citation-file-formatting/commit/d58228217bee0305ac2345082c127a4ff48be870), namely the "?" was replaced with proper symbols where needed;
* additionally, we had to [add a "S" to secure a URL](https://github.com/asreview/citation-file-formatting/commit/72b81f0395d79f39b0c0fab316a00318d33af123) which was done properly in CSV but not in RIS.
* as a bonus, some links are missing from the RIS that were initially present in the CSV.

## Exporting
Below, you can find a list of files which have been exported from a specific tool or software *(e.g **[asreview.csv](CSV/asreview.csv)** represents a CSV which has been exported from ASReview)*.

| Format | ASReview | ... |
| --- | --- | --- |
| CSV | asreview.csv | |
| RIS | [WIP](https://github.com/asreview/asreview/issues/495) | |
| TSV | asreview.tsv | |
| XLSX | asreview.xlsx | |

## Importing
It is difficult to represent specific import capabilities of a given software from the perspective of a file format. But we will try to give you some highlights anyway! Namely, we are using the [baseline files](#baseline) for an import and comment based on it.

| Format | ASReview | ... |
| --- | --- | --- |
| CSV | Success | |
| RIS | [WIP](https://github.com/asreview/asreview/issues/495) | |
| TSV | Success | |
| XLSX | Success | |
