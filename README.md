# Grocery Price & Basket Optimizer

An automated grocery price tracking and basket optimization prototype designed to calculate single-store vs. split-store shopping trips and highlight potential household savings.

---

## Project Overview

This repository contains an early-stage proof of concept (PoC) exploring grocery price normalisation, missing item detection, and cost-comparison algorithms across competing supermarkets.

### Core Features
- **Single-Trip Comparison:** Calculates which supermarket offers the lowest total cost for a full basket.
- **Split-Trip Optimization:** Identifies the absolute lowest price per item across multiple retailers and calculates total potential savings.
- **Stock & Missing-Item Detection:** Flags unavailable or out-of-stock items and prevents incomplete baskets from being ranked as the cheapest option.

---

## Notice & Proprietary Rights

> **Strictly Personal Project – All Rights Reserved.**

This repository and its contents (including code, design architecture, and documentation) are part of a private, independent personal project. 

- **No Licence Granted:** No licence (open source or commercial) is granted to any individual, group, or organisation to copy, reproduce, fork, modify, distribute, sell, or create derivative works from this code.
- **Viewing Only:** Public visibility on GitHub is strictly for portfolio demonstration and controlled prototype testing purposes.
- **Unauthorised Use:** Scraping, redistributing, publishing, or incorporating this codebase into other projects without explicit written permission is strictly prohibited.

---

## Roadmap

1. [x] Interactive browser-based calculation prototype.
2. [ ] Dynamic data ingestion pipeline and product normalisation schemas.
3. [ ] Scheduled workflow automation via Claude API.
4. [ ] Cross-platform mobile client (iOS & Android).
