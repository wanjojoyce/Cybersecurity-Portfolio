# SOC Alert Investigation

## Project Overview

This project demonstrates my approach to investigating a suspicious security alert as a beginner SOC Analyst.

## Scenario

A security alert was generated after a suspicious process with an uncommon parent-child relationship was detected in the environment.

## Investigation Steps

1. Reviewed the alert details and timestamp.
2. Examined the suspicious process and its parent process.
3. Checked the process relationship for unusual behavior.
4. Reviewed available event and log information.
5. Assessed whether the activity could indicate malicious behavior.
6. Documented the findings and recommended appropriate defensive actions.

## Findings

The alert required further investigation because the parent-child process relationship was unusual and could potentially indicate malicious activity.

## Recommended Actions

- Investigate the originating process.
- Review related logs and events.
- Check for additional suspicious activity from the same host or account.
- Isolate the affected endpoint if malicious activity is confirmed.
- Document and escalate the incident according to the organization's incident-response procedure.

## Skills Demonstrated

- Security alert investigation
- Log analysis
- Process analysis
- Threat detection
- Incident response
- Security documentation

## Tools and Concepts

- SIEM
- Windows security events
- Process analysis
- NIST Cybersecurity Framework

8818

Inbound Email Containing Suspicious External Link
Medium
Phishing
Aug 23rd 2026 at 12:45
Awaiting action

Description:

This alert was triggered by an inbound email contains one or more external links due to potentially suspicious characteristics. As part of the investigation, check firewall or proxy logs to determine whether any endpoints have attempted to access the URLs in the email and whether those connections were allowed or blocked.

datasource:

email

timestamp:

08/23/2026 12:43:29.508

subject:

Action Required: Finalize Your Onboarding Profile

sender:

onboarding@hrconnex.thm

recipient:

j.garcia@thetrydaily.thm

attachment:

None

content:

Hi Ms. Garcia,\n\nWelcome to TheTryDaily!\n\nAs part of your onboarding, please complete your final profile setup so we can configure your access.\n\nKindly click the link below:\n\n<a href="https://hrconnex.thm/onboarding/15400654060/j.garcia">Set Up My Profile</a>.\n\nIf you have questions, please reach out to the HR Onboarding Team.

direction:

inbound
