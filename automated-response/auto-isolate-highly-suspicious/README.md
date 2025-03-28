# Auto-Isolate Highly Suspicious

This playbook triggers when a Workbench Alert is received and performs the following actions:

- Creates a case for alerts with object enriched with suspicious level: `HighlySuspicious`, `Suspicious`, or `Unrated`
- Executes response actions: block object, collect file, submit to sandbox
- Sends a notification email with execution details and alert details

## Metadata

- **Created by:** BlufyFugu
- **Last updated:** 2025-03-28
- **Playbook type:** Automated Response
- **Severity covered:** All
- **Compatible with:** Trend Vision One

## Notes

- This is a sample automation for demonstration purposes.
- Ensure any user IDs or case owners used are updated for your environment.
