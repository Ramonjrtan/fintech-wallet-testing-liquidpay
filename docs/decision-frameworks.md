# 🎯 Wallet QA Decision Frameworks

## Risk-Based Testing Priority

### Highest Priority
1. Wallet funding / top-up
2. Transfer / send money
3. Merchant payment
4. Balance and transaction history consistency

### Medium Priority
5. Notifications
6. profile / preferences
7. non-financial UI flows

---

## When to Write Detailed Test Cases
Use detailed cases for:
- money movement
- balance updates
- API validations
- edge cases with retries / duplicate requests

Use higher-level cases for:
- layout-only checks
- static informational screens

---

## Release Decision Rules

A release should be considered **NOT READY** if:
- duplicate transactions are possible
- wallet balance becomes inconsistent
- successful transactions are missing from history
- failed payments are marked as completed
- API and backend states do not match

---

## What to Validate for Every Payment Flow
- request payload correctness
- response status and fields
- final wallet balance
- transaction ledger entry
- user-visible history / receipt
