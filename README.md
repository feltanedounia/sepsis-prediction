# Sepsis Prediction

## Overview

This project builds a machine learning pipeline to predict the onset of sepsis in ICU patients ahead of clinical diagnosis, using time-series vitals, labs, and demographic data. The goal is early warning: flagging at-risk patients hours before sepsis is clinically confirmed, giving care teams a window to intervene.

## Motivation

Sepsis is a leading cause of in-hospital mortality, and outcomes are highly time-sensitive — every hour of delayed treatment measurably increases mortality risk. Most diagnoses happen only after clinical criteria are already met, which is often too late for optimal intervention. An early-warning model that flags risk before onset could give clinicians a meaningful head start.

## Dataset

- **Source:**
- **Size:**
- **Time window / features used:**
- **Label definition (Sepsis-3 criteria, onset window, etc.):**

## Problem Framing

Framed as a binary classification / early-warning task: given a patient's clinical trajectory up to time *t*, predict the probability of sepsis onset within a defined future window (e.g., 6 hours ahead). This prioritizes lead time over simple retrospective classification.

## Approach / Methodology



## Models



## Results

| Model | Metric | Value |
|-------|--------|-------|
|       |        |       |

## Key Findings



## Limitations

- Class imbalance: septic cases are a small fraction of ICU admissions.
- Label noise: sepsis onset time depends on the labeling criteria used (e.g., Sepsis-3), which itself involves some clinical judgment.
- Generalization: models trained on a single-source dataset may not transfer well to other hospitals or patient populations.

## Project Structure

```

```

## How to Run

```bash

```

## Requirements

```

```

## Future Work

- Validate on an external dataset to test generalization across hospitals.
- Explore explainability tools (e.g., SHAP) to make predictions clinically interpretable.
- Deploy as a simple web app/API for demo purposes.

## References

- Singer, M. et al. (2016). The Third International Consensus Definitions for Sepsis and Septic Shock (Sepsis-3).
- PhysioNet/CinC Challenge 2019: Early Prediction of Sepsis from Clinical Data.

## Author

Doun
