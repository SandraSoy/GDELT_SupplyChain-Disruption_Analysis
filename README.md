# 🌍 GDELT Supply Chain Disruption Analysis

Leveraging global news data and commodity price signals to detect and analyze supply chain disruptions in the food industry.

---

## 📌 Project Overview

This project explores how large-scale global news data from the GDELT Global Knowledge Graph (GKG) can be used to detect and analyze supply chain disruptions affecting essential food commodities such as meat, coffee, and eggs.

The objective was to combine real-time news intelligence with commodity pricing signals to better understand how geopolitical events, climate shocks, and transportation delays influence food supply chains.

---

## 🎯 Objective

* Identify global supply chain disruption events using theme-based filtering of GDELT data

* Focus analysis on high-impact food commodities (meat, coffee, eggs)

* Perform sentiment and tone analysis to isolate severe negative disruption signals

* Conduct geolocation-based clustering to identify regional stress zones

* Analyze temporal patterns to understand how disruptions evolve over time

* Explore integration of LLM-based techniques for commodity price and inventory forecasting

---

## 🗂 Data Sources

- GDELT Global Knowledge Graph (GKG) – Global event and news metadata

- USDA Market News Retail Reports – Commodity pricing data (https://www.marketnews.usda.gov/)

  **Note:** Due to dataset size and remote compute environment constraints, raw data and processing code are not included in this repository.

---

## ⚙️ Methodology

**Event Filtering**

  * Theme-based keyword extraction to isolate supply chain–related events

  * Commodity-specific filtering for food-related disruptions

**Sentiment & Tone Analysis**

  * Classified events by tone (positive, neutral, negative)

  * Flagged high-negative sentiment events as potential supply stress indicators

**Geospatial Analysis**

  * Mapped valid latitude/longitude coordinates

  * Identified geographic clusters of disruption activity

**Temporal Trend Analysis**

  * Examined daily event frequency by region

  * Tracked escalation patterns across commodities

**LLM Exploration (Research Extension)**

  * Investigated how Large Language Models could:

    * Summarize disruption clusters

    * Identify emerging risk signals

    * Support commodity price variation prediction

---

## 📊 Key Insights

* Food supply chains are highly sensitive to geopolitical and climate-driven disruptions.

* Severe negative-tone events often precede price fluctuations in certain commodities.

* Geographic clustering reveals concentrated stress regions rather than uniform global impact.

* Integrating LLM-based summarization enhances interpretability of large-scale news signals.

---

## 🛠 Tools & Technologies

- Python
  
- GDELT API / Big Data ingestion

- Sentiment and tone analysis

- Geospatial visualization

- Time-series exploration

- LLM-based experimentation

- USDA Market News pricing data

---

## 📌 Project Context

This project was conducted in a remote computational environment due to the scale of the GDELT dataset. Code and raw data are not included here because of data size constraints, but the analytical framework and methodology are documented above.
