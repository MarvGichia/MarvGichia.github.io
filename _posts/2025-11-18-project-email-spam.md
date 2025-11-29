---
title: "Email Spam & Phishing Detection System (Explainable AI)"
date: 2025-11-18 09:00:00 +0300
categories: [Projects]
tags: [Python, Flask, MachineLearning, Security, LIME]
description: "Python/Flask platform that detects phishing and spam emails with explainable ML intelligence."
---

## Project Overview

Python & Flask platform that ingests suspicious emails, runs a Naive Bayes + TF-IDF classification pipeline, and augments every prediction with LIME-based explanations, domain reputation checks, and analyst feedback loops.

### Key Capabilities

- Real-time classification workflow with background queueing for heavier analysis.  
- Integrated domain reputation checks, URL pattern signatures, DNS lookups, and header inspection.  
- User feedback loop updates the training corpus and re-tunes model weights.  
- Lightweight SQLite backend stores audit logs, analyst decisions, and continuous learning metrics.  
- Built-in accuracy reporting, pattern highlighting, and trust scores for SOC analysts.  

### Tool Stack

- Python, Flask, Bootstrap UI  
- scikit-learn (TF-IDF + Multinomial Naive Bayes)  
- LIME for explainability  
- SQLite for logging and lightweight persistence  

### Screenshots

![Main UI for email analysis](/assets/img/Projects/Emailspam/ui.png)  
*Main email input interface used for real-time spam and phishing analysis.*

![ML analysis and accuracy breakdown](/assets/img/Projects/Emailspam/analysissection.png)  
*Displays ML-driven classification using Naive Bayes + TF-IDF, highlights suspicious patterns, and shows accuracy scores.*

![Performance dashboard and feedback trends](/assets/img/Projects/Emailspam/statisticssection.png)  
*Shows performance metrics, user feedback trends, and model learning history.*

### Professional Summary

Delivered an explainable phishing-defense assistant that empowers analysts with transparent ML outcomes, reduces investigation time, and continuously improves via user-in-the-loop feedback.

