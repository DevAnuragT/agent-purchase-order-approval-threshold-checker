# Purchase Order Approval Threshold Checker

Compare purchase order amounts with declared approval thresholds and recorded signoffs.

## Run

    python3 agent.py examples/good-input.json
    python3 tools/review-purchase-order-approval-threshold-checker.py examples/good-input.json

Input requirements and thresholds are listed in metadata.json. Output contains status, score, checked rules, and evidence-backed findings.

## Limits

Offline, deterministic review aid. Cannot establish facts beyond supplied evidence; a human must review before acting.
