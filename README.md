# Ops Tools Index

A curated index of small practical tools for Linux, server operations, troubleshooting, and automation.

This repository serves as both a portfolio index and a personal catalog for quick access to tools I built for practical operational work.

---

## Categories

- Troubleshooting / Triage
- Mail / DNS
- Logs / Monitoring
- Network / Firewall
- Config / Validation
- Data / Utilities
- Web / Notes

---

## Troubleshooting / Triage

### [initial_triage_tool](https://github.com/tikuro69/initial_triage_tool)
Collect basic system information for initial investigation.

- Type: Python / CLI
- Use case: First response when a Linux server becomes slow or unstable

### [system_snapshot_tool](https://github.com/tikuro69/system_snapshot_tool)
Capture a quick system snapshot from a Linux server for investigation and record keeping.

- Type: Python / CLI
- Use case: Quickly gather system state before deeper troubleshooting

### [migration_prep_tool](https://github.com/tikuro69/migration_prep_tool)
Prepare information needed for migration, rebuild, or handover work.

- Type: Python / CLI
- Use case: Organize investigation data before server migration or environment reconstruction

---

## Mail / DNS

### [mail_header_probe](https://github.com/tikuro69/mail_header_probe)
Inspect email headers and authentication results such as SPF, DKIM, and DMARC.

- Type: Python / CLI
- Use case: Quick investigation of suspicious emails or spoofing attempts

### [domain-probe-tool](https://github.com/tikuro69/domain-probe-tool)
Check DNS records and basic domain configuration.

- Type: Python / CLI
- Use case: Verify DNS settings during setup or troubleshooting

---

## Logs / Monitoring

### [log_parser_tool](https://github.com/tikuro69/log_parser_tool)
Parse logs and summarize frequent entries.

- Type: Python / CLI
- Use case: Quick review of server logs during incident investigation

### [cert_expiry_check](https://github.com/tikuro69/cert_expiry_check)
Check SSL/TLS certificate expiration dates.

- Type: Python / CLI
- Use case: Prevent certificate expiry issues before service impact

---

## Network / Firewall

### [iptables-rule-viewer](https://github.com/tikuro69/iptables-rule-viewer)
Visualize `iptables -L -n -v` output in a browser-friendly format.

- Type: HTML / JavaScript
- Use case: Review firewall rules more easily during server operations

---

## Config / Validation

### [nginx_apache_config_linter](https://github.com/tikuro69/nginx_apache_config_linter)
Lint and review Nginx and Apache configuration files.

- Type: Python / CLI
- Use case: Catch simple configuration issues before deployment or migration

---

## Data / Utilities

### [csv_tool](https://github.com/tikuro69/csv_tool)
Extract, filter, and reshape CSV data.

- Type: Python / CLI
- Use case: Small operational data processing and quick CSV cleanup

---

## Web / Notes

### [thought-bag](https://github.com/tikuro69/thought-bag)
A lightweight web app for collecting and organizing small ideas and notes.

- Type: Web app
- Use case: Keep rough thoughts and small ideas in one place

---

## Profile

### [tikuro69](https://github.com/tikuro69/tikuro69)
My GitHub profile repository.

- Type: Profile README
- Use case: Overview of my background, skills, and featured projects

---

## Notes

- These tools are intentionally small and focused.
- Most of them were built from practical operational needs.
- This index is maintained as both a portfolio and a working reference for my own use.
- New tools will be added over time.

---

## Focus Areas

- Linux server operations
- Troubleshooting and incident response
- DNS / mail investigation
- Log analysis
- Small automation utilities
- Practical CLI tools

---

## Recommended Workflow

This toolkit is intended for small-scale Linux server operation, initial troubleshooting, and configuration review.

1. **initial_triage_tool**  
   Collect basic system information and prepare an initial investigation report.

2. **log_parser_tool**  
   Summarize Apache/Nginx access logs and identify request trends.

3. **nginx_apache_config_linter**  
   Review web server configuration files and detect common issues.

4. **mail_header_probe**  
   Inspect mail headers and check SPF/DKIM/DMARC-related information.

5. **iptables-rule-viewer**  
   Visualize iptables rules and make firewall behavior easier to understand.

## Concept

These tools are designed to help operators collect facts quickly, reduce manual checking, and prepare information that can be reviewed by humans or AI assistants.