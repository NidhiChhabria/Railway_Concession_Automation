# 🚆 Railway Concession Automation System
**Vivekanand Education Society's College of Arts, Science & Commerce (VESASC), Mumbai**

> A full-stack automation system that replaced a broken, paper-based railway concession process used by 1,000+ students — reducing processing time from **3 days to same-day** and eliminating physical queues entirely.

---

## 🔗 Official Recognition

This project was officially published on the **VES College institutional website**:
👉 [https://ves.ac.in/vesasc/students-corner/](https://ves.ac.in/vesasc/students-corner/)

---

## 📌 The Problem

Every semester, students at VESASC needed to apply for a railway concession pass — a government subsidy for student commuters on Mumbai's local train network.

The old process looked like this:
- Students filled out **paper forms manually**
- Forms were physically submitted to admin staff
- Staff verified details against records — **by hand**
- The approved forms were stamped and returned to students
- Total turnaround: **2–3 working days**, with no tracking or status updates

This meant long queues, lost forms, repeated visits to the admin office, and zero transparency for students or staff.

---

## 💡 The Solution

I redesigned the entire workflow end-to-end — from student submission to admin approval — as a **fully automated, paperless digital system**.

### How It Works

**Student Side:**
- Student enters their **7-digit Student ID** → personal details auto-populate from the database (no manual entry)
- Student fills in railway details: period, class, stations, pass number, voucher number
- Student uploads verification document (Aadhaar or Railway Pass) — stored directly to **Google Drive**
- One-click submission via the online form

**Admin Side:**
- Admin accesses a **centralised dashboard** showing all submissions in real time
- Dashboard displays live stats: Total Applications, Pending, Verified, Rejected
- Admin can **Verify or Reject** each application with one click
- Rejected applications automatically trigger a **resubmission request** to the student
- Full **CSV and Excel export** capability for record keeping
- **Share via Email** function for batch communication

**Deployment:**
- System deployed college-wide via **QR code** — accessible from any device
- No app download required; fully browser-based

---

## 📸 Screenshots

### Student Form — Personal Details
> Student ID triggers auto-population of name, email, course, and address

![Student Form - Personal Details](screenshots/student_form_personal.png)

### Student Form — Railway Details & Document Upload
> Students select period, class, route, and upload verification documents

![Student Form - Railway Details](screenshots/student_form_railway.png)

### Admin Dashboard — Live Application Tracking
> Real-time view of all applications with one-click verify/reject actions
> *(Student data blurred for privacy)*

![Admin Dashboard](screenshots/admin_dashboard_blurred.png)

---

## 📊 Impact

| Metric | Before | After |
|--------|--------|-------|
| Processing Time | 2–3 working days | Same day |
| Physical queues | Daily, 30+ mins | Eliminated |
| Data entry errors | Frequent (manual) | Near zero (auto-populated) |
| Total applications handled | — | **383+** |
| Applications verified | — | **205** |
| Status transparency | None | Real-time dashboard |

---

## 🛠️ Tech Stack

| Component | Technology |
|-----------|-----------|
| Backend / Logic | Google Apps Script |
| Frontend | HTML, CSS, JavaScript |
| Database | Google Sheets (Student Records) |
| File Storage | Google Drive |
| Deployment | QR Code (browser-based, no install) |

> **Note:** Source code is not publicly available due to institutional confidentiality. This repository documents the system design, workflow, and real-world impact.

---

## 👩‍💻 Built By

**Nidhi Chhabria** — BSc Data Science, VESASC Mumbai (CGPA: 9.8/10)

[LinkedIn](https://linkedin.com/in/nidhichhabria10) · [GitHub](https://github.com/NidhiChhabria)# Railway_Concession_Automation
