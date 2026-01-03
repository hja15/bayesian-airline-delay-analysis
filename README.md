# Bayesian Linear Regression for Airline Arrival Delays

This project presents a Bayesian linear regression analysis examining how weather-related factors influence airline arrival delays.  
Rather than focusing solely on point estimates, the analysis emphasizes probabilistic modeling, uncertainty quantification, and posterior interpretation.

**Project Website:**  
[View the Analysis](https://hja15.github.io/IDC6940_BayesianBandits/BLRproject.html)

---

## Project Overview

Airline arrival delays are influenced by a range of operational and environmental factors, with weather frequently cited as a major contributor.  
This project investigates the relationship between weather-related delay events and arrival delays using a Bayesian framework.

The primary goals of the analysis were to:
- Model arrival delays using Bayesian linear regression
- Quantify uncertainty in parameter estimates
- Interpret posterior distributions instead of relying on single-value coefficients
- Demonstrate applied Bayesian modeling using real-world transportation data

---

## Methodology

- **Model:** Bayesian Linear Regression  
- **Response Variable:** Arrival delay (minutes)  
- **Predictor(s):** Weather-related delay counts  
- **Inference Method:** Markov Chain Monte Carlo (MCMC)  
- **Software:** R (`brms` package)

Key steps included prior specification, MCMC sampling, convergence diagnostics, and posterior interpretation using credible intervals.

---

## Why a Bayesian Approach?

A Bayesian framework allows for:
- Direct probability statements about model parameters
- Explicit representation of uncertainty
- Greater interpretability in decision-making contexts
- Flexible model extension compared to traditional frequentist regression

These properties make Bayesian methods especially well-suited for applied problems involving uncertainty and variability, such as transportation delays.

---

## Technologies Used

- **R**
- **brms**
- **Bayesian statistics**
- **MCMC**
- **Data visualization**
- **GitHub Pages**

---

## Repository Notes

This repository intentionally contains only the final project website and this overview README.  
Supporting coursework files and drafts were excluded to maintain a clean, professional presentation focused on the final analysis.
