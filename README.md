# Mortgage Calculator

This repository contains a **Mortgage Calculator** implemented as a Jupyter Notebook (Google Colab compatible).  
It is designed to calculate mortgage installments, generate a full amortization schedule, and visualize the repayment process in a clear and structured way.  
The code is fully commented and can be adapted to different loan scenarios.

---

## Features (Detailed)

- **Monthly Installment Calculation**
  - Uses the annuity formula to compute constant monthly payments.
  - Based on:
    - Loan amount (*principal*)
    - Annual interest rate
    - Loan duration (*years*).

- **Amortization Schedule**
  - Builds a full table with:
    - Total installment (constant each month)
    - Portion of installment used for interest repayment
    - Portion of installment used for principal repayment
    - Remaining principal balance
    - Remaining total interest over the loan.

- **Financial Summary**
  - Calculates:
    - Constant monthly installment
    - Total interest paid over the loan
    - Total repayment (principal + interest).

- **Visualization**
  - Generates a line chart (via `matplotlib`) to show:
    - Decline of the outstanding principal
    - Cumulative interest evolution.
  - Helps users *see* the dynamics of their mortgage over time.

- **Flexibility**
  - Code can be adapted to test different loan sizes, durations, or interest rates.
  - Easy to extend with more financial features.

---

## Run on Google Colab
You can open the notebook directly in Colab without installing anything locally:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/<your-username>/<your-repo>/blob/main/Mortgage_calculator.ipynb)

---

## Run Locally (Optional)

If you prefer running the notebook on your machine:

1. **Clone this repository**
   ```bash
   git clone https://github.com/<your-username>/<your-repo>.git
