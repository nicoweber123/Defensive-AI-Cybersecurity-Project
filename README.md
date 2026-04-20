# Governance and Security Planning for Internal AI Tools in a Small-to-Medium-Sized Financial Services Organization
Selected Domain: Governance and Secure Deployment

## Members
- Shree Khambekar
- Izaak Workman
- Nico Weber
- Jeff Camp
- Jacob Jonas

## Project Description
Our group will study a small-to-medium-sized financial services organization deploying internal LLMs, retrieval systems, copilots, or AI agents to support business operations. 

These AI tools may be used for tasks such as drafting client communications, summarizing policies and reports, assisting employees with internal knowledge retrieval, supporting fraud review workflows, and improving general productivity. Because smaller and mid-sized businesses often have limited security staff and fewer technical resources than large enterprises, they may be more likely to utilize the assistance of AI (even in a questionable fashion), and they may be especially vulnerable if AI systems are deployed without strong governance and security controls. Furthermore, since the organization handles sensitive financial and personal data, the secure deployment and governance of these AI systems is a significant cybersecurity and privacy concern.

## Tools Used
- Google Docs
- Github

## Weekly Progress Summary
|Week|Progress Summary|
|-|-|
|1|Created initial plan and documentation for the project. Created github repo. Created project charter.|
|2|Updated GitHub repository and weekly progress in README. Created threat model document including: key threats, attack surfaces, misuse scenarios, likely impact. Expanded asset inventory. Created baseline evidence pdf, including: prompts and outputs, log samples, architecture screenshot, policy review notes, workflow screenshots, permission analysis, retrieval examples, initial test cases. Created initial risk matrix. Created planned control list showing which defensive controls your group will propose or test.|
|3|During Week 3, the team focused on Checkpoint 3 by moving from baseline analysis into defensive control design and evaluation planning. We selected a focused set of controls based on the highest-risk issues identified in the threat model, baseline evidence, and initial risk matrix. These controls included role-based access control, retrieval access scoping, DLP filtering for AI prompts and outputs, prompt injection detection, audit logging, log integrity protections, human review for high-risk AI outputs, and controls to reduce shadow AI usage.
The team completed the Control Implementation and Evaluation Summary, which explains why these controls were selected and how they connect to the project’s main risks. The selected controls directly address issues such as sensitive data leakage, indirect prompt injection, overprivileged AI access, incomplete logging, unsafe AI-assisted workflows, and shadow AI usage.
The team also created Evidence of Defensive Work to show the actual artifacts designed for the project. This evidence includes DLP filtering logic, prompt injection detection rules, a validation workflow, RBAC and retrieval access-control design, policy enforcement mapping, logging design, secure prompt templates, guardrail design, retrieval hardening rules, a least-privilege matrix, and review checklists.
By the end of Week 3, the project had a stronger connection between the baseline risks and the proposed defensive improvements. The team also prepared materials that will support the final report, including the evidence appendix and final report outline. Remaining work includes completing validation evidence, updating the risk register based on control results, and preparing the final presentation and final report.|


## Final Outcome Summary
N/A
