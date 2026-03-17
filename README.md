# iip-contract-classification-integrity-hhs

# 🗂️ HHS Contract Expiration — Classification Governance & Integrity Analysis

**Skills demonstrated:** Data governance · NAICS taxonomy classification · Data Field Separation · Multi-dimensional integrity analysis · Downstream use case planning · Public sector data · Looker visualization

## 📋 Overview

This project is based on publicly available government contract data and applies classification governance and integrity analysis principles to a dataset of 17,773 Health & Human Services (HHS) contracts expiring between FY2023 and FY2026. The raw data was assessed, restructured, and normalized to support meaningful analysis across four dimensions: company, agency, state, and industry classification.

The goal was not simply visualization, but to showcase how an Information Integrity Professional can analyze raw data and provide various starting points for teams to use further downstream.

## ❓ The Problem

Public contract data is available but not automatically useful.  Initially, without intervention and analysis, the raw data tells what contracts existed and the metadata assigned to them. However, that is only surface level. 

When I work with raw data I consider how that can be best utilized downstream with case planning by anticipating who may need what insight along the way.  

In the case of the HHS contracts expiry file this can be done by:

* **Marketing use:** NAICS code frequency to identify industry concentration and opportunity
* **Financial use:** Value at risk by expiration frequency, filterable by agency, state, and industry
* **Government use:** Which departments hold the most contracts and where volume is concentrated
* **Broader stakeholder use:**  Outputs usable by vendors, product teams, client-facing staff, internal strategy, lobbying, or procurement planning

Anticipating downstream uses prior to data organization allows for usable foundational points for stakeholders in a form that is ready to use or transform further downstream.

## 🔧 What I Built
A structured multi-sheet workbook built from the raw HHS contract expiration file.
Workbook tabs:

* **HHS Contract Expiration List:** Raw source data, unmodified, 17,773 records across 13 fields
* **Formatted Sheet:** Expanded to 17 fields with separated NAICS numeric and description columns, extracted contract start year, and extracted contract expiry year
* **Contract Expiry Company Data:** Company and vendor-level analysis  
* **Contract Expiry Agency Data:** Departmental volume and concentration analysis  
* **Contract Expiry State Data:** Geographic distribution analysis  
* **Contract Expiry NAICS Data:** Sector-level expiration pattern analysis  

The raw sheet is preserved unmodified for user reference and to keep the source data intact and auditable.

## 🎬 Available vs. Actionable

As with any raw data set, the HHS contract expiry file contains a variety of data points presenting simply that...data.  Yet data while plentiful is not the same as information.  It is available, but unorganized fact that has yet to grow into its potential as intelligent information that is useful, actionable, and allows for stakeholders to fulfill a purpose.

By planning potential purpose for these data points downstream either through separating classification from description, extracting fiscal year from date fields, or organizing records across dimensional analysis tabs, I've created a workbook that turns available data into actionable usable intelligence.

## 📊 Visualization Output
The following dashboard shows how the NAICS code classification data could be used by a stakeholder.  The dashboard highlights contract expiry concentration by industry classification across the FY2023–FY2026 timeframe.  Arranging the data in such a way shows which NAICS or professional services category contain the highest amounts of contract expiration.  This information would be beneficial to marketing, procurement, and stakeholder planning teams.

<img width="1126" height="797" alt="image" src="https://github.com/user-attachments/assets/ba874b71-529b-40ae-8dda-cfb3252a0739" />

[Alt text: "Bar chart and pie chart showing percentage of total HHS contracts expiring FY2023 through FY2026 by NAICS code. The largest segment is NAICS 541519 at 14.9%, followed by 541611 at 10.2% and 334516 at 7.1%. All other categories combined represent 42.7%."]

This visualization made in Google Looker represents one possible downstream output. The workbook's structure supports additional analysis by agency, state, company, and fiscal year depending on stakeholder needs.

## ⚙️ Tools Used
* **Google Sheets:** Data formatting, field separation, formula logic, and multi-dimensional analysis tabs
* **Microsoft Excel (.xlsx):**  Export format for portfolio distribution
* **Looker:** Visualization layer for NAICS expiration pattern analysis

## ⚠️ Disclaimer

The workbook, sheets therein, and dashboard graphic were created by me for use in the portfolio only as a representation of various skill sets utilized in their making.  This analysis represents my own work and interpretation and does not reflect any official position or endorsement by HHS or Data.gov.

**Note:** This analysis reflects the dataset as available at the time of access. The source data may have been updated since this workbook was created.

*A.H. Faria | Data Governance & Metadata Professional*

## 🪪 Raw Data File Source Dataset

Title: HHS Expiring Contracts List for FY23 - FY26

Publisher: U.S. Department of Health and Human Services

Maintainer: Kelley Smith

First Published: September 1, 2023

Last Modified: July 3, 2025

Access Level: Public

Source: https://catalog.data.gov/dataset/hhs-expiring-contracts-list-for-fy23-fy26

Citation Creation Date: March 17, 2026

Analysis Date: February 26, 2026
