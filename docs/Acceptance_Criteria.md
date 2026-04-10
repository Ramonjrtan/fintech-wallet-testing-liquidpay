# ✅ Acceptance Criteria

## Scope
This portfolio simulates QA validation for a digital wallet platform covering:
- wallet funding / top-up
- send money / transfer
- merchant payment
- wallet balance updates
- transaction history and reporting

---

## Core Acceptance Criteria

### 1. Wallet Funding
- User can fund wallet successfully using a valid payment method
- Correct amount is reflected in wallet balance
- Transaction is recorded in history and backend records
- Duplicate submission does not create duplicate funding

### 2. Send Money / Transfer
- User can transfer funds when sufficient balance exists
- Sender balance is reduced correctly
- Receiver / target transaction record is created correctly
- Failed transfer does not incorrectly debit balance

### 3. Merchant Payment
- Payment is processed successfully for valid transactions
- Failed payment does not appear as completed
- API response matches final payment state
- Wallet balance and transaction history remain consistent

### 4. Transaction History
- Successful transactions appear in history with correct status and amount
- Failed or reversed transactions show correct state
- History matches backend / ledger records

### 5. Data Integrity
- UI balance matches backend balance
- API and ledger entries match final transaction outcome
- Retry / timeout handling does not create inconsistent states

---

## Release Acceptance
A build is acceptable for release only if:
- no duplicate financial transactions are possible
- balance updates are accurate
- successful and failed transactions are clearly reflected
- transaction history, API, and backend records are consistent
