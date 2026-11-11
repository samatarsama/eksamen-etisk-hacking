# Web Application Penetration Test

This ethical hacking exam project documents a white-box penetration test of a PHP web application and its Linux host. I reviewed the application's source code, mapped exposed services, and manually validated findings from automated scans.

**The full report is written in Norwegian.** [Read the report (PDF)](EKSAMEN%20ETISKHACKING.pdf).

## Assessment highlights

- Investigated SQL injection, local file inclusion, cross-site scripting, and broken access control.
- Demonstrated how local file inclusion, credential reuse, and a vulnerable Linux component could be chained to gain root access in the exam environment.
- Documented findings with proof-of-concept evidence, severity ratings, and remediation recommendations. The report includes an executive summary and prioritizes fixes for the highest-risk findings.

The assessment followed the Penetration Testing Execution Standard (PTES). Tools included Nmap, Burp Suite, OWASP ZAP, Nikto, and sqlmap.
