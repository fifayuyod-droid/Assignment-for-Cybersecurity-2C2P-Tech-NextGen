# Assignment-for-Cybersecurity-2C2P-Tech-NextGen
Incident Response – Use Case Based Questions Purpose: These questions are designed to assess cybersecurity intern candidates’ understanding of incident response concepts, logical thinking, and security awareness, without requiring hands-on technical experience.
---
Assignment for Cybersecurity 2C2P Tech NextGen


////////////////////////////////////////////////////////////////////////////////////////////

# 1.	Malware Detection Scenario
Use Case:
An endpoint security tool reports a possible malware infection on a user laptop.
Questions:

• What would be the first thing you check after receiving this alert?
  > Review alert details from the endpoint security tool, including the detection type, affected file or process, severity level, and timestamp. I would determine if the alert is credible or is it a fault alert and how urgent the situation is.
> 
• What information should be collected before escalating the issue?
  > collect the device name, user information, malware types, current status of the threat, and any recent activity related to the alert.
> 
• Would you isolate the device immediately? Why or why not?
  > isolate the device if there are signs of active infection or risk of lateral movement. If the alert appears low risk or already contained, I would validate first to avoid unnecessary disruption.
> 
• Who should be informed about this incident?
  > The security operations team should be informed first. Depending on severity, IT support or management might also need to be notified.


# 2.	Phishing Email Scenario
Use Case:
A user reports that they clicked a suspicious email link.
Questions:

• What questions would you ask the user first?
> I would ask when the link was clicked, what actions were taken after clicking, and whether any credentials or personal information were entered.
> 
  
• What risks are associated with clicking a phishing link?
> Lead to credential compromise, malware infection, and potential data being stolen.
  >
  
• What immediate actions should be taken?
> The user’s device should be assessed, credentials reset if necessary, and the malicious link reported for blocking.
> 
• How would you prevent other users from being affected?
> The email and link should be blocked across the organization, and inform other users. 
  


# 3.	Multiple Failed Login Attempts
Use Case:
The SIEM shows multiple failed login attempts for a single account.
Questions:
> 
• What could this activity indicate?
> Unorthorize login attemps or user might forget password.
> 
• What additional information or logs would you check?
> I would review logs first, source IP addresses, and if similar attempts are occurring on other accounts.
> 
• At what point does this become a security incident?
> It becomes a security incident when attempts are persistent, automated, or originate from suspicious locations, or lastly if I have communicated with user and their activity is not conserning, might be credential lost.
> 
• What response actions would you recommend?
> Temporary account lockout, user notification, and continued monitoring actions.


# 4.	Abnormal Login Location
Use Case:
A user logs in from two different countries within a short period.
Questions:
> 
• What does this behavior suggest?
> Might be account compromise or unauthorized access.
> 
• What could be legitimate reasons for this activity?
> The user may be traveling, using a corporate VPN, or accessing from a different authorized location.
> 
• How would you validate whether this is malicious?
> Verify login details and confirm activity directly with the user.
> 
• What actions should be taken if it is confirmed as suspicious?
> Access should be blocked, credentials reset, and the incident investigation.


# 5.	DLP Alert Triggered
Use Case:
A Data Loss Prevention (DLP) alert indicates sensitive data is being sent externally.
Questions:
> 
• What types of data are considered sensitive?
>Personally identifiable information, financial data, credentials, confidential documents.
>
• How would you determine whether this is a real incident or a false positive?
> I would review the data type, destination, user role.
> 
• Who should be involved in investigating this alert?
> Security, IT, and compliance teams should be involved.
> 
• What is the potential business impact?
> Possible data leak, reputational damage, and financial loss.


# 6.	Incident During Non-Business Hours
Use Case:
A high-severity security alert is triggered at 2 AM.
Questions:
> 
• How should incidents be handled outside business hours?
> Critical incidents should be handled through an on-call or escalation process. And should be handled imediately.
> 
• What actions can be automated versus manual?
> Automated responses may include alerting and access restrictions, But investigation and decision-making in the next orocess on how to fix the sutuation should remain manual.
> 
• When should escalation occur?
> The moment when high-severity alert is triggered, that should already be taken seriously even if it might be false alarm, that should be investigate anyway.


# 7.	Suspected Ransomware Activity
Use Case:
A user reports that files have suddenly become inaccessible or encrypted.
Questions:
> 
• What signs indicate a possible ransomware attack?
> Encrypted files, unusual file extensions, ransom messages i.e requires payment to see the files, or abnormal system behavior.
> 
• What should be the first response action?
> The affected system should be disconnected from the network immediately.
> 
• What actions should be avoided?
> Do not power off systems, delete files, or pay the ransom.
> 
• Who must be notified immediately?
> The security team, and management must be informed immediately.


# 8.	Incident Prioritization
Use Case:
Multiple security alerts are received at the same time.
Questions:
> 
• How would you decide which alert to address first?
> Alerts should be prioritized based on potential impact, severity, and scope.
> 
• What factors influence incident severity?
> Data sensitivity, number of affected users, system criticality, and threat activity.
> 
• Which types of incidents require immediate response?
> Ransomware, trojans, and any suspecious/malecious threats.


# 9.	Communication During an Incident
Use Case:
 A confirmed security incident is actively being investigated.
Questions:
> 
• Why is communication important during incident response?
> Clear communication allow IT support to coordinated response and minimizes operational risk with users.
> 
• Who should receive incident updates?
> Security teams, management, IT stakeholders, and affected users when appropriate.
> 
• What information should not be shared during an incident?
> Unverified details, sensitive data, and information that could help attackers should not be shared.


# 10.	Post-Incident Review
Use Case:
A security incident has been successfully resolved.
Questions:
> 
• What is a post-incident review?
> An evaluation of the incident, response actions, and outcomes.
> 
• Why is it important?
> It helps identify the root cause and strengthen future incident response.
> 
• What lessons can be learned from it?
> Technical improvements, process enhancements, response efficiency, and for me, improve trouble shooting and thing process.


///////////////////////////////////////////////////////////////////////////


Thank you for giving me this oppotunity.

Kind regards,
