# Operating Model & Interacture (Human API)

This document describes how we design and run the **governance and operating model** for family office clients using the **Interacture (Human API)** framework.

The goal is to move from:

- Ad hoc, personality-driven decision-making  
→ to  
- Clear, resilient, and documented ways of working that survive stress, turnover, and change.

---

## 1. Principles

1. **Human-first, tech-augmented**  
   Tools support people; they don’t replace them. Decisions and ownership remain clearly with humans.

2. **Clarity over complexity**  
   We prioritize simple, clear interaction rules over intricate frameworks that nobody follows.

3. **Respect for existing relationships**  
   We fit the governance model around the actual people and dynamics already in place.

4. **Actionable in a crisis**  
   Governance must still work when people are stressed, tired, or under pressure.

---

## 2. The Human API Concept

Interacture treats people and teams as if they were well-documented APIs:

- **Inputs:** What information or context they need.
- **Outputs:** What decisions, approvals, or actions they provide.
- **Contracts:** How quickly they respond, and in what format.
- **Failure Modes:** What happens when they’re unavailable or overloaded.

For family offices, this means:

- Defining the “API” for the **principal**, **family office staff**, **advisors**, and **vendors**.
- Making it clear how information flows, who approves what, and how escalation works.

---

## 3. Operating Model Layers

We view the operating model in three layers:

1. **Strategic Layer (Principal / Family Governance)**
   - Sets risk appetite and guiding principles.
   - Approves major changes (vendors, jurisdictions, exposure).
   - Delegates authority formally.

2. **Management Layer (Family Office / Advisor Teams)**
   - Runs day-to-day operations.
   - Owns vendor relationships and implementation.
   - Maintains the risk register and governance calendar.

3. **Execution Layer (Vendors / IT / Providers)**
   - Implements technical and operational controls.
   - Provides evidence and reporting back up the chain.

Our job is to define **how these layers talk to each other**.

---

## 4. Core Artifacts

Every client should have, at minimum:

1. **Governance Charter**
   - Purpose and scope of governance.
   - Who is covered (family members, entities, trusts, etc.).
   - Principles for decision-making and risk management.

2. **RACI Map**
   - Who is **Responsible**, **Accountable**, **Consulted**, and **Informed** for key decisions:
     - New vendor onboarding.
     - High-risk data sharing.
     - Travel and relocation.
     - Major technology changes.
     - Incident response.

3. **Interaction Maps**
   - Visual diagrams showing key recurring interactions:
     - Monthly/quarterly meetings.
     - Incident calls.
     - Vendor reviews.
     - Family education sessions.

4. **Governance Calendar**
   - Annual schedule of key governance events:
     - Quarterly risk reviews.
     - Annual tabletop exercise.
     - Vendor and access reviews.
     - Policy and playbook updates.

---

## 5. Interacture Implementation Approach

We typically follow these steps:

1. **Discovery & Mapping**
   - Interview key people (principal, family office leads, advisors).
   - Map current decision flows, pain points, and bottlenecks.
   - Identify “shadow governance” (how things really work today).

2. **Design & Proposal**
   - Propose a simplified governance model using Interacture patterns.
   - Define roles, responsibilities, and interaction rules.
   - Iterate with the client until it feels realistic and natural.

3. **Documentation & Alignment**
   - Produce charter, RACI, interaction maps, and calendar.
   - Walk stakeholders through the model to align expectations.

4. **Pilot & Adjust**
   - Run the model for one or two governance cycles.
   - Capture friction, misunderstandings, and edge cases.
   - Adjust and harden the model.

5. **Operationalize**
   - Embed the model into recurring meetings, tooling, and playbooks.
   - Ensure new vendors and team members are onboarded into the model.

---

## 6. Example Use Cases

- **New WealthTech Platform:**  
  Who decides to adopt it, who configures it, who monitors alerts, and who approves changes?

- **Suspicious Email / Possible Fraud:**  
  Who is the first call? What information do they need? When do they involve legal or banks?

- **Travel to Higher-Risk Location:**  
  Who approves, what security measures kick in, and who is on-call if something goes wrong?

These scenarios should be captured in the governance documents and playbooks in `ops/`.

---

## 7. Maintenance & Review

Governance decays if it is not reviewed. At a minimum:

- **Annually:**  
  - Revisit charter, RACI, and calendar.
  - Confirm roles and contact details.

- **After Major Events:**  
  - Update governance after incidents, major moves, or leadership changes.

This document should be referenced whenever we design or refresh a client’s operating model.
