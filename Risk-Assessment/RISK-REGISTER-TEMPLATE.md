# Risk Register

## Purpose

This risk register documents identified risks to the SMB, their likelihood and impact, and mitigation strategies.

## Risk Register

### Risk #1: Ransomware Attack

| Field | Details |
|-------|----------|
| **Risk ID** | R-001 |
| **Risk Category** | Malware/Cyber Attack |
| **Description** | Ransomware encrypts critical business data, rendering systems unusable |
| **Threat Actors** | Cybercriminals, organized groups |
| **Attack Vector** | Phishing, unpatched vulnerabilities, compromised credentials |
| **Likelihood** | High (3/5) - Ransomware is increasingly common |
| **Impact** | Critical (5/5) - Could halt business operations |
| **Risk Score** | 15/25 (Critical) |
| **Current Controls** | Email filtering, endpoint protection |
| **Gaps** | No immutable backups, limited monitoring |
| **Mitigation Strategies** | Implement 3-2-1 backups, user training, segmentation, EDR |
| **Owner** | IT Manager |
| **Target Residual Risk** | Low (2/5) |
| **Status** | In Progress |
| **Target Completion** | [Date] |

### Risk #2: Phishing and Social Engineering

| Field | Details |
|-------|----------|
| **Risk ID** | R-002 |
| **Risk Category** | Social Engineering |
| **Description** | Employees clicked malicious links or provide credentials to attackers |
| **Threat Actors** | Cybercriminals, competitors |
| **Attack Vector** | Email phishing, SMS spoofing, pretexting |
| **Likelihood** | High (4/5) - Common and effective |
| **Impact** | High (4/5) - Could lead to account compromise and data access |
| **Risk Score** | 16/25 (Critical) |
| **Current Controls** | Email spam filtering, basic awareness |
| **Gaps** | No multi-factor authentication (MFA), limited training |
| **Mitigation Strategies** | Implement MFA, security awareness training, phishing simulations |
| **Owner** | Security Awareness Lead |
| **Target Residual Risk** | Medium (2/5) |
| **Status** | Planning |
| **Target Completion** | [Date] |

### Risk #3: Insider Threat

| Field | Details |
|-------|----------|
| **Risk ID** | R-003 |
| **Risk Category** | Insider Threat |
| **Description** | Current or former employee misuses access to steal or damage data |
| **Threat Actors** | Disgruntled employees, competitors |
| **Attack Vector** | Credential misuse, data exfiltration, sabotage |
| **Likelihood** | Medium (2/5) - Varies by industry and security culture |
| **Impact** | High (4/5) - Potential significant data loss or damage |
| **Risk Score** | 8/25 (Medium) |
| **Current Controls** | Basic access controls, manual auditing |
| **Gaps** | No user activity monitoring, no data loss prevention (DLP) |
| **Mitigation Strategies** | Implement access controls, user activity monitoring, DLP, background checks |
| **Owner** | HR Director, IT Manager |
| **Target Residual Risk** | Low (2/5) |
| **Status** | Planning |
| **Target Completion** | [Date] |

### Risk #4: Data Breach

| Field | Details |
|-------|----------|
| **Risk ID** | R-004 |
| **Risk Category** | Data Security |
| **Description** | Sensitive customer data is compromised due to inadequate controls |
| **Threat Actors** | Cybercriminals, hacktivists |
| **Attack Vector** | Weak credentials, unpatched systems, misconfiguration |
| **Likelihood** | Medium (3/5) |
| **Impact** | Critical (5/5) - Regulatory fines, reputation damage |
| **Risk Score** | 15/25 (Critical) |
| **Current Controls** | Basic firewalls, some encryption |
| **Gaps** | No data classification, inconsistent encryption, no DLP |
| **Mitigation Strategies** | Implement encryption, access controls, data classification, monitoring |
| **Owner** | CISO/IT Security Lead |
| **Target Residual Risk** | Low (1/5) |
| **Status** | In Progress |
| **Target Completion** | [Date] |

### Risk #5: Unpatched Vulnerabilities

| Field | Details |
|-------|----------|
| **Risk ID** | R-005 |
| **Risk Category** | System Administration |
| **Description** | Unpatched systems exploited by attackers |
| **Threat Actors** | Automated scanners, exploit kits |
| **Attack Vector** | Known vulnerability exploitation |
| **Likelihood** | High (4/5) - Unpatched systems commonly exploited |
| **Impact** | Medium (3/5) - System compromise possible |
| **Risk Score** | 12/25 (Medium-High) |
| **Current Controls** | Manual patching, periodic updates |
| **Gaps** | No automated patch management, no testing environment |
| **Mitigation Strategies** | Implement patch management tool, testing, automation |
| **Owner** | System Administrator |
| **Target Residual Risk** | Low (1/5) |
| **Status** | Planning |
| **Target Completion** | [Date] |

## Risk Summary

- **Total Risks Identified**: 5
- **Critical Risks**: 2 (R-001, R-004)
- **High Risks**: 1 (R-002)
- **Medium Risks**: 2 (R-003, R-005)

## Next Steps

1. Review and validate all identified risks
2. Prioritize mitigation efforts
3. Assign owners and timelines
4. Develop detailed mitigation plans
5. Schedule quarterly risk register reviews
