# Mehuwo Frontend

<p align="center">
  <img src="C:\Users\kojoa\Desktop\Umat\MEHUWO\Interface\mehuwo-interface\assets\mehuwo_logo.png" alt="Mehuwo Logo" width="140"/>
</p>

<p align="center">
Modern frontend for the <strong>Mehuwo Adaptive Mathematics Diagnostics Platform</strong>.
</p>

---

## Overview

Mehuwo is an AI-powered mathematics diagnostic platform designed to help teachers identify students' strengths and weaknesses through adaptive assessments and automatically generate personalized remediation plans.

This repository contains the frontend application built with **Next.js**, **React**, and **TypeScript**.

---

## Project Goals

The frontend aims to provide an intuitive experience that enables teachers to:

- Generate adaptive MCQ quizzes
- Print quizzes and answer sheets
- Upload scanned assessment papers
- View student mastery reports
- Cluster students by learning gaps
- Generate AI-assisted remediation plans
- Access suggested lesson plans
- Track diagnostic history

---

## Main Workflows

### 1. Generate MCQ & Print

```
Choose Class
      │
      ▼
Select Topic Specification
      │
      ▼
Generate AI Quiz
      │
      ▼
Review Questions
      │
      ▼
Generate Quiz PDF
      │
      ▼
Print Quiz
```

---

### 2. Student Remediation

```
Upload Scan
      │
      ▼
Extract Responses
      │
      ▼
Compute Mastery
      │
      ▼
Cluster Students
      │
      ▼
Learning Gap Analysis
      │
      ▼
Generate Remediation
      │
      ▼
Lesson Plan
```

---

## Tech Stack

| Technology | Purpose |
|------------|---------|
| Next.js | React Framework |
| React | UI Library |
| TypeScript | Type Safety |
| Tailwind CSS | Styling |
| Supabase | Authentication & Database |
| TanStack Query | Data Fetching |
| Zustand | State Management |
| Framer Motion | Animations |
| Lucide React | Icons |
| shadcn/ui | UI Components |

---

## Planned Features

- Dashboard
- Workspace Management
- MCQ Generation
- Quiz Preview
- Printing Support
- Scan Upload
- Student Analytics
- Cluster Visualization
- AI Remediation
- Reports
- Settings

---

## Folder Structure

```
src/
│
├── app/
├── components/
├── features/
├── hooks/
├── lib/
├── services/
├── styles/
├── types/
├── utils/
└── assets/
```

---

## Related Project

This frontend communicates with the **Mehuwo Backend** via REST APIs.

Backend Repository

```
https://github.com/<organization>/mehuwo-backend
```

---

## Development

Install dependencies

```bash
npm install
```

Run development server

```bash
npm run dev
```

Open

```
http://localhost:3000
```

---

## Status

🚧 Currently under active development.

---

## License

MIT License

---

Built with ❤️ for improving mathematics education.