# 🧠 How Senior QA Thinks in Wallet and Payment Systems

## 1. Think in money movement, not just features
Testing a wallet is not only about clicking buttons.
It is about validating how money moves across the system.

## 2. UI success does not guarantee transaction success
Always verify:
- API response
- backend processing
- wallet balance
- transaction history / ledger

## 3. Prioritize financial risk first
Test first:
- top-up / wallet funding
- transfers
- payment confirmation
- duplicate request handling

## 4. Assume failure paths are common
Strong QA checks:
- retries
- timeouts
- duplicate submissions
- partial processing
- stale balances

## 5. Focus on business impact
A wallet defect can lead to:
- financial loss
- customer complaints
- reconciliation issues
- trust and compliance problems
