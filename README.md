# LiquidPay QA Test Suite

## Overview
This repository contains a structured manual QA test suite for a fintech digital wallet application, designed using a real-world product acceptance and release-readiness approach.

The test pack is organized to reflect how QA teams handle digital wallet testing in fintech products, with coverage across registration, wallet management, QR payments, transfers, transaction history, disputes, security, compliance, and end-to-end workflows.

## Test Coverage
The suite includes 60+ manual test cases organized into the following modules:

- Registration_Login
- Wallet_Account
- QR_Payment
- Transfer_Remittance
- History_Disputes
- Security_Compliance
- End_to_End

## Test Design Approach

### BDD-style acceptance thinking
Each test case includes an **Acceptance Criteria (BDD)** column using:

- Given
- When
- Then

This helps ensure that requirements are translated into clear, testable, business-readable acceptance criteria.

### Risk-based coverage
The suite includes:
- Positive scenarios
- Negative scenarios
- Edge cases
- Fraud / duplicate scenarios
- Compliance-sensitive cases
- End-to-end payment validation

### Fintech QA focus
Special attention is given to:
- Payment integrity
- Duplicate transaction prevention
- Wallet balance validation
- Cross-border transfer behavior
- Security and session handling
- Auditability and execution evidence

## Workbook Contents
The Excel workbook includes:
- Module-based test case sheets
- Status tracking
- Pass / Fail / Blocked / Not Run execution support
- Summary sheet for execution progress
- BDD acceptance criteria for each case

## File Included
- `test-cases/LiquidPay_Full_TestSuite_BDD.xlsx`

## Sample Functional Areas Covered
- User registration and login
- Wallet/account validation
- QR code payment flows
- Failed and duplicate payment handling
- Transfer/remittance validation
- Transaction history and disputes
- Security/compliance checks
- End-to-end customer payment journeys

## Why this project
This project demonstrates:
- Senior-level QA thinking
- Product acceptance test design
- Business-to-test translation using BDD
- Structured manual testing for fintech/payment systems

## Author
**Ramon Tan Jr**  
Senior QA Engineer | FinTech | Payments | Manual + Automation QA

## Note
This repository is intended for portfolio and demonstration purposes.
