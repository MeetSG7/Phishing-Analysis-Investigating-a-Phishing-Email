# Phishing-Analysis-Investigating-a-Phishing-Email

🎯 Lab Objective

The objective of this lab is to analyze a real-world phishing email sample using manual investigation techniques. Students will learn to review email headers, validate the sender's identity, check domain/IP reputation, and extract indicators of compromise (IOCs).

# Task
We have a sample phishing E-mail. The task is to analyze it and confirm if it is suspecius or not.

# Lab Setup
📨 Download Email Sample (.eml)
💻 Tools Recommended:
MX Toolbox Email Header Analyzer
EML Analyzer
IP reputation check (e.g., VirusTotal, AbuseIPDB, Cisco Talos)
Whois lookup (e.g., whois.domaintools.com)
URL and Domain analysis (e.g., urlscan.io, VirusTotal)

# Step 1
 ## Determined the full email address of the sender
 <img width="624" height="400" alt="Q-A- 1" src="https://github.com/user-attachments/assets/bb8f3f9f-da2a-4737-a2f4-d960d0b66d36" />

# Step 2
## What domain is used to send this email? (Check Return-Path or From)
<img width="624" height="400" alt="domain" src="https://github.com/user-attachments/assets/a573b096-6b11-4fc7-9e2a-3f41442ad34c" />

# Step 3
## What is the sender’s IP address from the header?
<img width="624" height="400" alt="domain" src="https://github.com/user-attachments/assets/a573b096-6b11-4fc7-9e2a-3f41442ad34c" />

# Step 4
## Is the sender IP blacklisted? (Check using AbuseIPDB or VirusTotal – Answer Yes/No)
Ans: No
<img width="624" height="400" alt="ip black" src="https://github.com/user-attachments/assets/a0505898-ec14-4812-b166-49b723d1fe0a" />

# Step 5 
## What is the result of SPF authentication? (Pass / Fail / Neutral)
Ans:- Fail
<img width="624" height="400" alt="mail" src="https://github.com/user-attachments/assets/5590e51f-5325-4dc0-aa17-90ba1b42a84a" />

# Step 6 
## What is one suspicious URL or link found in the email body?
<img width="624" height="400" alt="URL" src="https://github.com/user-attachments/assets/e59758b8-65a5-400e-bd2d-6be5b2d0438f" />

# Step 7
## Screenshot of the email content or HTML preview that shows urgency, branding, or spoofing.
<img width="624" height="400" alt="Step 7" src="https://github.com/user-attachments/assets/f9019878-d5dd-485e-b37b-b597c393d9ce" />

# What I Learned From This Project  
## In my phishing analysis project, I learned how attackers craft phishing emails and malicious links to steal sensitive information. I analyzed email headers, URLs, and attachments to identify phishing indicators. This project helped me understand real-world phishing techniques and improved my ability to detect suspicious emails and protect users from phishing attacks.



 




