Characterization of OHDSI regional/national databases: understanding diagnostic failures in OHDSI global network studies
=============

<img src="https://img.shields.io/badge/Study%20Status-Repo%20Created-lightgray.svg" alt="Study Status: Repo Created">

- Analytics use case(s): Characterization, Population-Level Estimation
- Study type: Methods Research
- Tags: regional, database, database characterisation
- Study lead: Evelyn Goh
- Study lead forums tag: e0983111 (https://forums.ohdsi.org/u/e0983111/summary)
- Study start date: 5 May 2026
- Study end date: -
- Protocol: **-**
- Publications: -
- Results explorer: -

Distributed network studies in the OHDSI community rely on three main diagnostic metrics: absolute standard difference of the mean (ASDM), empirical equipoise, and EASE. These metrics form the basis for evaluating whether a given database contributes interpretable effect estimates. In a previously conducted study, non-North American (N. Am) databases, particularly from Asia-Pacific (APAC) and Europe, were seen to have disproportionately failed diagnostics in an OHDSI multi-region study. 

As most of the non-U.S. databases passed EASE but failed on one or both of ASDM or empirical equipoise, structural covariate sparsity became a leading hypothesis. Low prevalence of FeatureExtraction covariates in non-N. Am databases produces numerically unstable ASMD estimates post-matching, collapses preference score distributions, and inflates EASE. If the pre-existing diagnostic framework, developed based on North American/U.S. databases, are systematically excluding non-N. Am databases, an adapted framework may need to be developed to encourage additional participation in non-N. Am/regional databases. As such, this study explores the characterization of such databases to understand patterns that may be helpful in diagnosing reasons for systematic failure of objective diagnostics. 

The objective of this study is to systematically characterise how database structural differences manifest in diagnostic performance across OHDSI network studies between North American and non-North American databases across a sample of multi-database OHDSI network studies, and to determine whether these differences are consistent across studies, targets, and outcomes.  

Specifically:
•	To identify which diagnostic criteria (covariate balance (ASMD), empirical equipoise, or empirical calibration (EASE)) are most strongly associated with database regional origin, and to characterise the domain-specificity of covariate missingness patterns driving these failures.
•	To quantify covariate missingness in non-North American databases and compare patterns across regions and OMOP domains, determining whether missingness is generalised or concentrated in specific data domains (condition history, drug exposure, procedures, measurements, visits).
•	To evaluate negative control estimate distributions across databases and assess whether databases that fail primary OHDSI diagnostics produce empirical null distributions consistent with passing databases, providing an empirical basis for distinguishing structural data differences from genuine analytical bias.
•	To assess the consistency of diagnostic failure patterns across studies with different drug classes, therapeutic areas, and outcome definitions, testing whether the patterns observed in the GLP-1/liver injury study replicate across the broader network study sample.
•	To produce a database-level characterisation taxonomy (a typology of structural database profiles with associated expected diagnostic behaviour) for use as a pre-study planning tool by investigators designing future OHDSI network studies involving APAC databases.

