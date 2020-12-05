---
author-meta:
- Tessa Clarizio
- Jane Roe
- Jane Roe
- Jane Roe
- Jane Roe
- Jane Roe
bibliography:
- content/manual-references.json
date-meta: '2020-12-05'
header-includes: '<!--

  Manubot generated metadata rendered from header-includes-template.html.

  Suggest improvements at https://github.com/manubot/manubot/blob/master/manubot/process/header-includes-template.html

  -->

  <meta name="dc.format" content="text/html" />

  <meta name="dc.title" content="Predicting NO2 concentrations" />

  <meta name="citation_title" content="Predicting NO2 concentrations" />

  <meta property="og:title" content="Predicting NO2 concentrations" />

  <meta property="twitter:title" content="Predicting NO2 concentrations" />

  <meta name="dc.date" content="2020-12-05" />

  <meta name="citation_publication_date" content="2020-12-05" />

  <meta name="dc.language" content="en-US" />

  <meta name="citation_language" content="en-US" />

  <meta name="dc.relation.ispartof" content="Manubot" />

  <meta name="dc.publisher" content="Manubot" />

  <meta name="citation_journal_title" content="Manubot" />

  <meta name="citation_technical_report_institution" content="Manubot" />

  <meta name="citation_author" content="Tessa Clarizio" />

  <meta name="citation_author" content="Jane Roe" />

  <meta name="citation_author" content="Jane Roe" />

  <meta name="citation_author" content="Jane Roe" />

  <meta name="citation_author" content="Jane Roe" />

  <meta name="citation_author" content="Jane Roe" />

  <link rel="canonical" href="https://sfiala2.github.io/498_NO2_pred/" />

  <meta property="og:url" content="https://sfiala2.github.io/498_NO2_pred/" />

  <meta property="twitter:url" content="https://sfiala2.github.io/498_NO2_pred/" />

  <meta name="citation_fulltext_html_url" content="https://sfiala2.github.io/498_NO2_pred/" />

  <meta name="citation_pdf_url" content="https://sfiala2.github.io/498_NO2_pred/manuscript.pdf" />

  <link rel="alternate" type="application/pdf" href="https://sfiala2.github.io/498_NO2_pred/manuscript.pdf" />

  <link rel="alternate" type="text/html" href="https://sfiala2.github.io/498_NO2_pred/v/4136996cbb8b2927ee2a636e5c8f90b13f8d1ee4/" />

  <meta name="manubot_html_url_versioned" content="https://sfiala2.github.io/498_NO2_pred/v/4136996cbb8b2927ee2a636e5c8f90b13f8d1ee4/" />

  <meta name="manubot_pdf_url_versioned" content="https://sfiala2.github.io/498_NO2_pred/v/4136996cbb8b2927ee2a636e5c8f90b13f8d1ee4/manuscript.pdf" />

  <meta property="og:type" content="article" />

  <meta property="twitter:card" content="summary_large_image" />

  <link rel="icon" type="image/png" sizes="192x192" href="https://manubot.org/favicon-192x192.png" />

  <link rel="mask-icon" href="https://manubot.org/safari-pinned-tab.svg" color="#ad1457" />

  <meta name="theme-color" content="#ad1457" />

  <!-- end Manubot generated metadata -->'
keywords:
- markdown
- publishing
- manubot
lang: en-US
manubot-clear-requests-cache: false
manubot-output-bibliography: output/references.json
manubot-output-citekeys: output/citations.tsv
manubot-requests-cache-path: ci/cache/requests-cache
title: Predicting NO2 concentrations
...






<small><em>
This manuscript
([permalink](https://sfiala2.github.io/498_NO2_pred/v/4136996cbb8b2927ee2a636e5c8f90b13f8d1ee4/))
was automatically generated
from [sfiala2/498_NO2_pred@4136996](https://github.com/sfiala2/498_NO2_pred/tree/4136996cbb8b2927ee2a636e5c8f90b13f8d1ee4)
on December 5, 2020.
</em></small>

## Authors



+ **Tessa Clarizio**<br>
    · ![GitHub icon](images/github.svg){.inline_icon}
    [tessac2](https://github.com/tessac2)<br>
  <small>
  </small>

+ **Jane Roe**<br>
    · ![GitHub icon](images/github.svg){.inline_icon}
    [janeroe](https://github.com/janeroe)<br>
  <small>
  </small>

+ **Jane Roe**<br>
    · ![GitHub icon](images/github.svg){.inline_icon}
    [janeroe](https://github.com/janeroe)<br>
  <small>
  </small>

+ **Jane Roe**<br>
    · ![GitHub icon](images/github.svg){.inline_icon}
    [janeroe](https://github.com/janeroe)<br>
  <small>
  </small>

+ **Jane Roe**<br>
    · ![GitHub icon](images/github.svg){.inline_icon}
    [janeroe](https://github.com/janeroe)<br>
  <small>
  </small>

+ **Jane Roe**<br>
    · ![GitHub icon](images/github.svg){.inline_icon}
    [janeroe](https://github.com/janeroe)<br>
  <small>
  </small>



## Abstract {.page_break_before}


test commit on abstract


# 1. Introduction

NO2 is defined by the U.S. Environmental Protection Agency (EPA) as a criteria air pollutant, meaning it poses a risk to human and environmental health.  The primary National Ambient Air Quality Standard (NAAQS) is set at a 53 ppb annual average [@https://www.epa.gov/no2-pollution/primary-national-ambient-air-quality-standards-naaqs-nitrogen-dioxide]. NO2 can cause respiratory irritation and can aggravate respiratory diseases such as asthma (US EPA, n.d., B). NO2 can also react with other chemicals in the atmosphere to form both particulate matter (PM) and tropospheric ozone (US EPA, n.d., B). PM and ozone are also criteria air pollutants and are harmful to human health. NO2 also contributes to the formation of acid rain, smog, and nutrient pollution in coastal waters (US EPA, n.d., B). The primary source of NO2 emissions is fossil fuel combustion, particularly from traffic and power plants (US EPA, n.d., B). 

Therefore, understanding and predicting the spatial variability of NO2 emissions is of great importance to public health. However, prediction of air quality can be complicated due to the number of factors that affect local air quality, ranging from meteorology to land use. Machine learning models are a useful tool to interpret and find relationships in complex data. 

[introduce Bechle study…] Bechle et al (2015) explores the impact of.. [Grace please add here]

This report proposes a machine learning model to predict NO2 concentrations spatially. First, a literature review was undertaken to understand what machine learning models have typically performed well in predicting air quality. Next, an exploratory data analysis (EDA) was performed on the Bechle et al (2015) dataset. Finally, multiple linear regression, neural network and random forest models were built and results were compared to see which method had the lowest mean-squared error (MSE). 


# 2. Methods
## 2.1 Literature Review
### 2.1.1 PM2.5
### 2.1.2 AQI/API
## 2.2 Exploratory Data Analysis
## 2.3 Model
### 2.3.1 Multiple Linear Regression
### 2.3.2 Neural Networks
### 2.3.3 Random Forest
# 3. Results
# 4. Discussion 


## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>
