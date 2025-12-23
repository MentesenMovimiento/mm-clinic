# M&M Clinic Platform

A secure, medical-grade, mobile-first platform for multidisciplinary child support clinics.

Built for:
- Education
- Physiotherapy
- Logopedia
- Behaviour support

Primary region: Spain (GDPR & Spanish health data compliant)

---

## 🎯 Purpose

This platform supports collaboration between:
- Clinic staff
- Centre managers
- Directors
- External teachers
- Parents

It provides:
- Secure communication
- Transparent documentation
- Audit-safe records
- Offline-first workflows

---

## 👥 User Roles

| Role | Description |
|----|------------|
Director | Global oversight, security, audits |
Centre Manager | Child assignments, parent/teacher links |
Staff | Clinical & educational work |
Teacher | Read-only plans + chat |
Parent | Gallery, plans, chat |

All access is **child-linked** and **role-restricted**.

---

## 🔐 Security & Compliance

- GDPR compliant
- Spanish health data compliant
- Role-based access control (RBAC)
- Full audit logging
- Encrypted storage & transport
- No data stored in GitHub

---

## ☁️ File Storage

- Google Cloud Storage (EU region)
- Files encrypted at rest & transit
- Access via signed URLs only
- Automatic retention rules

---

## 📴 Offline Support

The app supports offline mode:
- View daily schedules
- Record meetings
- Write logs
- Upload files (queued)
- Auto-sync when online

---

## 🤖 AI Usage Policy

- AI is used for:
  - Speech-to-text transcription
  - Spanish summaries
- AI does **not**:
  - Suggest interventions
  - Replace clinical judgement
  - Train on stored data

---

## 🗂 Data Retention

| Data | Retention |
|----|----------|
Lesson plans | 6 months |
Daily logs | 12 months |
Images | Until child exit |
Transcripts | Archived indefinitely |
Chats | Archived after exit |

All deletions are logged.

---

## 🛠 Tech Stack (Planned)

- Frontend: React Native
- Backend: Node.js (NestJS)
- Database: PostgreSQL
- Storage: Google Cloud Storage
- Notifications: Firebase Cloud Messaging

---

## 🚧 Development Strategy

This platform is built in phases over 2 years:
- Year 1: Core architecture & MVP
- Year 2: Refinement, polish, audit

AI coding assistants may be used with strict architectural prompts.

---

## 📌 Important Notes

- No secrets in repository
- No patient data in repository
- One feature = one branch
- All code must pass permission checks

---

## 📄 License

Private internal use only.
