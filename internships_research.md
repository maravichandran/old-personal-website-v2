---
layout: page
title: Internships/Research
order: 2
---

## Internships

### ML for Performance Prediction @ MongoDB
During my summer 2021 internship at MongoDB, I worked on a project to use machine learning to predict whether a set of performance tests will have a performance regression given a set of code changes. Using Python, I scraped commit and diff data from the mongodb/mongo git repository and used a variety of data processing and feature engineering techniques, including random downsampling and one-hot encoding. I tried a variety of linear, tree-based, and other machine learning models and achieved results that exceeded the team's expectations, with the passive-aggressive model having a 0.881 accuracy, a 0.787 F1 score, and 0.909 ROC-AUC. Performance testing is currently an expensive and time-consuming endeavor at MongoDB, and this project will help reduce unnecessary testing, thereby reducing cost and and increasing development velocity. 

### Evergreen CI Data Pipeline @ MongoDB
During summer 2020, I worked as a Software Engineering Intern at [MongoDB](https://www.mongodb.com/). My co-intern and I created a data pipeline within the [Evergreen](https://evergreen.mongodb.com/) continuous integration (CI) system that logs system metrics on the hosts running the CI tests, transforms them into structured data, and stores them in the data sink for access via a REST API, enabling diagnosis of system failures via machine learning and visualization of the system metric data. My code is open-source and can be found in the [Cedar](https://github.com/evergreen-ci/cedar), [FTDC](https://github.com/mongodb/ftdc), and [Evergreen](https://github.com/evergreen-ci/evergreen) repositiories. 

### Sales and Trading Summer Analyst @ Bank of America Merrill Lynch
During my summer 2019 internship, I assisted with market research and analysis, networked with individuals across the firm, completed training on financial markets, securities, and financial statements and valuation, and delivered three presentations to trading desks: 
* Proposed buying TWLO stock to the Equity Swaps desk, and designed and priced two hedges for the trade, including constructing a custom basket of equities and an options collar
* Presented an equity-linked auto-callable structured note’s advantages for clients, payoff scenarios, and hedging strategies to the Structured Notes desk
* Proposed buying five-year swap spreads, based on the Fed’s Standing Repurchase Facility and termination of balance sheet unwinding, to the Global Rates team

## Research

### Deep Learning for Alzheimer's Disease Genomics @ Oxford
I completed my Oxford MSc in CS dissertation under the supervision of [Prof. Alejo Nevado-Holgado](https://www.psych.ox.ac.uk/team/alejo-nevado-holgado). In this project, I applied transformer neural network models and support vector machine (SVM) models to whole genome sequencing data to predict presence of Alzheimer’s disease. The transformer model was unable to find a signal in the Alzheimer’s Disease Neuroimaging Initiative dataset, but the SVM models were able to find a predictive signal on many single nucleotide polymorphisms within the genes tested. The results suggested that SVM models are more effective when applied to small datasets with limited signal, and that transformers require a larger dataset or greater amount of signal to be effective. To our knowledge, this is the first study applying neural networks to unbroken stretches of DNA sequencing data to attempt the prediction of a phenotypic trait. 

### Data Science for Smart Cities @ Rutgers CS
I was a Research Assistant in [Prof. Desheng Zhang's lab](https://people.cs.rutgers.edu/~dz220/) from 2020-2021. I worked on a project to develop privacy-preserving conflict detection and resolution of smart city services using secure multi-party computation. I also created data visualizations for smart city services in Newark, NJ and Shezhen, China. 

### Computational Genomics for Osteosarcoma @ NIH
During Summer 2018, I worked on computational genetics for osteosarcoma in [Dr. Paul Meltzer's lab](https://ccr.cancer.gov/staff-directory/paul-s-meltzer) at the National Cancer Institute, National Institutes of Health (NIH) in Bethesda, MD. I analyzed next-generation sequencing data to search for large-scale structural rearrangements in the DNA sequences and improved the accuracy of a program to identify these mutations using a logistic regression model.

### Sustainable Cement Nanostructure @ Princeton
During Summer and Fall 2016, I worked in the [Sustainable Cements Group](http://white.princeton.edu/) at Princeton University, mentored by Prof. Claire White. Concrete production accounts for 8% of global CO2 emissions, and the lab studies eco-friendly cement alternatives. I investigated the impact of sulfate attack on the atomic structure of alkali-activated cement by identifying atomic bonds and conducting X-Ray Pair Distribution Function analysis on data from a particle accelerator. Here is a [poster](https://maravichandran.github.io/ISEF_poster.pdf) summarizing my work that I presented at ISEF (International Science & Engineering Fair). 

