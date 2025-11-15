# Family Office Risk Suite – Repo Structure & Conventions (Source of Truth)

This document defines the **canonical structure** for the
`family-office-risk-suite` repository.

If there is ever a conflict between file names, locations, or content roles,
this document is the reference. Update this file when we rename/move things.

---

## 1. Top-Level Layout

family-office-risk-suite/
├─ README.md
├─ docs/
├─ marketing/
├─ sales/
└─ ops/

### 1.1 `README.md`

**Purpose:**  
High-level overview of the Family Office Risk Suite: what this repo is, who it
is for, and links to the most important docs.

**Owner topics:**

- Project description  
- Quick-start pointers (where to look first)  
- High-level roadmap link (`docs/roadmap.md`)  

---

## 2. `docs/` – Strategy, Offers, and Roadmap

docs/
├─ vision.md                  (optional but recommended)
├─ service-catalog.md
├─ packages-and-pricing.md
├─ ideal-client-profile.md    (or ICP section in vision.md)
├─ roadmap.md
└─ repo-structure-and-conventions.md   ← this file

### 2.1 `docs/service-catalog.md`

**Purpose:**  
Defines *what* we offer to family offices (services), not how we price them.

**Owner topics:**

- Individual services:
  - Cyber & Privacy Posture Review
  - HNWI Cyber & Privacy Protection
  - Vendor & WealthTech Risk Oversight
  - Governance & Operating Model (Human API / Interacture)
  - Crisis & Incident Readiness
  - Ongoing Trusted Advisory (Retainer)
- For each:
  - Who it’s for  
  - What we do  
  - Key outputs  

> Pricing lives in `docs/packages-and-pricing.md`, not here.

---

### 2.2 `docs/packages-and-pricing.md`

**Purpose:**  
Defines *how* we package and price services (Package A–F).

**Owner topics:**

- Packages (A–F) with:
  - Typical scope  
  - Deliverables  
  - Indicative pricing bands  
  - Typical duration  

> Service definitions should not be duplicated here; instead reference
> `service-catalog.md`.

---

### 2.3 `docs/ideal-client-profile.md` (or section in `vision.md`)

**Purpose:**  
Document ideal client profiles (ICPs) and signals of fit.

**Owner topics:**

- Primary ICP types (e.g., newly formed SFO, scaling MFO)  
- Positive signals (fit)  
- Negative signals (non-fit)  
- Typical triggering events  

---

### 2.4 `docs/roadmap.md`

**Purpose:**  
High-level project roadmap and phases.

**Owner topics:**

- Phases (Define, Collateral, GTM pilots, Scale)  
- Major milestones and exit criteria  

---

### 2.5 `docs/repo-structure-and-conventions.md` (this file)

**Purpose:**  
Define structure and roles for all directories and key files.

**Owner topics:**

- Directory layout  
- Which file owns which concept  
- Naming conventions  

---

## 3. `marketing/` – External-Facing Messaging

marketing/
├─ website-section-family-offices.md
├─ one-pager-family-office-risk-suite.md
├─ partner-pack-family-offices.md
├─ sample-intro-email-for-advisors.md
└─ family-office-risk-briefing-deck.md

### 3.1 `marketing/website-section-family-offices.md`

**Purpose:**  
Website-ready copy for the “Family Offices” page or section.

**Owner topics:**

- Headline + subheadline  
- Who we serve  
- What we do  
- How we work  
- CTA  

---

### 3.2 `marketing/one-pager-family-office-risk-suite.md`

**Purpose:**  
Copy for a single-page PDF/handout describing the full Family Office Risk Suite.

**Owner topics:**

- Short positioning  
- Who we work with  
- Summary of key services  
- How we work  
- Why families choose us  
- Contact / next step  

---

### 3.3 `marketing/partner-pack-family-offices.md`

**Purpose:**  
Narrative for a 2–4 page “Partner Pack” aimed at advisors (RIAs, attorneys,
CPAs, private bankers).

**Owner topics:**

- Where we fit relative to their services  
- When to introduce us  
- How we protect their relationship  
- Value to advisors  

> Do not duplicate one-pager language; this is advisor-centric.

---

### 3.4 `marketing/sample-intro-email-for-advisors.md`

**Purpose:**  
Email templates advisors can use to introduce us to their clients.

**Owner topics:**

- 1–2 email templates (short + slightly longer)  
- Phrasing that is low-pressure and non-salesy  

---

### 3.5 `marketing/family-office-risk-briefing-deck.md`

**Purpose:**  
Script and slide-by-slide content for the “Family Office Risk Briefing” deck.

**Owner topics:**

- Slide titles and bullet text  
- Speaker notes  
- Structure for a 20–30 minute briefing  

---

## 4. `sales/` – Sales Conversations & Proposals

sales/
├─ discovery-call-script.md
├─ qualification-checklist.md
├─ proposal-package-a-posture-review.md
└─ email-mini-proposal-posture-review.md

### 4.1 `sales/discovery-call-script.md`

**Purpose:**  
Talk track and question set for first calls with family offices or advisors.

**Owner topics:**

- Call structure (opening → discovery → pain → fit → next steps)  
- Core questions by topic  
- Notes/reminder cues  

---

### 4.2 `sales/qualification-checklist.md`

**Purpose:**  
Quick checklist to qualify fit and pick the right package.

**Owner topics:**

- Structural fit  
- Risk and pain signals  
- Appetite for change  
- Financial fit  
- Recommended starting package  

---

### 4.3 `sales/proposal-package-a-posture-review.md`

**Purpose:**  
Proposal / SOW template for the flagship “Posture Review” engagement.

**Owner topics:**

- Objectives  
- Scope  
- Approach  
- Deliverables  
- Timeline  
- Fees & terms  
- Acceptance  

---

### 4.4 `sales/email-mini-proposal-posture-review.md`

**Purpose:**  
Follow-up email template to send after a discovery call when proposing the
Posture Review.

**Owner topics:**

- Light recap of the conversation  
- Short explanation of the Posture Review  
- Ask for permission to send formal proposal (or attach it)  

---

## 5. `ops/` – Delivery & Operations

ops/
├─ assessment-template-outline.md
├─ incident-readiness-outline.md
└─ retainer-service-guide.md

### 5.1 `ops/assessment-template-outline.md`

**Purpose:**  
Outline for the client-facing report produced by the Posture Review.

**Owner topics:**

- Executive summary structure  
- Risk posture overview  
- Detailed findings sections  
- 90-day action plan  
- Appendices (interviews, documents reviewed)  

---

### 5.2 `ops/incident-readiness-outline.md`

**Purpose:**  
Outline for a client-specific incident readiness playbook.

**Owner topics:**

- Scenarios covered  
- Roles and responsibilities  
- First-hour / first 24-hour actions  
- Decision trees  
- Tabletop exercise framework  

---

### 5.3 `ops/retainer-service-guide.md`

**Purpose:**  
Internal/external guide for how ongoing advisory (retainer) works.

**Owner topics:**

- In-scope vs out-of-scope activities  
- Cadence and format  
- Levels of engagement  
- Onboarding and offboarding considerations  

---

## 6. Naming & Versioning Conventions

- File names:  
  - Use `kebab-case` with clear, descriptive names.  
  - Avoid duplicates with slightly different names for the same concept.  

- Versioning (optional):  
  - If we need major versions of a doc, add `v1`, `v1.1` in the filename
    suffix, e.g. `partner-pack-family-offices-v1.md`.  

---

## 7. How to Keep Things Consistent

When adding or changing content:

1. Check this file to see if a related file already exists.  
2. If updating an existing concept, edit the existing file rather than create a new one.  
3. If a new file is truly needed:  
   - Add it in the appropriate directory.  
   - Add a short entry for it in this document under the relevant section.  
4. If you rename or move a file:  
   - Update the reference here so this remains the authoritative map.  
