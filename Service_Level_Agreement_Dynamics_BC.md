# SERVICE LEVEL AGREEMENT (SLA)
## Microsoft Dynamics Business Central Support Services

**Effective Date:** [Insert Date]
**Client:** [Insert Client Name]
**Location:** Australia
**Service Provider:** [Insert Provider Name]

---

## 1. EXECUTIVE SUMMARY

This Service Level Agreement ("SLA") establishes the terms, conditions, and performance expectations for managed support services provided for Microsoft Dynamics Business Central (Business Central) implementations and ongoing operations in Australia.

---

## 2. SERVICE SCOPE

### 2.1 Included Services
- System monitoring and technical support
- Application troubleshooting and issue resolution
- User assistance and training support
- System maintenance and patching
- Performance optimization recommendations
- Backup and disaster recovery support
- Security updates and compliance maintenance

### 2.2 Support Channels
- Email support
- Phone support (during business hours)
- Remote assistance via secure connections
- Web portal ticketing system
- Emergency hotline (24/7 for critical issues)

### 2.3 Exclusions
- Client-caused configuration errors
- Third-party application issues
- Non-standard customizations
- Training on client-specific business processes
- Hardware failures outside Business Central environment
- Issues arising from non-compliance with recommendations

---

## 3. SERVICE AVAILABILITY

### 3.1 Support Hours
- **Standard Support:** Monday to Friday, 8:00 AM - 6:00 PM AEST
- **Extended Support:** Monday to Friday, 8:00 AM - 10:00 PM AEST (Additional fee applies)
- **24/7 Critical Support:** Available for Tier 1 issues (system down)

### 3.2 System Availability Target
- **Production Environment:** 99.5% uptime (excluding scheduled maintenance)
- **Development/Test Environments:** 95% uptime
- **Planned Maintenance Windows:** 2nd and 4th Sunday of each month, 10:00 PM - 12:00 AM AEST (with 2 weeks' notice)

### 3.3 Availability Calculation
```
Availability % = (Total Hours - Downtime Hours) / Total Hours × 100
```

---

## 4. INCIDENT SEVERITY LEVELS & RESPONSE TIMES

### Tier 1 - CRITICAL
**Definition:** System is completely down or unusable; business operations are halted
- **Initial Response Time:** 15 minutes
- **Resolution Target:** 2 hours
- **Escalation:** Immediate
- **Availability Impact:** 24/7 support

### Tier 2 - HIGH
**Definition:** Major functionality is impaired; significant business impact but workaround available
- **Initial Response Time:** 1 hour
- **Resolution Target:** 4 hours
- **Escalation:** Within 2 hours if not progressing
- **Availability Impact:** Standard + Extended support

### Tier 3 - MEDIUM
**Definition:** Minor functionality issue; limited business impact; workaround exists
- **Initial Response Time:** 4 hours
- **Resolution Target:** 24 hours
- **Escalation:** Within 8 hours if not resolved
- **Availability Impact:** Standard support hours

### Tier 4 - LOW
**Definition:** Cosmetic issues, feature requests, general inquiries
- **Initial Response Time:** 24 hours
- **Resolution Target:** 5 business days
- **Escalation:** As needed
- **Availability Impact:** Standard support hours

---

## 5. PERFORMANCE COMMITMENTS

### 5.1 Incident Response
| Metric | Target | Measurement |
|--------|--------|-------------|
| Initial Response | Per tier above | From ticket creation |
| Time to Resolution | Per tier above | From ticket creation to closure |
| First Call Resolution | 40% for Tier 3-4 | Monthly reporting |
| Escalation Adherence | 100% | Per defined timeframes |

### 5.2 Ticket Management
- All tickets logged within 24 hours of receipt
- Status updates provided every 24 hours for Tier 1-2
- Status updates every 48 hours for Tier 3-4
- Root cause analysis provided for all Tier 1-2 incidents
- Closure verification within 3 business days

### 5.3 System Performance
- Database query response time: < 2 seconds (95th percentile)
- Report generation time: < 5 seconds (standard reports)
- User login time: < 10 seconds
- Page load time: < 3 seconds

---

## 6. MONTHLY REPORTING & CREDITS

### 6.1 Service Credits
Credits are applied to the following month's invoice if SLA targets are missed:

| Availability | Credit |
|--------------|--------|
| 99.0% - 99.4% | 5% monthly fee |
| 98.0% - 98.9% | 10% monthly fee |
| 97.0% - 97.9% | 15% monthly fee |
| Below 97.0% | 25% monthly fee |

### 6.2 Reporting
- Monthly SLA Performance Report provided by 5th business day of following month
- Incident summaries and trends analysis
- Recommendations for service improvement

---

## 7. CLIENT RESPONSIBILITIES

### 7.1 Requirements
- Provide timely and accurate information for incident diagnosis
- Implement recommended security patches and updates
- Maintain appropriate user access controls
- Perform regular backups as per recommendations
- Notify provider of configuration changes
- Maintain current contact information for support team

### 7.2 Change Management
- Changes to Business Central environment require 5 business days' notice
- Major changes require testing in development environment first
- Client responsible for testing all customizations before production deployment

---

## 8. LIMITATIONS & EXCLUSIONS

The Service Provider will not be liable for service failures resulting from:
- Client negligence or misuse
- Failure to follow recommendations
- Unauthorized modifications to the system
- Force majeure events (natural disasters, wars, pandemics)
- Third-party service failures (Microsoft services, ISPs, etc.)
- Client-provided hardware or network issues
- Issues arising from non-compliance with software updates

---

## 9. BUSINESS CONTINUITY & DISASTER RECOVERY

### 9.1 Backup Schedule
- Daily incremental backups
- Weekly full backups
- 30-day backup retention minimum
- Monthly backup restoration testing

### 9.2 Recovery Time Objective (RTO)
- Tier 1 incidents: 4 hours
- Tier 2 incidents: 24 hours
- Full system recovery: 48 hours

### 9.3 Recovery Point Objective (RPO)
- Maximum data loss: 24 hours
- Backup tested monthly
- Documented recovery procedures maintained

---

## 10. SECURITY & COMPLIANCE

### 10.1 Security Standards
- All support staff cleared to appropriate security level
- Encrypted communication channels for sensitive data
- Compliance with Australian Privacy Act
- Adherence to ISO 27001 information security standards
- Multi-factor authentication for access control

### 10.2 Compliance
- GDPR compliance (where applicable)
- SOC 2 Type II compliance
- Regular security audits (annual)
- Incident breach notification within 24 hours

---

## 11. SUPPORT ESCALATION PROCEDURE

**Level 1:** Support Technician
- Handles initial triage and standard issues
- Escalates if not resolved within timeframe

**Level 2:** Senior Technical Support
- Complex technical issues
- Performance tuning
- Custom solutions

**Level 3:** Engineering/Architecture
- Critical system failures
- Architectural recommendations
- Microsoft liaison

**Level 4:** Management Escalation
- SLA breach discussions
- Service improvement
- Contract amendments

---

## 12. MAINTENANCE & UPDATES

### 12.1 Scheduled Maintenance
- Maintenance windows: 2nd and 4th Sunday monthly
- Notice provided: Minimum 2 weeks
- Duration: Typically 2 hours or less
- Emergency maintenance: As needed with best effort notification

### 12.2 Update Policy
- Security updates: Deployed within 30 days
- Feature updates: Coordinated with client schedule
- Testing: 5-day testing period minimum in dev environment
- Rollback plan: Available for all updates

---

## 13. TRAINING & KNOWLEDGE TRANSFER

- Initial system training included
- Documentation provided (Standard Operating Procedures)
- User group access and resources
- Annual refresher training (basic level)
- Advanced training available (additional fees)

---

## 14. TERM & TERMINATION

### 14.1 Contract Term
- Initial Term: 12 months
- Renewal: Automatic unless 60 days' notice given
- Termination: 30 days' notice required

### 14.2 Transition Support
- 30-day transition assistance upon termination
- Data export and documentation provided
- Knowledge transfer sessions scheduled
- New provider coordination support

---

## 15. FEES & PAYMENT

### 15.1 Service Fees
- Monthly recurring fee: $[Amount] AUD
- Support tier add-ons available
- Emergency response fees: $[Amount] per incident (if outside SLA)
- Additional services: Quoted separately

### 15.2 Invoicing & Payment
- Monthly invoices issued in advance
- Payment due within 14 days of invoice
- Late payment: 1.5% monthly interest applied
- Annual payment: 5% discount available

---

## 16. CONTACTS & ESCALATION

### Primary Support
- **Email:** [support@provider.com.au](mailto:support@provider.com.au)
- **Phone:** +61 2 [Number]
- **Portal:** [https://support.provider.com.au](https://support.provider.com.au)
- **Hours:** Monday-Friday, 8:00 AM - 6:00 PM AEST

### Emergency Escalation
- **24/7 Hotline:** +61 2 [Number]
- **On-Call Manager:** [contact details]

### Account Management
- **Account Manager:** [Name]
- **Email:** [email@provider.com.au](mailto:email@provider.com.au)
- **Phone:** +61 2 [Number]

---

## 17. AMENDMENTS & REVIEWS

- Annual SLA review scheduled
- Changes effective with 30 days' notice
- Both parties must agree to material changes
- Service improvements may be implemented unilaterally

---

## 18. ACCEPTANCE & SIGNATURE

**For the Client:**

Name: _________________________________
Title: __________________________________
Date: ___________________________________
Signature: ______________________________

**For the Service Provider:**

Name: _________________________________
Title: __________________________________
Date: ___________________________________
Signature: ______________________________

---

## APPENDIX A: AUSTRALIAN COMPLIANCE NOTES

### Relevant Legislation
- Privacy Act 1988 (Cth)
- Notifiable Data Breaches Scheme (Mandatory breach notification)
- Australian Consumer Law
- Copyright Act 1968 (Cth)

### Data Residency
- All data stored in Australian data centers (where applicable)
- Compliance with Australian Signals Directorate (ASD) guidelines
- Regular compliance audits

### Time Zones
- All times referenced in AEST (Australian Eastern Standard Time)
- AEDT observed during daylight saving (October-April)

---

**Document Version:** 1.0
**Last Updated:** [Insert Date]
**Next Review:** [Insert Date + 12 months]

---

*This Service Level Agreement is a binding contract between the parties and supersedes all prior agreements.*