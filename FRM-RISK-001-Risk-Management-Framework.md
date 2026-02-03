# CodeVolt Risk Management Framework

**Document ID:** FRM-RISK-001  
**Version:** 1.0  
**Effective Date:** February 3, 2026  
**Review Date:** February 3, 2027  
**Owner:** Rook (rook@codevolt.co.uk)  
**Approved By:** Senior Management

---

## 1. Purpose

This framework establishes a comprehensive approach to information security risk management aligned with ISO 27005, NIST SP 800-30, and industry best practices.

---

## 2. Risk Management Context

### Risk Appetite
CodeVolt operates with a **moderate risk appetite**:
- Critical risks: Must be mitigated or transferred
- High risks: Require treatment within defined timeframes
- Medium risks: Monitored and treated as resources permit
- Low risks: Accepted with monitoring

### Risk Criteria
Risk evaluation considers:
- Impact on business operations and reputation
- Regulatory and legal compliance requirements
- Financial implications
- Customer trust and relationships

---

## 3. Risk Assessment Process

### 3.1 Risk Identification

**Methods:**
- Asset-based assessment (identify assets → threats → vulnerabilities)
- Scenario-based assessment (what-if analysis)
- Historical incident review
- Threat intelligence analysis
- Supplier and third-party risk assessment

**Sources:**
- Internal audit findings
- Security incident reports
- Vulnerability assessments
- Penetration test results
- Staff observations and reports

### 3.2 Risk Analysis

**Likelihood Scale:**
| Rating | Description | Frequency |
|--------|-------------|-----------|
| 5 - Almost Certain | Expected to occur in most circumstances | > Annual |
| 4 - Likely | Will probably occur in most circumstances | 1-2 years |
| 3 - Possible | Might occur at some time | 2-5 years |
| 2 - Unlikely | Could occur but not expected | 5-10 years |
| 1 - Rare | May occur only in exceptional circumstances | > 10 years |

**Impact Scale:**
| Rating | Business Impact | Examples |
|--------|-----------------|----------|
| 5 - Catastrophic | Business failure, regulatory action, major fines | Complete data breach, prolonged outage |
| 4 - Major | Significant business disruption, major financial loss | Extended service outage, large data loss |
| 3 - Moderate | Moderate business impact, manageable financial loss | Limited data breach, partial service loss |
| 2 - Minor | Minor business impact, small financial loss | Single system failure, minor data exposure |
| 1 - Negligible | Minimal impact, easily absorbed | Cosmetic issues, no data exposure |

**Risk Matrix:**
```
           Impact
         1   2   3   4   5
       +---+---+---+---+---+
    5  | M | H | C | C | C |  L = Low (1-4)
L      +---+---+---+---+---+  M = Medium (5-9)
I   4  | L | M | H | C | C |  H = High (10-16)
K      +---+---+---+---+---+  C = Critical (17-25)
E   3  | L | L | M | H | H |
L      +---+---+---+---+---+
I   2  | L | L | L | M | M |
H      +---+---+---+---+---+
O   1  | L | L | L | L | M |
O      +---+---+---+---+---+
D
```

### 3.3 Risk Evaluation

Risks are evaluated against risk appetite:
- **Critical (17-25):** Exceeds appetite - immediate treatment required
- **High (10-16):** Near appetite limit - treatment required within 30 days
- **Medium (5-9):** Within appetite - treatment planned within 90 days
- **Low (1-4):** Well within appetite - accepted and monitored

---

## 4. Risk Treatment

### 4.1 Treatment Options

| Option | Description | When Used |
|--------|-------------|-----------|
| **Mitigate** | Implement controls to reduce likelihood or impact | Primary approach for most risks |
| **Transfer** | Share risk with third party (insurance, outsourcing) | Financial risks, specialist services |
| **Avoid** | Discontinue activity creating risk | Risk exceeds appetite and cannot be reduced |
| **Accept** | Acknowledge and monitor risk | Low risks within appetite |

### 4.2 Control Selection

Controls selected based on:
- Cost-benefit analysis
- Effectiveness in reducing risk
- Alignment with CodeVolt capabilities
- Compliance requirements
- Industry best practices (NIST, CIS, ISO 27002)

### 4.3 Residual Risk

After treatment, residual risk is:
- Documented in risk register
- Evaluated against risk appetite
- Accepted by appropriate management level
- Monitored on ongoing basis

---

## 5. Risk Register

A risk register is maintained documenting:
- Risk ID and description
- Risk owner
- Current assessment (likelihood × impact)
- Existing controls
- Treatment plan
- Target risk level
- Residual risk
- Review date

Access to the detailed risk register is restricted to authorised personnel.

---

## 6. Monitoring and Review

### 6.1 Ongoing Monitoring

Risk indicators monitored:
- Security incident trends
- Vulnerability discovery rates
- Control effectiveness metrics
- Threat landscape changes
- Regulatory developments

### 6.2 Review Schedule

| Review Type | Frequency | Scope |
|-------------|-----------|-------|
| Critical/High Risks | Monthly | Detailed review of open risks |
| Risk Register | Quarterly | Full register review and updates |
| Comprehensive Assessment | Annually | Complete risk reassessment |
| Trigger-Based | As needed | After incidents, major changes, or new threats |

---

## 7. Roles and Responsibilities

| Role | Responsibility |
|------|---------------|
| **Senior Management** | Set risk appetite, accept residual risks, resource allocation |
| **Information Security Manager** | Coordinate risk assessments, maintain risk register, report to management |
| **Risk Owners** | Manage specific risks, implement treatments, report changes |
| **All Staff** | Report risks, comply with risk treatment measures |

---

## 8. Integration with ISMS

This framework integrates with:
- **POL-ISP-001:** Information Security Policy (governance)
- **POL-INC-001:** Incident Management (risk realisation)
- **POL-BCP-001:** Business Continuity (residual risk treatment)
- **POL-SUP-001:** Supplier Management (third-party risk)

---

## 9. Review

This framework is reviewed:
- At least annually
- Following significant organisational changes
- After major security incidents
- When risk landscape changes materially

---

**Review Cycle:** Annual  
**Next Review:** February 3, 2027  
**Framework Owner:** Information Security Manager

---

*© 2026 CodeVolt. Aligned with ISO 27005, NIST SP 800-30.*
