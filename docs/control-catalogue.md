# Control catalogue

## C-001: Block public cloud storage

| Field | Value |
| --- | --- |
| Risk | Sensitive data may be exposed to the internet. |
| Control type | Preventative |
| Azure enforcement | Azure Policy with a `deny` effect. |
| AWS enforcement | S3 Block Public Access and an organisation guardrail. |
| Control owner | Cloud Security Team |
| Evidence | Pipeline result, policy assignment, compliance report, and deployment commit ID. |
| ISO/IEC 27001:2022 | A.5.23 and A.8.9 |
| NIST CSF 2.0 | PR.PS-01 |
| Review frequency | Every three months, and after a major cloud change. |
