---
title: Snyk's Bug Bounty Program
---

If you believe you have found a security vulnerability on Snyk, we encourage you to let us know right away. We will investigate all legitimate reports and do our best to quickly fix the problem. Before reporting though, please review this page including our responsible disclosure policy, reward guidelines, and those things that should not be reported.

### Responsible Disclosure Policy
* If you comply with the policies below when reporting a security issue to Snyk, we will not initiate a lawsuit or law enforcement investigation against you in response to your report. We ask that:
a) You give us reasonable time to investigate and mitigate an issue you report before making public any information about the report or sharing such information with others.
b) You do not interact with an individual account (which includes modifying or accessing data from the account) if the account owner has not consented to such actions.
c) You make a good faith effort to avoid privacy violations and disruptions to others, including (but not limited to) destruction of data and interruption or degradation of our services.
d) You do not exploit a security issue you discover for any reason. (This includes demonstrating additional risk, such as attempted compromise of sensitive company data or probing for additional issues).
You do not violate any other applicable laws or regulations.


### Bug Bounty Program Terms
* We recognize and reward security researchers who help us keep people safe by reporting vulnerabilities in our services. Monetary bounties for such reports are entirely at Snyk's discretion, based on risk, impact, and other factors. To potentially qualify for a bounty, you first need to meet the following requirements:
* Adhere to our Responsible Disclosure Policy (see above).
* Report a security bug: that is, identify a vulnerability in our services or infrastructure which creates a security or privacy risk. (Note that Snyk ultimately determines the risk of an issue, and that many software bugs are not security issues).
* We specifically exclude certain types of potential security issues; these are listed under “Ineligible Reports and False Positives” (see below).
* Submit your report to [security@snyk.io](mailto:security@snyk.io) (one issue per report) and respond to the report with any updates. Please do not contact employees directly or through other channels about a report.
* If you inadvertently cause a privacy violation or disruption (such as accessing account data, service configurations, or other confidential information) while investigating an issue, be sure to disclose this in your report.
* Use test accounts and the dedicated bug bounty server (beemo.snyk.io) when investigating issues. 

In turn, we will follow these guidelines when evaluating reports under our bug bounty program:
* We investigate and respond to all valid reports. Due to the volume of reports we receive, though, we prioritize evaluations based on risk and other factors, and it may take some time before you receive a reply.
* We determine bounty amounts based on a variety of factors, including (but not limited to) impact, ease of exploitation, and quality of the report. If we pay a bounty, the minimum reward is $20 USD. Note that extremely low-risk issues may not qualify for a bounty at all.
* We seek to pay similar amounts for similar issues, but bounty amounts and qualifying issues may change with time. Past rewards do not necessarily guarantee similar results in the future.
* In the event of duplicate reports, we award a bounty to the first person to submit an issue. (Snyk determines duplicates and may not share details on the other reports.) A given bounty is only paid to one individual.
* You may donate a bounty to a recognized charity (subject to approval by Snyk), and we double bounty amounts that are donated in this way.
* We reserve the right to publish reports (and accompanying updates).
* We verify that all bounty awards are permitted by applicable laws, including (but not limited to) US trade sanctions and economic restrictions.

Note that your use of Snyk services, including for purposes of this program, is subject to Snyk’s Terms and Policies. We may retain any communications about security issues you report for as long as we deem necessary for program purposes, and we may cancel or modify this program at any time.

### Bug Bounty Program Scope
To qualify for a bounty, report a security bug in one of the following qualifying products or components:
* Snyk's web site (dedicated host for the program is: https://beemo.snyk.io)
* Snyk's Command Line Interface (CLI) npm package https://github.com/Snyk/snyk
* Snyk's Broker component https://github.com/Snyk/broker

### Out of Scope
* Spam or social engineering techniques.
* Denial-of-service attacks.
* Security issues in third-party apps or websites that integrate with Snyk. These are not managed by Snyk and do not qualify under our guidelines for security testing.

