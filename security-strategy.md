# Risk-to-control mapping (academic scenario)

| Hypothetical risk | Suggested control | Rationale |
| --- | --- | --- |
| Account takeover from password-only authentication | MFA, session timeouts, RBAC | Introduces stronger authentication and access limits |
| Exposure of customer information | TLS, encrypted storage, key management, access controls | Protects data in transit and at rest |
| Web application attacks such as XSS and SQL injection | Secure coding, WAF, patching and regular scanning | Helps prevent and detect common application weaknesses |
| Undetected suspicious activity | SIEM, centralized logs and alerting | Improves monitoring and investigation |
| Privileged account misuse | PAM, individual administrator accounts, least privilege | Supports traceability and reduces excessive access |
| Service interruption or incident escalation | Incident response plan, regular backups, recovery testing | Improves operational resilience |
| Human error and phishing | Role-specific awareness training, phishing exercises | Reduces preventable exposures |

These are the group's **recommendations**, not implemented controls. See the [full report](../report/MIS170_ShopSphere_Final_Report.pdf) for original context and citations.
