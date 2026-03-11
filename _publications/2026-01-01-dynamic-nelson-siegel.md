---
title: "Dynamic Nelson Siegel Model with Time-Varying Neural Factor Loadings"
collection: publications
category: working-papers
permalink: /publication/2026-01-01-dynamic-nelson-siegel
excerpt: 'This paper introduces neural network-predicted factor loadings in the dynamic Nelson-Siegel yield curve model for simultaneous analysis and forecasting of interest rates across different maturities.'
date: 2026-01-01
venue: 'Working Paper'
citation: 'Kooiker, S., van Brummelen, J., Schaumburg, J., & Zamojski, M. (2026). Dynamic Nelson Siegel Model with Time-Varying Neural Factor Loadings. <i>Working Paper</i>.'
---

**Authors:** Sicco Kooiker, Janneke van Brummelen, Julia Schaumburg, and Marcin Zamojski

**Abstract:**

In this article, we introduce neural network-predicted factor loadings in the dynamic Nelson-Siegel yield curve model for simultaneous analysis and forecasting of interest rates across different maturities. The classical Nelson-Siegel model has been extended to include vector autoregressive factors and time-varying factor loadings, yet the functional form of these loadings has remained arbitrary despite their recognized importance. We address this limitation by developing a flexible approach that learns factor loadings through two shallow neural networks. Our simulation study shows that a nine-parameter neural network can closely approximate traditional Nelson-Siegel factor loadings. These neural networks improve both in-sample and out-of-sample filtered estimates of the US Treasury bond yield curve. Recognizing the similarity between Stochastic Gradient Descent and score-driven filters, we extend our approach by allowing neural network parameters to evolve in a score-driven manner. We integrate these dynamics within the Kalman filter state space framework to create a simultaneous optimization routine. Our empirical study demonstrates the validity of our method compared to traditional approaches in yield curve forecasting up to one year ahead.

**Presentations:**
- ECB Conference on Forecasting Techniques, Frankfurt, Germany (2026)
- FinEML Conference in Financial Econometrics and Machine Learning, Rotterdam, Netherlands (2025)
- ISF Conference, Beijing, China (2025)
