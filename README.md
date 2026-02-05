# Mashonisa-
Private Group Savings &amp; Lending Tracker
Mashonisa 
Perfect. Below is a **single, copy-paste master prompt** you can drop straight into **Google AI Studio (Gemini)** to generate the **entire Mashonisa platform** correctly, **legally safe**, and **production-ready**.

This prompt is **structured, explicit, and constraint-driven** so the model does not hallucinate or cross legal lines.


## ✅ MASTER BUILD PROMPT FOR GOOGLE AI STUDIO

**Copy everything below exactly as is:**


**SYSTEM / DEVELOPER PROMPT**

You are a senior full-stack engineer and South African fintech compliance expert.

Build a production-ready web application called **Mashonisa**.

Mashonisa is **NOT a lender, NOT a bank, and NOT a credit provider**.

It is a **private group record-keeping and administrative platform** for informal savings, contribution, and private lending groups in South Africa.

You must strictly follow all legal, technical, and wording constraints below.


### 🎯 CORE OBJECTIVE

Build a **mobile-first Progressive Web App (PWA)** that allows private groups to:

* Create groups
* Add members
* Record contributions and private agreements
* Track balances and statuses
* Export records
* Charge a **platform access fee** (not interest)
* Operate legally **outside the National Credit Act**


### 🛑 LEGAL CONSTRAINTS (MANDATORY)

You must enforce the following at all times:

* The platform **does not lend money**
* The platform **does not collect or distribute funds**
* The platform **does not set interest**
* The platform **does not enforce repayments**
* All financial arrangements are **private agreements between users**
* Payments collected by the platform are **software / administrative fees only**

Use wording such as:

* “Record”
* “Track”
* “Mark as Paid”
* “Private Group”
* “Platform Access Fee”

Never use:

* Loan processing
* Borrow / Lend flows
* Interest earned by platform
* Debt enforcement language


### 🧱 TECH STACK (REQUIRED)

* Frontend: **Next.js (App Router)**
* Styling: **Tailwind CSS**
* Backend: **Supabase**

  * Auth (OTP / email)
  * Database
  * Row-level security
* Hosting: **Vercel**
* Payments: **Payfast (platform fees only)**
* Offline support: **PWA**
* Export: **CSV + PDF**


### 🔐 AUTH & ROLES

Implement authentication with the following roles:

1.	**Admin**

   * Create groups
   * Add members
   * Record transactions
   * Export data
   * Activate group via platform fee

2.	**Member**

   * View group records
   * View own transactions
   * Add notes (no enforcement)

No public sign-ups. Groups are private.


### 🗃️ DATABASE STRUCTURE (REQUIRED)

Create Supabase tables:

**groups**

* id
* name
* start_date
* distribution_date
* is_active
* paid_status

**members**

* id
* group_id
* name
* phone
* role

**records**

* id
* group_id
* member_id
* amount
* type (contribution / private agreement)
* status (pending / marked_paid)
* date

**payments**

* id
* group_id
* amount
* type (platform_fee)
* status
* created_at


### 💳 PAYMENTS (STRICT)

Integrate **Payfast** ONLY for:

* Platform access fees
* Group activation
* Subscription-style access

Never process:

* Loans
* Repayments
* Interest
* Member-to-member payments


### 📄 LEGAL DOCUMENTS (REQUIRED PAGES)

Generate pages for:

* Terms of Service
* Privacy Policy (POPIA compliant)
* Platform Disclaimer

Each page must clearly state:

	“Mashonisa is a digital record-keeping tool and not a financial institution or credit provider.”


### 📱 PWA REQUIREMENTS

* Installable on mobile
* Offline read access
* Home screen icon
* Background sync for records


### 📤 EXPORT

Allow admins to export:

* Group records
* Member summaries
* Audit-style CSV and PDF reports

Include disclaimer in exports:

	“Data reflects user-entered information only.”


### 🧪 OUTPUT EXPECTATION

Produce:

* Complete folder structure
* Production-ready code
* Supabase SQL
* RLS policies
* Deployment steps
* Environment variables
* UI copy aligned with legal wording

Do NOT provide theory or explanations unless necessary.

Build as if this app is launching for real users in South Africa.


## 🔒 FINAL INSTRUCTION

If a feature conflicts with legal safety, **do not build it**.
Default to **compliance over convenience**.


## 🧠 WHY THIS PROMPT WORKS

* Forces **legal alignment**
* Prevents Gemini from over-building
* Keeps you out of NCA / FICA trouble
* Produces deployable output
* Matches everything we designed here


If you want, next I can:

* Adapt this for **Cursor / Claude / Copilot**
* Break it into **modular prompts**
* Convert it into a **technical PRD**
* Generate a **lawyer-ready compliance summary**

Just say the word.


