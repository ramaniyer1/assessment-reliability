# Assessment Runner

This repository contains the full pipeline to automate psychometric reliability and validity analysis for assessments.

## Files

- `reliability_combined.py`: Main script for running reliability & validity analysis.
- `requirements.txt`: Python dependencies.
- `README.md`: Setup guide.

## How to Use

1. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

2. Run the script with your input files:
   ```
   python reliability_combined.py
   ```

Make sure your working directory includes:
- `Assessment_Template.xlsx`
- `Can_Data.xlsx`

These will be used to generate:
- `Candidate_Response_Generated.xlsx`
- `section_summary.csv`
- `item_stats.csv`
- `pca_summary.csv`