# Power BI Desktop Step-by-Step Build Guide

Follow these steps when you open Power BI Desktop on a computer.

### Step 1: Load Data
1. Open **Power BI Desktop**.
2. Click **Get Data** -> **Text/CSV**.
3. Select `document_operations.csv`.
4. Click **Close & Apply**.

### Step 2: Create DAX Measures
Click **New Measure** on the Home tab for each formula:

1. **Total Documents:**
   `Total Documents = COUNTROWS('document_operations')`

2. **Completed Documents:**
   `Completed Documents = CALCULATE(COUNTROWS('document_operations'), 'document_operations'[Processing Status] = "Completed")`

3. **Average Processing Time:**
   `Avg Processing Time (Mins) = AVERAGE('document_operations'[Processing Time])`

4. **Accuracy %:**
   `Accuracy % = DIVIDE(CALCULATE(COUNTROWS('document_operations'), 'document_operations'[Quality Check Status] = "Passed"), COUNTROWS('document_operations'), 0)`

5. **SLA Met %:**
   `SLA Compliance % = DIVIDE(CALCULATE(COUNTROWS('document_operations'), 'document_operations'[SLA Status] = "Met"), COUNTROWS('document_operations'), 0)`

### Step 3: Color Palette
* **Navy Blue:** `#0B2545`
* **Gold:** `#D4AF37`
* **Background:** `#F4F6F9`
* 
