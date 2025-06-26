# Deconstructing a Cybersecurity Event

> **Overview**: On May 8, 2023, Dragos, an industrial cybersecurity company, thwarted a cybercriminal group's attempt to extort them. The attackers exploited a business email compromise (BEC) to compromise the personal email account of a new, yet-to-begin employee. Dragos' security tools detected and blocked the attack, including phishing attempts on other employees. Their incident response team successfully prevented any further harm and shared this experience to destigmatize security incidents and aid other organizations in learning from it.
>
> **Objective**: Conduct a Business Impact Analysis (BIA) on the incident. Consider the following aspects:
>
>  - **Financial Impact**: What financial losses or costs did Dragos incur due to this incident?
>
>  - **Operational Impact**: How did the incident affect Dragos' day-to-day operations, including its ability to provide cybersecurity services?
>
>  - **Reputational Impact**: Discuss the impact on Dragos' reputation and relationships with clients and stakeholders.
>
>  - Research additional perspectives that are relevant to the incident

## Business Impact Analysis (BIA): Dragos Cybersecurity Incident

### 1. General Information

- **Organization Name**: Dragos, Inc.
- **System/Process Assessed**: Employee Onboarding Process and Corporate Email Systems
- **Event Date**: May 8, 2023
- **BIA Prepared By**: ---
- **Date of BIA**: ---


### 2. System/Process Description

Dragos is an industrial cybersecurity company specializing in the protection of industrial control systems. On May 8, 2023, the company successfully thwarted a cybercriminal group’s attempt to gain access via a Business Email Compromise (BEC). The attackers compromised the personal email account of a newly hired, not-yet-onboarded employee to conduct phishing campaigns. Dragos’ security systems detected and blocked the attempts, and the internal incident response team mitigated the threat with no operational or data loss.


### 3. Impact Categories and Analysis

#### 3.1 Financial Impact

| **Impact Type**             | **Impact Description**                                                                                         | **Potential Impact Level** |
|----------------------------|------------------------------------------------------------------------------------------------------------------|----------------------------|
| Revenue Delay/Loss         | If undetected, phishing could have disrupted sales or contracts.                                                | Medium                     |
| Unforeseen Expenses         | Potential costs for security training, auditing, and investigation.                                            | Low                        |
| Payment Delays              | No actual delays reported; could have occurred with deeper compromise.                                         | Low                        |
| Penalties/Regulatory Fines  | No fines, but data exposure or poor reporting could have triggered penalties.                                  | Low to Medium              |

---

#### 3.2 Operational Impact

| **Impact Type**           | **Impact Description**                                                                                          | **Potential Impact Level** |
|--------------------------|-------------------------------------------------------------------------------------------------------------------|----------------------------|
| Work Disruptions         | Minimal disruption; significant impact avoided due to prompt response.                                            | Low                        |
| Loss of Key Employees    | No direct loss; potential for stress or reputational effects on affected new hire.                               | Low                        |
| Equipment/System Issues  | No equipment or system outages occurred.                                                                         | None                       |
| Incident Response Effort | Security teams temporarily diverted to handle response and communication.                                        | Low to Medium              |

---

#### 3.3 Reputational Impact

| **Impact Type**             | **Impact Description**                                                                                           | **Potential Impact Level** |
|----------------------------|--------------------------------------------------------------------------------------------------------------------|----------------------------|
| Client Trust               | Improved through transparency; public disclosure was well received.                                              | Positive (Short-term)      |
| Customer Confidence        | No known losses; future recurrence may affect customer perception.                                               | Low                        |
| Market Perception          | Market responded positively to Dragos’ openness and defense posture.                                              | Low                        |

---

#### 3.4 Information Security Impact

| **Impact Type**           | **Impact Description**                                                                                             | **Potential Impact Level** |
|--------------------------|----------------------------------------------------------------------------------------------------------------------|----------------------------|
| Data Exposure             | No sensitive customer or internal data was compromised.                                                            | None                       |
| Credential Compromise     | Only a personal account was compromised; no internal credentials leaked.                                           | Low                        |
| Cybersecurity Posture     | Demonstrated effective defense, bolstering confidence in Dragos’ capabilities.                                     | Positive (Resilience)      |

---

### 4. Recovery Time Objectives (RTO) and Recovery Point Objectives (RPO)

| **System/Function**      | **RTO**       | **RPO**       | **Comments**                                                                 |
|-------------------------|---------------|---------------|------------------------------------------------------------------------------|
| Email Communication     | < 1 hour      | 0 (live data) | Critical for real-time detection and internal coordination.                 |
| Security Monitoring     | Continuous    | Real-time     | Essential for prevention and detection of similar incidents.                |
| Employee Onboarding     | 1–2 days      | N/A           | Minimal impact due to the employee not yet being onboarded.                 |


### 5. Conclusions and Recommendations

- **Overall Business Impact**: **Low**
  - The incident was effectively contained without financial loss or business disruption.

#### Recommendations

- Enhance onboarding security workflows to limit exposure from personal accounts.
- Include personal-corporate account safety in employee security awareness training.
- Continue fostering industry-wide transparency in incident handling and threat intelligence sharing.
