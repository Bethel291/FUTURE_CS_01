FUTURE_CS_01 - Web Application Security Testing (OWASP ZAP)

This project is part of my cybersecurity internship program. The objective was to perform an automated security scan on a test web application using OWASP ZAP.

---

Objective:

Conduct a security scan using ZAP by Checkmarx on the URL: http://www.itsecgames.com/. The goal was to identify common web vulnerabilities and insecure configurations.

---

Tools Used:

- ZAP by Checkmarx (OWASP ZAP v2.16.1)
- Firefox browser
- Windows 10

---

Vulnerabilities Identified:

| Vulnerability                                | Risk Level | Confidence |
|---------------------------------------------|------------|------------|
| Content-Security-Policy Header Not Set      | Medium     | High       |
| Anti-clickjacking Header Missing            | Medium     | Medium     |
| X-Content-Type-Options Header Missing       | Low        | Medium     |

---

Screenshots:

(Insert screenshots here if viewing on GitHub)

- Screenshot_1.png (Scan Completed)
- Screenshot_2.png (Alert Details)

---

Report:

See `ZAP_Report.pdf` in this repository for the full scan output.

---

Skills Gained:

- Web application security assessment
- Interpreting HTTP security headers
- Automated vulnerability scanning
- Report writing and alert analysis

---

Conclusion:

This task helped build my practical skills in identifying real-world web application vulnerabilities and understanding secure web development practices. It was an excellent introduction to ethical hacking and automated scanning.
