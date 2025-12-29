Data-Driven Analysis of Tiny Insect Pest Detection

Business Problem
Early detection of agricultural insect pests is critical to prevent crop damage and yield loss.
Tiny insect pests are particularly difficult to detect due to class imbalance, small object size,
and limited visual information.

This project focuses on **data analysis and performance evaluation** of a computer vision system
trained on the IP102 agricultural pest dataset.

 Dataset Overview
- Dataset: IP102
- Images: ~19,000
- Annotations: ~22,000
- Categories: 97 insect species
- Format: COCO

Key Data Insights
- ~1.45% of objects occupy less than 1% of image area
- Strong class imbalance across insect categories
- Detection performance varies significantly by object siz

Data Analysis Performed
- Class distribution analysis
- Object size distribution analysis
- Tiny-object prevalence metrics
- Dataset quality validation
- Evaluation metric breakdown by object scale

Model Evaluation (Analytical Focus)

| Metric | Value |
|------|------|
| mAP @ 0.5:0.95 | 0.1216 |
| mAP (Small Objects) | 0.0627 |
| mAP (Medium Objects) | 0.1511 |
| mAP (Large Objects) | 0.1261 |

 Key Findings
- Small object performance is significantly lower than medium and large objects
- Indicates data scarcity and scale imbalance
- Supports data-driven optimization strategies

Business Insights
- Poor detection of tiny pests can lead to delayed intervention
- Data imbalance directly impacts detection reliability
- Analytical evaluation helps prioritize data improvements

Skills Demonstrated
- Data analysis and visualization
- Dataset exploration and validation
- Metric interpretation (mAP, recall)
- Analytical reporting
- Business-focused insights

Project Files
- Full academic report: `docs/CVAI_final_assessment.pdf`
- Analysis notebooks: `analysis/`
- Results and visualizations: `results/`
