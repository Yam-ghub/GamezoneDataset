# GamezoneDataset

## Data Cleaning
![PowerQuery]<img src="Photos/PowerQuery" width="500">

📥 1. Loaded Orders Sheet

Extracted the orders worksheet from the Excel source.

Accessed the raw sheet data for transformation.

🔄 2. Standardized Data Types

Converted PURCHASE_TS and SHIP_TS to Date type.

Converted categorical and ID fields to Text type:

MARKETING_CHANNEL

PURCHASE_PLATFORM

ORDER_ID

USER_ID

ACCOUNT_CREATION_METHOD

Ensured consistent data types for accurate downstream analysis.

🔍 3. Filtered Valid Purchase Dates

Removed rows with missing or invalid PURCHASE_TS values.

Ensured only valid transaction records remain.

🛠 4. Standardized Product Naming

Corrected inconsistent product naming for uniform reporting.

Prevented duplicate groupings caused by text variations.

❓ 5. Handled Missing Categorical Values

Replaced null values with "unknown" in key categorical columns.

Prevented null-related issues during aggregation and segmentation.

🗑 6. Removed Unnecessary Columns

Dropped unused or empty columns (e.g., Column12) to streamline the dataset.