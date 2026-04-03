
# 🎬 2. Amazon Prime Video Dashboard  

---

## 📌 Dataset Overview

This dataset contains metadata of streaming content available on Amazon Prime Video. It is used to analyze content distribution, genre trends, and platform content strategy.

- **Total Titles:** 9,687
- **Content Types:** Movies + TV Shows
- **Scope:** Global streaming catalog

---

## 📌 Data Source

The dataset is derived from publicly available streaming catalog datasets such as:
- Kaggle datasets
- TMDB-based aggregations
- Open-source OTT content libraries

> Note: Dataset is cleaned and structured for BI analysis purposes.

---

## 📊 Key Attributes

| Field Name | Description |
|------------|-------------|
| Title | Name of the movie or TV show |
| Type | Content type (Movie / TV Show) |
| Genre | Category or categories of content |
| Country | Production or availability region |
| Release Year | Year of release |
| Rating | Age classification (13+, 16+, etc.) |
| Director | Content director (if available) |
| Duration | Runtime or episode length |

---

## 🧹 Data Cleaning & Transformation

The dataset underwent structured preprocessing:
    - Parsed multi-genre fields into structured categories
    - Standardized rating system (e.g., 13+, 16+, 18+)
    - Converted release date into **year-only format**
    - Normalized country field for aggregation consistency
    - Removed records with critical missing metadata
    - Flattened nested categorical fields for BI modeling

---

## ⚠️ Assumptions
- Each title is treated as an independent content unit
- Multi-genre entries are split into normalized categories
- Missing metadata is retained only if core fields are valid
- Ratings are standardized for comparative analysis

---

## 🎯 Analytical Purpose

The dataset enables:
- Content distribution analysis (Movies vs TV Shows)
- Genre dominance evaluation
- Content growth trend tracking
- Geographic content mapping
- Audience rating segmentation
