# Audit-Style Findings and Evidence Gaps

**Ron Richardson | October 6, 2026 | Fictional scenario**

Conditions below summarize authored scenario statements. No real-world technical deficiency or legal violation is confirmed. Underlying test and configuration records are unavailable; causes are not fabricated. P1/P2 and elapsed targets are proposed review priorities, not accepted SLAs.

## A01 — Access and authentication is not substantiated

**Condition:** Least privilege, duty separation and password governance described as absent. No underlying operating-control evidence is retained.

**Criteria:** Proposed review benchmark: approved minimum access, protected recovery and attributable identities. NIST CSF 2.0 PR.AA supplies relevant outcomes; no adopted Botium policy or legal applicability is presumed.

**Cause:** Not established. Review design, provisioning, change and ownership records before assigning a root cause.

**Impact (business risk):** Unauthorized use could expose information and permit improper changes.

**Recommendation and priority:** P1; proposed owner IT/security lead. Request role/grant exports, approval records, authentication tests; agree scope, then authorize necessary treatment. Proposed evidence-review target: 10 business days from authorization. Close only after a reviewer accepts evidence that approved minimum access, protected recovery and attributable identities. A gap is confirmed only when excessive grants or successful disallowed authentication is demonstrated against the approved benchmark.

## A02 — Sensitive-data protection is not substantiated

**Condition:** Encryption and payment isolation described as absent. No underlying operating-control evidence is retained.

**Criteria:** Proposed review benchmark: scoped sensitive data protected; only necessary access permitted. NIST CSF 2.0 PR.DS / PR.IR supplies relevant outcomes; no adopted Botium policy or legal applicability is presumed.

**Cause:** Not established. Review design, provisioning, change and ownership records before assigning a root cause.

**Impact (business risk):** Customer/payment exposure could increase incident cost and disrupt services.

**Recommendation and priority:** P1; proposed owner Data/payment service owner. Request data flows, storage/key settings, cde scope and path tests; agree scope, then authorize necessary treatment. Proposed evidence-review target: 10 business days from authorization. Close only after a reviewer accepts evidence that scoped sensitive data protected; only necessary access permitted. A gap is confirmed only when unprotected sensitive store or prohibited payment-system path is demonstrated against the approved benchmark.

## A03 — Recovery is not substantiated

**Condition:** Backups and recovery planning described as absent. No underlying operating-control evidence is retained.

**Criteria:** Proposed review benchmark: measured restoration, integrity and usability meet approved objectives. NIST CSF 2.0 PR.IR / RC.RP supplies relevant outcomes; no adopted Botium policy or legal applicability is presumed.

**Cause:** Not established. Review design, provisioning, change and ownership records before assigning a root cause.

**Impact (business risk):** Outage or destructive change could interrupt fulfillment and sales.

**Recommendation and priority:** P1; proposed owner Operations lead. Request job history, agreed recovery objectives and isolated restore test; agree scope, then authorize necessary treatment. Proposed evidence-review target: 10 business days; proposed exercise within 30 days from authorization. Close only after a reviewer accepts evidence that measured restoration, integrity and usability meet approved objectives. A gap is confirmed only when recovery fails an agreed business requirement is demonstrated against the approved benchmark.

## A04 — Monitoring and response is not substantiated

**Condition:** Logging/IDS described as absent; firewall/antivirus described as present. No underlying operating-control evidence is retained.

**Criteria:** Proposed review benchmark: relevant events recorded, actionable and routed to an owner. NIST CSF 2.0 DE.CM / RS.MA supplies relevant outcomes; no adopted Botium policy or legal applicability is presumed.

**Cause:** Not established. Review design, provisioning, change and ownership records before assigning a root cause.

**Impact (business risk):** Undetected activity could persist and delay reliable incident scoping.

**Recommendation and priority:** P2; proposed owner Security operations lead. Request coverage inventory, settings, event/alert samples and escalation exercise; agree scope, then authorize necessary treatment. Proposed evidence-review target: 20 business days from authorization. Close only after a reviewer accepts evidence that relevant events recorded, actionable and routed to an owner. A gap is confirmed only when required event missing or escalation fails during a scoped test is demonstrated against the approved benchmark.

## A05 — Privacy and supplier governance is not substantiated

**Condition:** Privacy gaps reported; processing, supplier and contractual scope unavailable. No underlying operating-control evidence is retained.

**Criteria:** Proposed review benchmark: applicable duties established; critical suppliers reviewed and gaps owned. NIST CSF 2.0 GV.SC / GV.PO supplies relevant outcomes; no adopted Botium policy or legal applicability is presumed.

**Cause:** Not established. Review design, provisioning, change and ownership records before assigning a root cause.

**Impact (business risk):** Unsupported assurance could mislead management and leave duties unaddressed.

**Recommendation and priority:** P2; proposed owner Privacy/legal and supplier risk leads. Request purpose/data inventory, applicability review, supplier contracts and assurance; agree scope, then authorize necessary treatment. Proposed evidence-review target: 20 business days from authorization. Close only after a reviewer accepts evidence that applicable duties established; critical suppliers reviewed and gaps owned. A gap is confirmed only when reviewed evidence fails an applicable scoped obligation is demonstrated against the approved benchmark.

All observations remain Pending Verification. Receipt is not acceptance. Actual residual risk is unassessed. Any exception requires risk-owner approval, rationale, compensating safeguards and expiry.
