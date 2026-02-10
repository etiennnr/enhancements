# Gardener Enhancement Proposals (GEPs)

A **Gardener Enhancement Proposal (GEP)** is the primary mechanism to propose, communicate, and coordinate **project-wide changes** for the Gardener project.

GEPs are used for topics that require discussion and decision-making in Gardener's **Product Steering Committee (PSC)** and/or **Technical Steering Committee (TSC)**.

---

## 🚀 Quick Start for the GEP Process

1. **Socialize the idea early**
   - Discuss your idea with the Gardener community or relevant stakeholders.
   - Suitable forums include:
     - Gardener Slack channels
     - Direct discussions with community members
     - Direct discussions with PSC/TSC members
   - The goal is to validate that the topic is worth pursuing and that there is sufficient interest to move forward.

2. **Create a GEP**
   - Follow the [process](../README.md#-how-to-propose-a-gardener-enhancement) and structure outlined in the [**GEP template**](./NNNN-gep-template/README.md).
   - Submit the proposal as a Pull Request to this repository.
   - A PSC or TSC member will coordinate review and scheduling for the relevant steering meeting.

---

## ❓ FAQs

### Do I have to use the GEP process?

In most cases, **yes**.

GEPs are required for **non-trivial, project-wide changes**, in particular for:

- Proposals that may be **controversial**
- **New features** beyond very small, incremental additions
- **Major changes** to existing functionality
- Topics with **cross-team or ecosystem-wide impact**
- **New extensions** in the Gardener organizatino
- Changes requiring **PSC or TSC discussion**

The goal is to keep the process lightweight enough that using a GEP is the **default** for significant changes.

---

### Why should I use the GEP process?

The GEP process exists to provide **clarity, transparency, and alignment** across the Gardener project.

Benefits include:

- A **single, discoverable place** for major proposals and decisions
- Clear articulation of **motivation, scope, and intent**
- A structured process with **explicit reviewers and decision-makers**
- A durable, searchable **record of decisions and rationale**
- Early feedback that often prevents costly redesigns later

The process is inspired by established proposal systems such as IETF RFCs, Python PEPs, Rust RFCs, and Kubernetes GEPs, but adapted to Gardener's governance model.

---

### How do PSC and TSC fit into the GEP process?

Gardener has **no SIG-based ownership model**.

Instead:

- **Product Steering Committee (PSC)**
  Evaluates proposals at an **early stage**, focusing on:
  - Vision and strategy
  - Prioritization and roadmap fit
  - The **"Whether / Why"** question

- **Technical Steering Committee (TSC)**
  Evaluates proposals at a **later stage**, focusing on:
  - Architecture and technical direction
  - APIs, interfaces, and design choices
  - The **"How"** question

A topic typically goes to:
- **PSC first**, and
- **TSC later**, once a concrete technical design exists.

---

### Where do GEPs live?

All **project-wide GEPs** live in this repository.

There are **no SIG subdirectories**.  
Instead, GEPs are organized by steering context (e.g., Product vs. Technical).

Subproject-internal proposals **do not belong here** unless they meet the criteria for PSC or TSC discussion.

---

### When should I *not* use a GEP?

You usually **do not** need a GEP for:

- Small, isolated bug fixes
- Minor, non-controversial enhancements
- Changes scoped strictly to a single subproject that do **not** meet steering criteria

When in doubt, err on the side of creating a GEP or ask a PSC/TSC member for guidance.

---

### How mature is the GEP process?

The GEP process is intentionally **evolving**.

Indicators of a healthy process include:
- A growing set of well-structured GEPs
- Timely steering discussions and documented decisions
- Public, searchable proposals and outcomes

Improvements to the process are welcome and can be proposed via Pull Requests to this repository.

---

### What is the naming convention for GEPs?

GEPs are now prefixed with their associated tracking issue number. This gives
both the GEP a unique identifier and provides an easy breadcrumb for people to
find the issue where the current state of the GEP is being updated.

### My FAQ isn't answered here!

The GEP process is still evolving!
If something is missing or not answered here feel free to reach out to the steering committee members.
If you want to propose a change to the GEP process you can open a PR with your proposal.
