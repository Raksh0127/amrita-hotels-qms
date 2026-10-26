TEAM 7 HOTEL & TRAVEL BOOKING QMS
==================================

Files
- index.html: self-contained interactive QMS prototype.
- README.txt: setup and feature guide.

Run locally
1. Extract the ZIP.
2. Open login.html in a current browser such as Chrome or Edge. The dashboard redirects to the login page until you sign in.
3. Enter any valid email address and a password of at least 6 characters to continue. This is a demo-only login gate; it does not authenticate users.
4. No Python, database server, package installation or internet connection is required.

Features
- Overview dashboard and lifecycle workflow.
- CRUD for requirements, reviews and verification activities, defects/NCRs, change requests, CAPA actions, and controlled documents.
- Search and status filtering for record tables.
- Requirements baseline states and change control board workflow.
- Defect classification tailored to availability and booking/payment transaction failures.
- Editable quality metric values and targets.
- Rule-based release gate with a Go/Hold outcome.
- Release decision record and JSON/CSV export.
- Browser localStorage persistence.
- Demo login gate with optional remembered access.

Prototype limits
- Data is stored in the current browser profile only. It is not a multi-user production service.
- Sample records and metric values are illustrative. Replace them with verified project evidence.
- Authentication, role-based authorization, server-side audit trails, database transactions, email notifications and integrations are not implemented.
- The login page only demonstrates a client-side flow. It does not verify credentials and must not be used to protect real or sensitive data.
- The release gate is a teaching aid. A real release requires accountable human approval and verified CI/CD evidence.

Suggested demo sequence
1. Requirements: baseline REQ-001 and REQ-002, then add a requirement.
2. Defects: inspect DEF-001 and DEF-002, update status, add evidence.
3. Change Control: approve a request only after completing impact review.
4. Metrics: edit values and targets.
5. Release Gate: observe HOLD RELEASE while critical gates fail.
6. CAPA: record root cause and prevention.
7. Documents: keep the quality plan, test plan and release report versioned.
8. Export JSON as a backup.
