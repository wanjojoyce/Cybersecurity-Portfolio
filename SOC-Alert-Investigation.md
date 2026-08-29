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

  ## Investigation 2: Inbound Email Containing Suspicious External Link

## Alert Details

-Severity: Medium
-Classification: Phishing
-Date: August 23, 2026
-Alert Time: 12:45
-Data Source: Email
-Direction: Inbound

## Email Information

Subject: Action Required; Finalize your Onboarding Profile
Sender: onboarding@hrconnex.thm
Recipient: j.garcia@thetrydaily.thm

The email appeared to be an onboarding-related message asking the recipient to complete their profile setup through an external link.

## Investigation Objectives
The objective was to determine whether the external link represented a potential phishing threat, to establish whether any 
endpoints had attempted to access the URL and to also determine whether it is a true positive.

## Investigation Steps

- Reviewed the alert details and email metadata.
- Examined the sender, recipient, subject, and email content.
- Reviewed the external link included in the email.
- Checked firewall or proxy logs for connections to the URL
- Determined whether any endpoints attempted to access the URL
- Checked whether the connections were allowed or blocked
- Used the available evidence to assess the risk associated with the alert

 ## Key Indicators

The alert was classified as phishing because the sender's domain was suspicious and did not match the recipient's company domain, also because the subject line seems suspicious " Action Required, Finalize your Onboarding Profile".

## Recommendations

-  I validated the Inbound Email as a true Positive
-  Blocked the suspicious URL/domain
-  Identified whether Garcia clicked on the link
-  Isolated any affected endpoint
-  Reset credentials if they may have been exposed
-  Recommended that the problem should be escalated

  ## Skills Demonstrated
  - Security alert investigation
  - Phishing alert analysis
  - Email security analysis
  - Log analysis
  - Incident response

    ## Tools and Concepts
    - SIEM concepts
    - Email security
    - Firewalls and Proxy logs
    - Phishing Investigation
   
    ## Key Takeaway

    These investigations strengthened my understanding of how a SOC Analyst approaches security alerts from initial detection through investigation and response. I learned to examine alert details, analyze suspicious processes and email indicators, review relevant logs assess the likelihood of a true positive, and recommend appropriate containment and defensive actions based on the available evidence. 




