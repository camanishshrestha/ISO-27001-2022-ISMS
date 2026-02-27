# ISO 27001:2022 Statement of Applicability – Bini IT Solutions Pvt. Ltd.

> **© 2026 Bini IT Solutions Pvt. Ltd. | All Rights Reserved.**  
> This document is intended for educational and internal ISMS purposes only. Unauthorized reproduction or use is prohibited.  

---

## Document Metadata
| Field | Details |
|-------|---------|
| Organization | Bini IT Solutions Pvt. Ltd. |
| ISMS Scope | IT infrastructure, cloud services, software development, and business operations |
| Version | 1.0 |
| Last Updated | 27-Feb-2026 |
| Prepared / Approved By | CA Manish Shrestha – ISMS Lead |
| Next Review | 27-Feb-2027 |
| Control Framework | ISO/IEC 27001:2022 |
| Document Owner | Information Security Department |

---

## Control Overview
| Domain | Total Controls | Applicable | Excluded | Implemented | Partial | Planned |
|--------|---------------|------------|----------|-------------|---------|---------|
| Organizational | 37 | 35 | 2 | 28 | 7 | 0 |
| People | 8 | 8 | 0 | 6 | 2 | 0 |
| Physical | 14 | 12 | 2 | 10 | 2 | 0 |
| Technological | 34 | 32 | 2 | 25 | 7 | 0 |
| **Overall** | **93** | **87** | **6** | **69** | **18** | **0** |

> **Note:** “Partial” indicates controls that are implemented but require further enhancement or monitoring.

---

## Theme 5: Organizational Controls
| Ref | Control | Applicable | Status | Control Owner | Evidence / Notes |
|-----|---------|------------|--------|---------------|-----------------|
| 5.1 | Information Security Policies | Yes | Implemented | ISMS Lead | Policies approved by management, published internally |
| 5.2 | Roles & Responsibilities | Yes | Implemented | HR & IT Dept | Roles defined in Org Chart and Job Descriptions |
| 5.3 | Segregation of Duties | Yes | Partial | IT Security | Some overlaps exist; mitigation plan in progress |
| 5.4 | Management Responsibilities | Yes | Implemented | Management Board | Monthly ISMS KPI reviews conducted |
| 5.5 | Contact with Authorities | Yes | Planned | Compliance Officer | Formal communication templates under preparation |
| 5.6 | Contact with Special Interest Groups | No | N/A | N/A | Not applicable for current ISMS scope |
| 5.7 | Threat Intelligence | Yes | Partial | IT Security | Monthly threat reports; automated alerts under development |
| 5.8 | Security in Project Management | Yes | Implemented | Project Managers | Security checkpoints integrated in all IT projects |
| 5.9 | Inventory of Assets | Yes | Implemented | IT Dept | Asset register maintained and reviewed quarterly |
| 5.10 | Acceptable Use of Assets | Yes | Implemented | HR & IT | Staff trained; policies acknowledged via LMS |
| … | … | … | … | … | … |

> *(The rest of Organizational controls follow the same format; see full list in the repo for all 37 controls.)*

---

## Theme 6: People Controls
| Ref | Control | Status | Owner | Notes / Evidence |
|-----|--------|--------|-------|-----------------|
| 6.1 | Employee Screening | Implemented | HR Dept | Background checks completed for all staff |
| 6.2 | Employment Terms | Implemented | HR Dept | Security clauses in all contracts |
| 6.3 | Security Awareness Training | Partial | ISMS Lead | Monthly training ongoing; completion logs maintained |
| 6.4 | Disciplinary Process | Implemented | HR Dept | Policy enforced and documented |
| 6.5 | Post-Termination Responsibilities | Implemented | IT Dept | Access revoked on employee exit |
| 6.6 | NDA / Confidentiality Agreements | Implemented | HR Dept | Signed NDAs for all staff |
| 6.7 | Remote Work Security | Implemented | IT Security | VPN, endpoint protection, MFA enforced |
| 6.8 | Event Reporting | Implemented | ISMS Lead | Clear reporting channels; incident logs maintained |

---

## Theme 7: Physical Controls
| Ref | Control | Status | Owner | Notes |
|-----|---------|--------|-------|-------|
| 7.1 | Physical Security Perimeters | Implemented | Facilities | CCTV & access control in all buildings |
| 7.2 | Physical Entry | Implemented | Facilities | Entry restricted to authorized personnel; logs maintained |
| 7.3 | Securing Offices & Rooms | Implemented | Facilities | Server rooms and critical areas locked & monitored |
| 7.4 | Physical Security Monitoring | Implemented | Security Team | CCTV and patrol logs maintained |
| 7.5 | Protection Against Environmental Threats | Partial | Facilities | Fire suppression installed; flood mitigation pending |
| … | … | … | … | … |

---

## Theme 8: Technological Controls
| Ref | Control | Status | Owner | Implementation Notes |
|-----|--------|--------|-------|-------------------|
| 8.1 | Endpoint Devices | Implemented | IT Security | Antivirus, encryption, and patching applied |
| 8.2 | Privileged Access Rights | Partial | IT Security | RBAC implemented; exceptions under review |
| 8.3 | Information Access Restriction | Implemented | IT Security | Permissions enforced; regular audits |
| 8.4 | Source Code Access | Implemented | Development Team | Repository permissions strictly controlled |
| 8.5 | Secure Authentication | Implemented | IT Security | MFA enforced across all critical systems |
| 8.6 | Capacity Management | Implemented | IT Ops | Resource monitoring dashboards active |
| 8.7 | Malware Protection | Implemented | IT Security | EDR and AV deployed |
| … | … | … | … | … |

---

## Exclusions & Justifications
| Control Ref | Control Name | Reason | Alternative Measure |
|-------------|-------------|--------|------------------|
| 5.6 | Contact with Special Interest Groups | Out of scope | N/A |
| 7.14 | Secure Disposal / Reuse of Equipment | Outsourced vendor | Vendor SLA & certificate maintained |
| 8.12 | Data Leakage Prevention | Partial implementation | Monitoring & partial DLP in place |

---

## Risk-to-Control Mapping
| Risk ID | Risk Description | Controls Addressing Risk |
|---------|----------------|-------------------------|
| R1 | Unauthorized access to sensitive data | 5.15, 6.3, 8.2 |
| R2 | Malware infection on endpoints | 8.7, 8.1 |
| R3 | Data loss due to system failure | 8.13, 7.5 |

---

## Version History
| Version | Date | Author | Notes |
|---------|------|--------|------|
| 1.0 | 27-Feb-2026 | CA Manish Shrestha | Initial release for ISMS portfolio |

---

## Approval Signatures
| Role | Name | Date | Signature |
|------|------|------|-----------|
| Information Security Manager | CA Manish Shrestha | 27-Feb-2026 | - |
| Risk Owner | CA Manish Shrestha | 27-Feb-2026 | - |
| Management Representative | CA Manish Shrestha | 27-Feb-2026 | - |

---

> **Trademark & Copyright**:  
> © 2026 Bini IT Solutions Pvt. Ltd. All rights reserved. This work is proprietary and intended for internal ISMS use. Copying, redistribution, or commercial use without permission is strictly prohibited.
