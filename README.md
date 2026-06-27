# UPI Fraud & Credit Risk Analytics

## Executive Summary
Analyzed 6.3M+ synthetic mobile-money transactions and 300K+ loan applications 
to build an end-to-end fraud detection and credit risk analytics framework. 
Identified that TRANSFER and CASH_OUT transaction types account for 100% of fraud 
in the dataset. Achieved PR-AUC of [fill after model] on fraud detection and 
Gini coefficient of [fill after model] on credit risk scoring.

## Business Problem

**1. What financial loss is happening?**
UPI fraud losses reached ₹805 crore across 10.64 lakh complaints by November 2025 (FY26). 
Only ~6% of stolen funds are ever recovered — making pre-settlement detection critical.

**2. Who is the stakeholder?**
Risk & Fraud Analytics team at a digital lending NBFC or payments company.

**3. What decision does this inform?**
- Which transactions to auto-block vs. flag for manual review vs. allow through
- Which loan applicants to approve, decline, or price at a risk premium

**4. What does success look like?**
- Reduce false negatives (missed fraud) without spiking false-positive review burden
- Identify top 5 default risk drivers with statistical confidence

## Data Sources
- **Fraud layer:** PaySim synthetic mobile-money dataset (Kaggle) — 
  synthetic data structurally modeled on UPI P2P/P2M flows. 
  Real UPI transaction data is not publicly available for security reasons; 
  this is industry-standard practice for fraud model prototyping.
- **Credit risk layer:** Home Credit Default Risk dataset (Kaggle) — 
  mimics thin-file borrower profiles common in Indian digital lending.
