# Case Study: Private Equity Operations Performance Optimization

## 1. Executive Summary
In private equity fund operations, General Partners (GPs) and fund administrators process thousands of capital call notices, distribution notices, quarterly reports, and tax packs across platforms like Investran, eFront, and Allvue. Inaccuracies or SLA delays in document indexing delay capital deployment and cause disputes.

This project tracks turnaround time (TAT), First-Time-Right (FTR) accuracy, and Service Level Agreement (SLA) compliance across operational documents.

## 2. Core Operational Metrics
* **Total Documents:** Ingested notices and reports.
* **Accuracy Rate (%):** Percentage of documents passing Quality Check (QC) without errors.
* **Processing Time:** Average minutes taken per document type.
* **SLA Compliance:** Percentage of documents completed within the target deadline.

## 3. Data Architecture
* **Source:** Excel / CSV (`document_operations.csv`)
* **Cleaning:** Power Query for data formatting and type conversion.
* **Calculations:** DAX measures for dynamic filtering by platform and analyst.

## 4. Key Takeaways
* **Main Bottleneck:** Quarterly Financial Reports take the longest time due to multi-page review requirements.
* **Common Errors:** Metadata Mismatches and Incorrect Amounts make up the majority of QC rejections.
* 
