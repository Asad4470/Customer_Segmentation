# Customer Segmentation using RFM and Clustering

This project explores customer purchasing behavior using Recency, Frequency, and Monetary (RFM) features, compares multiple unsupervised clustering models, and adds four rule-based business segments for marketing interpretation.

## Files

- `Customer_Segmentation.ipynb` — Google Colab/Jupyter notebook with preprocessing, EDA, RFM analysis, model comparison, visualizations, four business segments, and Excel export.
- `customer_segmentation_complete_report.xlsx` — report with model comparison, per-customer labels, cluster profiles, and the `START HERE - Segment Guide` dashboard.

## How to run

1. Open the notebook in Google Colab.
2. Run the cells from top to bottom.
3. Upload the Online Retail dataset when prompted.
4. At the end, download the newly generated Excel report.

## Four business segments

The four business-friendly groups are created with rules based on RFM values, separate from the algorithm-generated ML clusters:

1. Champions / High Value
2. Loyal / Repeat Buyers
3. At Risk / Previously Frequent
4. New or Occasional / Low Engagement

Thresholds are calculated from the loaded dataset, so counts can change if the input data changes. The groups are intended to support interpretation and marketing ideas, not to guarantee business outcomes.

## Dataset and privacy

The notebook expects the Online Retail dataset to be provided by the user at runtime. Do not upload identifiable customer-level information to a public repository without checking whether it is appropriate to share.
