# Incident Response Simulation

## Scenario
Multiple failed login attempts detected from a single IP address.

## Investigation Steps
1. Reviewed authentication logs to confirm failed login attempts.
2. Identified source IP address responsible for the activity.
3. Checked frequency of attempts to determine possible brute-force attack.

## Findings
Multiple failed login attempts originating from a single IP address indicate suspicious activity.

## Response
- Monitor the IP address.
- Temporarily block the IP using firewall rules.
- Alert system administrators.

## Outcome
Potential brute-force attack identified and mitigated.
