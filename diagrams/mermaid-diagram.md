# Security Posture & Remediation Diagram

```mermaid
flowchart TD
    A[Botium Toys Security Posture] --> B[Access Control Failures]
    A --> C[Data Protection Failures]
    A --> D[Incident Response Gaps]
    A --> E[Network Security Gaps]
    A --> F[Compliance Failures]

    B --> B1[No Least Privilege]
    B --> B2[No Password Policies]
    B --> B3[No Password Manager]

    C --> C1[No Encryption]
    C --> C2[PCI DSS Failures]

    D --> D1[No Disaster Recovery Plan]
    D --> D2[No GDPR Breach Notification Plan]

    E --> E1[No IDS]
    E --> E2[Legacy Systems Manual Monitoring]

    F --> F1[PCI DSS: All No]
    F --> F2[GDPR: Mostly No]
    F --> F3[SOC: Mostly No]

    %% Remediation
    B --> R1[Implement RBAC + PoLP]
    C --> R2[Encrypt Data at Rest & Transit]
    D --> R3[Create & Test DRP]
    E --> R4[Deploy IDS + Centralized Logging]
    F --> R5[Compliance Program Overhaul]