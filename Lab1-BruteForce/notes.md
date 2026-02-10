# Lab 1: Brute Force Detection

## Goal
Detect multiple failed login attempts indicating a brute force attack.

## Data Source
- Windows Security Event Logs
- Event ID: 4625 (Failed Login)

## Investigation Steps
1. Filtered Windows security logs for failed logins.
2. Grouped events by user account and source IP.
3. Identified accounts with a high number of failures.

## Findings
User ACCOUNT_NAME had multiple failed login attempts from IP ADDRESS.

## Next Steps
- Investigate the source IP
- Check for successful logins after failures
- Escalate if necessary
