# Exploring-Perturbation-Patterns-and-Impact-in-Adversarial-Machine-Learning---replication-package
This repository contains the replication package related to the Systematic Literature Review (SLR) in the field of Adversarial Machine Learning (AML).

It includes a comprehensive set of Excel files documenting each phase of the review process, from study identification to data extraction and synthesis. The objective is to ensure transparency, reproducibility, and applicability of the methodology and findings.

Contents

Below is a description of each file included in the replication package:

## 1.Database search

This file documents the initial search strategy performed across selected academic databases. It includes:
•	Names of the databases used (e.g., Scopus, IEEE Xplore, ACM Digital Library)
•	Search strings and Boolean queries
•	Dates of the search
•	Number of records retrieved per source

## 2.Study selection + inclusion/exclusion criteria

This file details the screening process applied to the studies identified through both database and citation-based searches. The inclusion and exclusion criteria were defined a priori and systematically applied across different stages to ensure a rigorous and transparent selection of the primary studies.
The Excel file is structured into multiple sheets, each representing a distinct filtering step. These steps include the removal of duplicate entries, the exclusion of incomplete records, and the elimination of publications that did not meet predefined criteria, such as workshop papers, preprints, survey articles, and short papers. The selection was further refined by considering only full research papers published in top-tier venues, specifically journals ranked as Q1 and conferences classified as A* or A.
To assess scientific quality and topical relevance, a scoring mechanism was implemented based on three components: number of citations, importance of the publication venue, and the paper's alignment with the topic of adversarial machine learning. Each study was assigned a composite score ranging from 0 to 1, calculated using a weighted combination of citations (0–3 points), venue ranking (1 or 2 points), and topic relevance (0–5 points). Only studies with a final score of at least 0.6 were retained.
Finally, the file includes a summary sheet that reports the number of studies excluded at each stage of the selection process, offering a clear overview of how the final dataset was constructed

## 3.Citation-based search + snowballing

This file presents the results of the backward and forward snowballing process carried out on a set of key papers. It documents the additional articles retrieved through this method and describes how the same predefined inclusion and exclusion criteria were systematically applied to these studies. The file also reports the final set of papers that were selected and included in the review as a result of the snowballing process.

## 4.Quality assessment + checklist

This file contains the results of the quality evaluation performed on the selected primary studies using a structured checklist. The assessment focused on two key aspects: whether the proposed attack or defense techniques are clearly defined, and whether appropriate evaluation metrics are used to measure model robustness.
Each of these aspects was rated using a three-level scale: "Yes" (assigned a score of 1), "Partially" (0.5), and "No" (0). For each study, a final quality score was calculated as the average of the two responses. Studies that reached or exceeded a predefined threshold score of 0.75 were considered of sufficient quality and retained in the final set.
The file includes a dedicated sheet for the checklist criteria and scoring rubric, a detailed table listing the individual quality ratings assigned to each study, and a summary sheet that provides an overview of the score distribution and the number of studies included or excluded based on quality. This ensures transparency and replicability of the quality assessment process.

## 5.Data extraction + form

This file contains the structured data extraction form used during the systematic literature review. It is designed to ensure consistency in capturing relevant information from all included studies. The form records general metadata such as title, authors, publication venue, year, and country of author affiliation.
In addition, it collects detailed information about the study’s objectives and context, including the machine learning models or algorithms employed, input data characteristics, application and solution domains, datasets used, machine learning tasks addressed, types of attacks or defenses discussed, and evaluation metrics adopted.
The file also includes fields describing the type of dataset, the perturbation pattern category and strength, and other relevant experimental details. Finally, it captures aspects related to impact and severity, such as the degradation of model performance due to attacks, security and robustness threats, and factors affecting severity and exploitability. All fields are structured in alignment with the research questions defined in the review protocol.

## 6.Graphics generation

This file contains the aggregated data and visual outputs used to support the synthesis and presentation of the review findings. It includes pivot tables and summary statistics that were used to analyze key aspects of the selected studies. The file also provides the data behind the graphs and figures included in the paper, such as publication trends over time and distribution across different application domains. These visualizations offer a clearer understanding of the research landscape and contribute to the interpretation and communication of the systematic review results.

