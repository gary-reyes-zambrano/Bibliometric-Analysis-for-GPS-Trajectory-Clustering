# Bibliometric Analysis for GPS Trajectory Clustering

## Article title:

Scientific Production on GPS Trajectory Clustering: A Bibliometric Analysis

## Abstract:

Clustering algorithms or methods for GPS trajectories are in constant evolution due to the interest aroused in part of the scientific community. 
With the development of clustering algorithms considered traditional, improvements to these algorithms and even unique methods considered as ''novelty'' for science have emerged. 
This work aims to analyze the scientific production that exists around the topic ``GPS trajectories clustering'' by means of bibliometrics. 
Therefore, a total of 559 articles from the main collection of Scopus were analyzed, previously filtering the generated sample to discard any article that does not have a direct relationship with the topic to be analyzed. 
This analysis establishes an ideal environment for other disciplines and researchers, since it provides a current state of the trend of the subject of study in their field of research.

## Requirements

1. Installation of R ([The R project](https://www.r-project.org/))
2. Bibliometrix package
- For install use the command `install.packages("bibliometrix")`
3. Vosviewer executable ([VOSviewer](https://www.vosviewer.com/))

## Used data

Exported data from Scopus  [scopus.3-2002-2023.csv](https://github.com/gary-reyes-zambrano/Bibliometric-Analysis-for-GPS-Trajectory-Clustering/blob/main/Scopus_Export_2002-2023_(Extracted%20on%2025-jan-2024).csv)

## Extraction process

1. Search in Scopus
2. Terms included in the search:
- GPS Trajectory Clustering
3. Manual selection of articles based on keywords:
- `trajectory clustering`, `GPS trajectories`, `clustering methods` and related terms.

<!-- ### Terminos excluidos -->

## General description

### General Information
- I1. Overview > Main Information

### Tables
- Table 1. Main areas of research assigned to the sample papers.

Manual compilation of the statistical according to the Scopus page.

- Table 2. Number of articles published per year.

`bibliometrix > Overview > Annual Scientific Production`

- Table 3. Ten countries of corresponding authors.

`bibliometrix > Authors > Countries > Corresponding Author's Countries`

- Table 4. Top ten total citations by country.

`bibliometrix > Authors > Countries > Most Cited Countries`

- Table 5. The ten most relevant sources.

`bibliometrix > Sources > Most Relevant Sources`

- Table 6. The ten most cited articles, arranged in descending order by number of citations.

`bibliometrix > Documents > Documents > Most Global Cited Documents`

- Table 7. Most productive authors.

`bibliometrix > Authors > Authors > Most relevant Authors`

- Table 8. Main keywords.

`bibliometrix > Documents > Most Frequent Words`

(In options choose Author KeyWord or KeyWord Plus)

- Table 9. Entropic concentration index (H) of the selected variables.

Entropic concentration index (H) according to Shanon's entropy (https://doi.org/10.1002/j.1538-7305.1948.tb01338.x).
It uses Table 7, Table 5, Table 3, Table 1, and Table 6.

- Table 10. Observed distribution of the number of authors who wrote a given number of articles and adjusted values of Lotka's law.

bibliometrix > Authors > Authors > Lotka Law


### Figures
- Figure 1. Strategic diagram of KeyWords Plus generated with bibliometrix.

`bibliometrix > Conceptual Approach > Network Approach > Thematic Map`

Parameter Settings:
| **Option** | **Value** |
| ---- | ---- |
| Field |  Keywords Plus    |
| Number of Words | 50 |
| Min Cluster frequency | 5 |
| Number of Labels| 1 |
| Label size | 0.3 |
| Community Repulsion | 0 |
| Clustering Algorithm | Walktrap |

*Note:* The distribution of the specific terms related to each topic is only visible in the interactive web interface provided by biblioshiny.

- Figure 2. Strategic diagram of the authors' keywords generated with bibliometrix.
`bibliometrix > Conceptual Approach > Network Approach > Thematic Map`

Parameter Settings:
| **Option** | **Value** |
| ---- | ---- |
| Field | Author's Keywords |
| Number of Words | 50 |
| Min Cluster frequency | 5 |
| Number of Labels| 1 |
| Label size | 0.3 |
| Community Repulsion | 0 |
| Clustering Algorithm | Walktrap |

*Note:* The distribution of the specific terms related to each topic is only visible in the interactive web interface provided by biblioshiny.

- Figure 3. Thematic evolution of the authors' keyWord Plus generated with bibliometrix.
bibliometrix > Conceptual Approach > Network Approach > Thematic Evolution

Parameter Settings:
| **Option** | **Value** |
| ---- | ---- |
| Field |  Keywords Plus |
| Number of Words | 50 |
| Min Cluster frequency | 5 |
| Weight index | Inclusion Index weighted by Word-Occurences |
| Min Weight Index | 0.1 |
| Label size | 0.3 |
| Number of labels | 3 |
| Clustering Algorithm | Walktrap |
| Number of Cutting Points | 1 |
| Cutting Year | 2018 |

- Figure 4. Thematic evolution of the authors' keyWords generated with bibliometrix.
bibliometrix > Conceptual Approach > Network Approach > Thematic Evolution

Parameter Settings:
| **Option** | **Value** |
| ---- | ---- |
| Field | Author's Keywords |
| Number of Words | 50 |
| Min Cluster frequency | 5 |
| Weight index | Inclusion Index weighted by Word-Occurences |
| Min Weight Index | 0.1 |
| Label size | 0.3 |
| Number of labels | 3 |
| Clustering Algorithm | Walktrap |
| Number of Cutting Points | 1 |
| Cutting Year | 2018 |

- Figure 5. Map of word clouds in titles and abstracts (full count), generated with VOSviewer.


- Figure 6. Map of word clouds in titles and abstracts (binary count), generated with VOSviewer.


- Figure 7. Cloud map of journals where articles on "GPS trajectory clustering" are published, generated with VOSviewer.


- Figure 8. Cloud map created from authors with journal papers on "GPS trajectory clustering", generated with VOSviewer.

