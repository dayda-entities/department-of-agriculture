---
title: Evaluating accuracy of DNA pool construction based on white blood cell counts
created: '2021-01-06T00:03:11.667434'
modified: '2021-02-10T19:07:03.182421'
state: active
type: dataset
tags:
  - Alleles
  - Blood
  - Blood Volume
  - Gene Frequency
  - Genotype
  - Genotyping
  - Np101
  - Sample Pooling
  - Spectrophotometers
  - White Blood Cell Count
  - White Blood Cells
groups: []
csv_url: 'https://data.nal.usda.gov/system/files/g.csv.gz'
json_url: ''
layout: post

---
<p>Pooling individual samples prior to DNA extraction can mitigate the cost of DNA extraction and genotyping; however, these methods need to accurately generate equal representation of individuals within pools. This data set was generated to determine accuracy of pool construction based on white blood cell counts compared to two common DNA quantification methods. Fifty individual bovine blood samples were collected, and then pooled with all individuals represented in each pool. Pools were constructed with the target of equal representation of each individual animal based on number of white blood cells, spectrophotometric readings, spectrofluorometric readings and whole blood volume with 9 pools per method and a total of 36 pools. Pools and individual samples that comprised the pools were genotyped using a commercially available genotyping array. ASReml was used to estimate variance components for individual animal contribution to pools. The correlation between animal contributions between two pools was estimated using bivariate analysis with starting values set to the result of a univariate analysis.</p>
<p>The dataset includes:<br />
1) pooling allele frequencies (PAF) for all pools and individual animals computed from normalized intensities for red (X) and green (Y); PAF = X/(X+Y).<br />
2) Genotypes or number of copies of B(green) allele (0,1,2).<br />
3) Definitions for each sample.</p>

