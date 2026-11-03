# Hi, I'm Anchal Kakadia

Full-stack software engineer with an MS in Computer Science from NC State University (2026). I design full-stack applications, real-time data pipelines, and AI-driven systems used in practical environments, and I focus on building systems that are **scalable, observable, and meaningful in real-world use**.

---

## What I care about

I don't start with code. I start with how a system behaves.

I think in terms of data flow, system boundaries, and how things hold up under real-world constraints like latency, incomplete inputs, and edge cases. That perspective shapes how I build, whether it's a real-time data pipeline, a dashboard, or an AI-driven feature.

I build end-to-end systems with React, Next.js, Node.js, TypeScript, and PostgreSQL, with a strong focus on backend flows, correctness, and reliability. I enjoy working across the stack, but I'm most drawn to designing systems where the interactions between components matter as much as the components themselves.

When I use AI, I don't treat it as a plug-in. I treat it as a non-deterministic part of the system that needs structure, validation, and clear boundaries to be useful in production.

Most of my work sits at the intersection of:

- real-time data systems
- backend design and APIs
- AI integrated into structured workflows

---

## What I'm working on now

**Software Developer at Vitelis (since June 2026).** I work on the Vitelis DOP platform with a small team of developers, building full-stack features on Next.js, Supabase/PostgreSQL, and Vercel.

**Research Assistant at NC State's EnBiSys Lab.** I build full-stack systems that process real-time agricultural data and surface insights for stakeholders, using React, Node.js, and Azure PostgreSQL to design APIs, pipelines, and dashboards. My work improved pipeline reliability and reduced failure rates while making the system easier to maintain and extend.

**KitchenIQ (in development).** An iOS-first, AI-assisted pantry and meal-planning app. Details under Selected Work below.

## Previously

**Tailon Labs.** Built a real-time conversational AI system for loan workflows covering voice input, transcription, structured data extraction, and backend integration. The focus was making the system reliable end-to-end, and it reduced onboarding time by 30% for hundreds of users.

**MahiTech.** Worked on offline-first Android systems used by thousands of users, designing storage and sync mechanisms that stayed reliable in low-connectivity environments and reduced processing time.

---

## Selected Work

### 🛒 KitchenIQ: AI-Assisted Pantry & Meal Planning App
**React Native · Expo · TypeScript · Supabase · Python/FastAPI**

I'm building KitchenIQ, a full-stack mobile application that connects grocery intake, household inventory, and meal planning to help reduce food waste. The core idea is to make meal decisions reflect the ingredients a household actually owns, their expiry dates, and its dietary preferences.

The application combines AI-assisted grocery photo analysis with structured pantry management. Users review detected items before confirming inventory changes, maintain a shared household pantry, and build weekly meal plans with connected shopping lists.

- **Mobile application:** Authentication, session restoration, onboarding, camera/gallery intake, and pantry management using Expo Router and TypeScript.
- **Backend and data security:** Household-scoped data access, versioned database migrations, private scan drafts, and persistent inventory workflows.
- **AI integration:** A FastAPI analysis service that translates grocery images into reviewable pantry entries, with explicit confirmation before saving changes.
- **Recommendation workflows:** Deterministic meal recommendations with household dietary filters, recipe details, and editable weekly plans.
- **Notification infrastructure:** Opt-in expiry reminders, device registration, an Edge delivery worker, and receipt tracking.
- **Quality and delivery:** Automated CI checks covering linting, type safety, application tests, database security tests, and iOS bundle export.

The technical challenge is keeping image analysis, shared inventory, recommendations, and reminders consistent across a complete user workflow. The project is currently in development; real-device scan accuracy, push delivery, and deployed behavior remain validation milestones.

### 🔍 LLM-Based Code Review Automation
**Ruby · GPT-4 · GitHub Actions**

Code reviews in academic settings were inconsistent and hard to scale. I built an evaluation pipeline in Ruby that uses GPT-4 to analyze submissions against SOLID principles, with a structured scoring system and GitHub Actions triggers.

- Reduced manual review effort by ~40%
- Standardized feedback across all submissions
- Showed LLMs working as a tool for structured analysis, not just generation

### 💰 Expense Tracker (Microservices Architecture)
**MERN · Docker · JWT · TDD**

A microservices system (auth, analytics, reporting) with JWT-secured REST APIs, built test-first and containerized with Docker, to learn service boundaries and system design beyond implementation.

### 💼 J-Tracker (Intelligent Workflow System)
**React · Node.js · MongoDB · OpenAI API**

Structured application-state tracking with AI-powered resume-to-job comparison and dashboards for data-driven job searching.

### 📊 Interwoven (Research Workflow Platform)
**Next.js · Node.js · MongoDB**

A full-stack platform for submission and peer-review workflows that reduced manual coordination overhead for academic users.

---

## Tech I use

**Languages:** Python, JavaScript, TypeScript, Java
**Frontend / Mobile:** React, Next.js, React Native, Expo
**Backend:** Node.js, Express, FastAPI
**Data:** PostgreSQL, Supabase, MongoDB
**Cloud / DevOps:** Vercel, AWS, Azure, Docker, GitHub Actions
**AI:** OpenAI APIs, prompt design, real-time systems

---

## What I'm working toward

- Designing systems end-to-end, not just implementing parts
- Building AI-powered features that are reliable and measurable
- Contributing to products that solve real problems

---

## Let's connect

[LinkedIn](https://linkedin.com/in/anchaltk) · [GitHub](https://github.com/anchal-kakadia)
