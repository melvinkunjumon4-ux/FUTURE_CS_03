# FUTURE_CS_03
## API Security Risk Analysis Report — Cyber Security Task 3, Future Interns

### Overview
An API security risk analysis performed as part of the Cyber Security 
Internship program at Future Interns. The goal was to identify common 
API security risks using safe, read-only testing on a public demo API.

### Target
- **API tested:** JSONPlaceholder (jsonplaceholder.typicode.com), a 
public demo API built for testing and educational use

### Scope
- Read-only GET requests only
- No exploitation, authentication bypass, or high-volume/DoS testing
- No production or third-party APIs tested

### Tools Used
- **Postman (Web)** — used to send requests and inspect responses, 
headers, and status codes

### Analysis Approach
Four areas were assessed:
1. Authentication requirements on endpoints returning personal data
2. Access control / ownership verification on individual records
3. Rate limiting behavior under rapid repeated requests
4. Input validation handling for invalid and nonexistent IDs

### Findings Summary
Four findings were identified: missing authentication (High risk), 
absent rate limiting (Medium risk), lack of object-level access 
control / BOLA risk (High risk), and confirmed safe input validation 
handling (positive finding, no risk). Full details, business impact, 
and remediation steps are documented in the report.

### Files in This Repository
- [your report filename].pdf — full API Security Risk Analysis Report
- CYBER___TASK3__evidence_.pdf — Postman evidence screenshots 
supporting each finding

### Deliverable
This report was designed to reflect the kind of analysis a SaaS 
security consultant would deliver to a client — identifying real risk, 
explaining business impact, and providing clear remediation steps.
