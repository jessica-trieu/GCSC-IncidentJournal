# Google Cybersecurity Certification Project: Incident handler's journal
### Description
Throughout Google's course, there were multiple activities that introduced new concepts and tools. The incident handler's journal was a template provided to help track and analyze different security incidents .

## Entries
**Entry:** 1

**Date:** 12/24/24

**Description:** A small U.S. health care clinic experienced a security incident on Tuesday at 9:00 a.m. which severely disrupted their business operations. Several employees reported that they were unable to use their computers to access files like medical records. Business operations shut down because employees were unable to access the files and software needed to do their job.
Additionally, employees also reported that a ransom note was displayed on their computers. The ransom note stated that all the company's files were encrypted by an organized group of unethical hackers who are known to target organizations in healthcare and transportation industries. In exchange for restoring access to the encrypted files, the ransom note demanded a large sum of money in exchange for the decryption key. 

**Tools Used:** None

**The 5 W's**
- Who: Organized group of unethical hackers
- What : Ransomware security incident
- When: Tuesday at 9am
- Where: US health clinic
- Why: Attackers were able to gain access to the system via phishing attacks. The attackers then used ransomware to encrypt medical records. They then demanded a large sum of money in exchange for the decryption key.

**Additional Thoughts:** 
What are the vulnerabilities in the clinic’s network?
What are the pros and cons of paying the hackers?

<br /> 
<br />

**Entry:** 2

**Date:** 12/25/24

**Description:** I received an alert about a suspicious file downloaded to an employee computer.

**Tools Used:** I used VirusTotal, which is a tool that can scan files and URLs for malicious content like malware, trojans, worms, etc by utilizing multiple antivirus scanners and URL/domain blocklisting sites. After analyzing the file or URL, VirusTotal aggregates the results and compiles it into a comprehensive report. 

**The 5 W's**
- Who: Malicious actor used phishing attack, possibly BlackTech
- What: A suspicious file was sent via email to an employee computer. 
- When: Today between 1:11pm to 1:20pm
- Where: An employee computer at a financial services company
- Why: To have the employee download and install the malware received via email. 

**Additional Thoughts:** 
Were any files modified/deleted? 
What signs of phishing emails can we teach employees so they can have an easier time avoiding these tactics?

<br /> 
<br />

**Entry:** 3

**Date:** 12/26/24

**Description:** A mid-sized retailer experienced a major security breach of approx. 50,000 customer’s PII and financial information.

**Tools Used:** None

**The 5 W's**
- Who: One hacker
- What: An employee received several emails from the malicious actor claiming that they had stolen the company’s data and demanded payment in exchange for keeping the information private. After investigation by the security team, the root cause of the incident was identified as a vulnerability in the e-commerce web application. This vulnerability allowed the attacker to perform a forced browsing attack and access customer transaction data by modifying the order number included in the URL string of a purchase confirmation page. This vulnerability allowed the attacker to access customer purchase confirmation pages, exposing customer data, which the attacker then collected and exfiltrated.
- When: December 22, 2022 - Dec 31, 2022
- Where: Retail employee’s email.
- Why: The malicious actor was motivated by financial reasons and demanded $50,000 in cryptocurrency. 
- What are the vulnerabilities in the clinic’s network?
- What are the pros and cons of paying the hackers?

-**Additional Thoughts:** 
Should the hacker be paid? 
How do we train employees to know when to escalate incidents to the security team?

<br /> 
<br />

**Entry:** 4

**Date:** 12/27/24

**Description:** In this activity, I received a phishing alert about a suspicious file being downloaded on an employee's computer. After investigating the email attachment file's hash, there has already been a report that the attachment has been verified to be malicious. Now I must complete the investigation and resolve the alert ticket.

**Tools Used:** I used the organization’s phishing playbook. A playbook is a step-by-step guideline on how to approach and resolve security incidents. The phishing playbook provided was specifically made for level 1 SOC analysts to use to resolve phishing attempts. 

**The 5 W's**
-  Who: An unknown malicious actor who signed off their email as “Clyde West” but the sender’s email “76tguyhh6tgftrt7tg.su” name was “Def Communications”.
- What: An alert ticket was created due to a possible security incident 
where an employee had opened a suspicious email disguised as a job application and may have opened attachments or clicked links. After evaluating the email’s attachments, noting the email’s grammatical mistakes, and inconsistencies with the sender’s name, I confirmed that the email was indeed malicious and escalated the ticket to a level 2 SOC analyst.
- When: Email was sent Wednesday, July 20, 2022 09:30:14 AM
- Where: A computer belonging to an employee of a financial services company
- Why: The malicious actor wanted the employee to download the malicious file attached to the email they sent.


**Additional Thoughts:** 
What was the malicious actor trying to gain with the installation of malware?
How often is HR receiving cold emails for potential new hires? Is there a better way to receive resumes?
