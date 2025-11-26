# Complete 5-Stage Text Analysis & Headline Generation Pipeline

**Overview**
This repository implements a 5-stage pipeline that preprocesses text, detects sensational/fake/bias signals, performs fact verification, rewrites headlines, and outputs annotated headlines with confidence scores and sources. The pipeline now includes a **DistilBERT** transformer classifier fine-tuned on your dataset (optional) for improved fake-news detection.

---

## Key features
- Stage 1: Preprocessing (cleaning, stopword removal)
- Stage 2: Fake/Bias detection (heuristic + optional DistilBERT classifier)
- Stage 3: Fact verification (regex entity extraction, knowledge-base check, source credibility)
- Stage 4: Headline rewriting (template-based NLG + ranking)
- Stage 5: Output generation (annotations, warnings, quality tiers)
- Works without `scikit-learn` / `scipy` (Windows-friendly)
- Supports fine-tuning DistilBERT on labelled datasets

---

## Requirements
Install dependencies in a *virtual environment* (recommended):

```bash
python -m venv venv
# Windows PowerShell:
venv\Scripts\Activate.ps1
# or Windows CMD:
venv\Scripts\activate.bat

python -m pip install --upgrade pip
python -m pip install -r requirements.txt
