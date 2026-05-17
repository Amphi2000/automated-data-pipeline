### Automated Data Collection & Scoring Pipeline

End-to-end pipeline for automated prospect discovery, data extraction, deduplication, scoring, and outreach sequencing. Built to eliminate manual data work across thousands of targets.

---

#### 1. `data_collector` — Automated Data Collection
Scrapes and collects target URLs at scale. Supports queue-based batch processing with automatic pagination.

#### 2. `deduplication_engine` — Data Deduplication & Scoring
Deduplicates by root domain and applies keyword-based scoring to keep the highest-quality record per source.

#### 3. `contact_extractor` — Contact Extraction & Ranking
Visits each URL, extracts contact information, scores by relevance, and exports a structured ranked CSV.

#### 4. `outreach_automation` — Automated Sequence Engine
Google Apps Script automation handling sequenced delivery with rate limits, randomized timing, quota detection, and full Google Sheets logging.

---

#### How It Works
1. `data_collector` builds the initial dataset
2. `deduplication_engine` cleans and scores the data
3. `contact_extractor` enriches each record with contact info and relevance scores
4. `outreach_automation` sequences delivery automatically

#### Results
Reduced manual prospecting workload by ~90% across thousands of targets. Outputs clean structured CSV datasets ready for analysis or CRM import.

#### Tech Stack
JavaScript, Chrome Extension Manifest V3, Chrome APIs, Google Apps Script
