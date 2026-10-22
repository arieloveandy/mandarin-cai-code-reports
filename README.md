# Mandarin cai Polysemy: Analysis Reports

This repository provides supplementary computational reports for a corpus-based investigation of the semantic organisation and contextual identification of five working senses of the Mandarin adverb cai (才).

The study combines Behavioural Profile (BP) clustering with conditional inference trees to examine sense-level distributional similarities and token-level contextual distinctions.

## Study Overview

The analysis draws on 2,000 tokens sampled from the BCC and CCL corpora, with 400 tokens representing each of five working senses:

- CAI1: Temporal-proximity (recent)
- CAI2: Delayed-realisation
- CAI3: Low-quantity
- CAI4: Prerequisite–restrictive
- CAI5: Emphatic–contrastive

Each token was annotated for 30 contextual predictors covering lexical, syntactic, semantic and constructional properties.

## Analytical Methods

Two complementary approaches were employed.

### Behavioural Profile Clustering

Hierarchical clustering was conducted on sense-level contextual distributions, using Euclidean distance and Ward.D2 as the primary specification. Robustness assessments included alternative clustering specifications, silhouette analysis and bootstrap procedures.

### Conditional Inference Trees

Conditional inference trees were used for token-level sense classification based on contextual predictors. Predictive performance was evaluated using a stratified, sentence-grouped training–holdout split. Additional analyses examined variable sensitivity and terminal-node configurations.

## Analysis Reports

The repository provides the following reports:

- [Behavioural Profile Clustering](docs/clustering.html): Hierarchical clustering, distributional profiles, silhouette analysis, bootstrap stability and AU/BP branch support.
- [Conditional Inference Tree Analysis](docs/decision_tree.html): Classification performance, confusion matrices, splitting structures and terminal-node statistics.
- [Report Index](docs/index.html): An overview of both analyses.

The HTML reports contain analysis code, statistical outputs, tables and figures. They are self-contained and can be downloaded and opened in a web browser.

## Data Availability

The underlying token-level corpus dataset is not publicly redistributed because the source materials originate from the BCC and CCL corpora and may be subject to licensing and redistribution restrictions.

The reports document the analytical procedures and resulting outputs. Full computational reproduction requires access to the appropriately licensed corpus data and corresponding annotations.

## Reproducibility

The reports are intended to facilitate methodological inspection and assessment of the analytical results. They include the R code used for the principal analyses, together with reported statistical summaries and visualisations.

The materials are provided as supplementary research documentation.
