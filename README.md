# Veto Collapse in Multi-Agent LLM Credit Decisions
   
Research project investigating decision consistency, fairness-related counterfactuals, and approval outcomes in LLM-based credit decision settings.

## Research Overview

This project evaluates multiple experimental conditions using the German Credit dataset and Gemini-based decision workflows. It includes baseline comparisons, alternative decision conditions, and counterfactual tests involving protected attributes.

The experiments and analysis are documented in `debiasing_main.ipynb`.

## Repository Contents

- `debiasing_main.ipynb` — main research notebook and analysis.
- `german_credit_clean.csv` — cleaned German Credit dataset.
- `adult_income_clean.csv` — cleaned Adult Income dataset used in the project.
- `*_full_german.csv` — experiment output files.
- `*_partial.csv` — partial experiment outputs.
- `*_results_50*.csv` — saved experimental results.
- `phase5_flip_test_2026-09-28.csv` — counterfactual flip-test results.
- `.env.example` — template for environment variables.
- `requirements.txt` — Python dependencies.

## Requirements

- Python 3.10 or later recommended.
- A Gemini API key for running experiments that call the Gemini API.

## Setup

1. Clone this repository.
2. Create and activate a virtual environment.
3. Install dependencies:

   ```bash
   python -m pip install -r requirements.txt
