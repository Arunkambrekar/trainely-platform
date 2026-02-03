\## User Model (Phase 1)



Firestore collection: users



Fields:

\- role: USER | TRAINER | ADMIN

\- status: ACTIVE | PENDING

\- createdAt: timestamp



Rules:

\- USER → ACTIVE by default

\- TRAINER → PENDING by default

\- ADMIN → created manually



