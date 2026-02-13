# Metasploitable2 Security Assessment

## Overview
This project documents a network security assessment conducted against a deliberately vulnerable Linux system (Metasploitable2) in a controlled lab environment. 
The goal was to demonstrate structured reconnaissance, vulnerability identification, and responsible validation of security risks.

## Tools Used
- Nmap (host discovery, port scanning, service enumeration, NSE scripts)
- Metasploit Framework (controlled vulnerability validation)
- Kali Linux

## Key Findings
- Multiple exposed network services increasing attack surface
- Critical FTP vulnerability (vsFTPd 2.3.4) allowing unauthenticated remote code execution
- Web service susceptible to Slowloris-style denial-of-service attacks

## Validation
One critical vulnerability was safely validated using Metasploit. No destructive testing or privilege escalation was performed.

## Report
📄 **Full Security Assessment Report:**  
`report/security_assessment.pdf`

## Disclaimer
This project was conducted in an isolated lab environment for educational purposes only.
