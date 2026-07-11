
Testing of payment transactions using Razorpay sandbox
# Payment Gateway Sandbox Testing – Card & UPI Transactions

 -> Objective 
Manual QA testing of payment transaction flows using Razorpay's test/sandbox 
environment, covering card and UPI payment methods, as a self-driven project 
to build hands-on card payment domain testing experience.

-> Scope
- Card payment lifecycle: authorization, capture, decline scenarios
- Negative/failure scenarios: payment timeout, invalid card, insufficient funds
- OTP / 3D Secure authentication flows (success and failure)
- UPI payment success and failure flows
- Reconciliation checks: verifying transaction status consistency between 
  checkout UI and merchant dashboard
- Refund and partial refund verification

-> Tools Used
- Razorpay Test Mode (sandbox environment)
- Excel (test case design and documentation)
- Manual defect logging with reproduction steps (JIRA-style format)

-> Deliverables
- 20 documented test cases with pre-conditions, steps, test data, 
  expected/actual results (see Payment_Gateway_Test_Cases.xlsx)
- 3 sample defect reports with severity/priority classification
- Screenshots of executed test transactions (see /screenshots folder)

-> Key Learnings
Applied payment transaction lifecycle concepts (authorization, capture, 
settlement) and reconciliation thinking to validate both success and 
failure paths across card and UPI payment methods in a sandbox environment.
