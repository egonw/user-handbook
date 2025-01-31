---
layout: page
title: FAIRness and data quality scores
permalink: /FAIRification/FAIRnessScores/
parent: FAIRification
description_long: Documentation of ongoing activities and approaches to evaluate the FAIRness and quality of datasets.
has_children: false
has_references: true
nav_order: 303
---

# FAIRness and data quality scores
Even if quality evaluation of datasets is a highly active area of research, we will cover current approaches and try to stay up-to-date with the information.
{: .lead }

## FAIRness scores
### FAIR Badge System

![]({{ site.baseurl }}/images/FAIRification/FAIR-Badges.jpg)

This system was proposed as a proxy for data quality assessment, and aims to operationalise the original FAIR principles to ensure no interactions among the four dimensions in order to ease scoring. The system then considers Reusability as the resultant of the other three, i.e. the average FAIRness score is then (F+A+I)/3=R.

[Assessing the FAIRness of Datasets in Trustworthy Digital Repositories: a 5 star scale](https://indico.cern.ch/event/588219/contributions/2384979/attachments/1426152/2188462/Dillo_Doorn_-_Assessing_FAIRness_CERN_Geneva_13-03-2017-3.pdf)
{: .more-link .more-link--slides}

[FAIR data assessment tool](http://blog.ukdataservice.ac.uk/fair-data-assessment-tool/)
{: .more-link .more-link--app}

### GO FAIR
A team of FAIR principles authors and drivers have published a core set of semi-quantitative metrics for the evaluation of FAIRness.

[GO FAIR Metrics for the evaluation of FAIRness](https://www.go-fair.org/2017/12/11/metrics-evaluation-fairness/)
{: .more-link .more-link--webpages}

### The 5-star deployment scheme
A very early evaluation of "how Findable data is" was proposed as part of a [post on linked data](https://www.w3.org/DesignIssues/LinkedData.html) by Tim Berners-Lee was published on the W3C website.

|---|---|
|★| Available on the web (whatever format) but with an open licence, to be Open Data|
|★★| Available as machine-readable structured data (e.g. excel instead of image scan of a table)|
|★★★| As (2) plus non-proprietary format (e.g. CSV instead of Microsoft Excel)|
|★★★★| All the above, plus: Use open standards from W3C (RDF and SPARQL) to identify things, so that people can point at your stuff|
|★★★★★| All the above, plus: Link your data to other people’s data to provide context|

## Data quality scores
### Klimisch score
Klimisch et al. (Klimisch et al., 1997) developed a scoring system to assess the reliability of data from toxicological and ecotoxicological studies [12]. This rating system has been extended to physico-chemical studies and is now accepted by many regulatory authorities and organisations. ECHA's IUCLID 6 software includes rationale for assigning Klimisch scores for toxicology testing, based on utilisation of standard assays. To automate the process of assigning Klimisch scores, [ToxRTool (Toxicological data Reliability Assessment Tool)](https://publications.jrc.ec.europa.eu/repository/handle/JRC51252) (Schneider et al., 2009), an Excel-based tool, was developed by ECVAM to provide comprehensive criteria and guidance for evaluations of the inherent quality of toxicological data.

### GuideNano score
The Klimisch score was extensively considered and adapted for application to nano studies within the GUIDEnano project.

<img src="{{ site.baseurl }}/images/FAIRification/GuideNano-Scoring.png" />
**Figure**. The scoring system related to test design and reporting considerations developed following the principles of
the Klimisch score (K score). In addition, a scoring system based on the physicochemical properties that have been
characterised and reported for the NM, including properties characterised in the exposure medium was developed (S
score). These two scores (K and S) are combined to obtain an overall quality score (Q score) that can be used to select
studies, to weight different studies, and/or to introduce uncertainty factors in the risk assessment process (Fernandez-Cruz et al., 2018).
{: .caption }

References
{: .references-header }
- Fernandez-Cruz et al., 2018: Fernández-Cruz, M. L.; Hernández-Moreno, D.; Catalán, J.; Cross, R. K.; Stockmann-Juvala, H.; Cabellos, J.; Lopes, V. R.; Matzke, M.; Ferraz, N.; Izquierdo, J. J.; Navas, J. M.; Park, M.; Svendsen, C.; Janer, G. Quality Evaluation of Human and Environmental Toxicity Studies Performed with Nanomaterials – the GUIDEnano Approach. <i>Environ. Sci.: Nano</i> <b>2018</b>, <i>5</i> (2), 381–397. <a href="https://doi.org/10.1039/C7EN00716G">https://doi.org/10.1039/C7EN00716G</a>.
- Klimisch et al., 1997: Klimisch, H.-J.; Andreae, M.; Tillmann, U. A Systematic Approach for Evaluating the Quality of Experimental Toxicological and Ecotoxicological Data. <i>Regulatory Toxicology and Pharmacology</i> <b>1997</b>, <i>25</i> (1), 1–5. <a href="https://doi.org/10.1006/rtph.1996.1076">https://doi.org/10.1006/rtph.1996.1076</a>.
- Schneider et al., 2009: Schneider, K.; Schwarz, M.; Burkholder, I.; Kopp-Schneider, A.; Edler, L.; Kinsner-Ovaskainen, A.; Hartung, T.; Hoffmann, S. “ToxRTool”, a New Tool to Assess the Reliability of Toxicological Data. <i>Toxicology Letters</i> <b>2009</b>, <i>189</i> (2), 138–144. <a href="https://doi.org/10.1016/j.toxlet.2009.05.013">https://doi.org/10.1016/j.toxlet.2009.05.013</a>.
{: .references }
