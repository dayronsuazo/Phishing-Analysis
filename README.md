# Phishing Analysis and Mitigation

## Objective
The objective of this phishing analysis project is to identify, investigate and mitigate phishing threats by analysing suspicious emails, extracting indicators of compromise (IoCs), and providing actionable insights. I will also be using Microsoft Defender to configure threat policies that will mitigate threats such as phishing, spam, malware, attachments and links. This will improve the organisation email security defences, reduce phishing-related incidents and enhance user awareness through targeted training and preventive measures.

### Skills Learned

- Identifying and categorising types of phishing emails
1) Recon emails - to get a response or check if mailbox is being used
2) Spam emails which are mostly unsolicited/unwanted
3) Credential Harvesters - These are emails that attempt to retrieve valid credentials which can potentially be used to gain access to the system. 
These emails typically feature a lure email that is styled to look like it is from a legitimate company, impersonating some of the most popular online services and retailers like Outlook, Amazon and DHL. The email will tell the recipient to click a button or URL, where they will typically be presented with a real-looking login portal - however, any credentials entered are either stored on the site in an inaccessible directory, or emailed to a dummy account, typically utilising free online mail services such as Gmail, Hotmail and Outlook, where the attacker can log in and collect them.
4) Whaling - This is a targeted phishing attack that looks to target individuals within management positions in an organisation
5) Social Engineering - Is the practice of exploiting a human as opposed to a system.
6) Vishing and Smishing - Targets users by phone call or text messages
7) Malicious file - Delivering malware via phishing, as an attachment, or as a hyperlink taking the target to a web server that is hosting malware available for download.

- Investigating Phishing Emails (Artifacts collection)
1)Email
Sending email address
Subject line
Recipient Email Addresses
Sending server IP & Reverse DNS
Reply-to Address
Date & Time
2)File Artifacts
Attachment Name
SHA256 Hash Value
3)Web Artifacts
Full URLs
Root Domain

- Taking Defensive Actions
Using Microsoft Defender I was able to configure preventative and reactive security measures to keep our organisations safe from phishing attacks.
1) Marking External Emails.
2) Spam filters covering content, rule-based, and bayesian filters
3) Attachment filtering - Carefully deciding with management to block most obvious file types like .exe|.js|.ps and others to not disrupt business continuity.
4) Security Awareness Training.
5) Blocking email, web and file based artifacts.
6) Investigation Report - This provides an audit trail to show that the email was identified, investigated and defensive measures were taken to protect the organisation from this attack.

### Tools Used
- URL2PNG - You simply enter in a URL, hit go, and it’ll provide you with a screenshot of what the webpage looks like.
- URLScan also provides a screenshot, allowing us to see what the destination web page looks like
- VirusTotal - helps detect malware and malicious content in files and URLs.
- Talos File reputation
- Hybrid Analysis (Malware Sandboxing) - an online malware analysis platform that lets you upload malware for instant cloud-based analysis, providing you with a detailed report about the observed activity.

