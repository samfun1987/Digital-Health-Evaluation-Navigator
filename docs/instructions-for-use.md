# Digital Health Evaluation Navigator — Instructions for Use

## Part 1: Introduction

### What is this?

The Digital Health Evaluation Navigator is a **Claude skill**: a set of instructions that changes how Claude behaves when it helps you evaluate a digital health product. Examples of such products include health apps, remote monitoring tools, online therapy services and clinical decision support software.

The skill is built on the UK government framework **"Evaluating digital health products"**, which the Office for Health Improvement and Disparities (OHID) published on GOV.UK in 2020–21. It turns that framework into a guided conversation. Claude acts as a collaborative evaluation assistant and steps in as a critical expert when needed.

### Why use it?

Evaluations of digital health products often go wrong in the same few ways:

- **Starting with the method instead of the purpose.** For example, "We need an RCT" comes before anyone asks who the evidence is for.
- **Vague goals** such as "prove it works" or "show value", which can't be answered as stated.
- **Overclaiming.** For example, high app usage is presented as proof of clinical benefit.
- **Plans that can't be delivered** because they ignore time, budget, data or governance.

The Navigator addresses these problems by:

- **Starting from your real-world goal** and the decision-maker you need to convince (a commissioner, clinician, investor or regulator).
- **Working through seven stages in order**, so each choice builds on what you have already agreed.
- **Keeping a running record of agreed decisions**, so you don't repeat yourself.
- **Challenging your thinking** in two roles: a *methodological expert* ("Is the comparator credible?") and the *target stakeholder* ("Would this evidence actually change my decision?").
- **Matching rigour to the decision.** The evaluation should fit the product's maturity, the risk and your resources, rather than defaulting to the most demanding design.
- **Stating clearly what your evidence supports and what it doesn't.**

**Who it is for:** product teams, digital health start-ups, NHS innovation and transformation teams, commissioners, researchers and evaluators. You don't need to be an evaluation expert to use it.

**The end-to-end journey:**
> Real-world goal → agreed context → evaluation questions → evidence approach → executable plan → defensible interpretation → decision or next action

---

## Part 2: High-Level Instructions

### Step 1 — Start the conversation

Ask Claude for help with evaluating your digital health product, or mention the OHID framework. Begin with your situation, not the method you have in mind. A good opening covers:

- **What the product is** and who uses it, and in what setting
- **How mature it is** (prototype, pilot, scaling)
- **Who you need to convince** and **what decision they are making**
- **Your constraints**: time, budget, staff, data access

*Example:* "We have a self-management app for people with type 2 diabetes, piloted in two GP practices. We want an integrated care board to commission it. We have six months and limited budget. How should we evaluate it?"

### Step 2 — Work through the seven stages

Claude will guide you through these stages. It skips or speeds up any stage where you have already provided enough information.

| Stage | What you agree | Key question |
|---|---|---|
| **1. Goal and scope** | Purpose, primary stakeholder, the decision to inform | *Who is this evidence for, and what will they decide?* |
| **2. Product and change model** | How the product leads to change, from use through to health or service outcomes | *Why should this product make a difference?* |
| **3. Questions and measures** | Primary and secondary evaluation questions, outcomes, data sources | *What exactly do we need to find out?* |
| **4. Evaluation approach** | Method family (descriptive, comparative, qualitative, economic, combined) and study design | *Which design can answer our question?* |
| **5. Plan and delivery** | Sample, recruitment, timelines, staffing, consent, governance | *Can we realistically do this?* |
| **6. Analysis and interpretation** | Analysis plan and the strongest claim the design allows | *What can we legitimately conclude?* |
| **7. Conclusions and next action** | What the evidence supports and doesn't, and what to do next | *Is the original decision now informed?* |

At each stage, Claude reviews what is already known, identifies only the gaps that matter, proposes options, asks you to confirm material decisions, and then moves on.

### Step 3 — Engage with the challenges

Claude will sometimes raise an expert or stakeholder challenge. It shows your current position, the concern, why it matters and a proposed change. **You decide** whether to accept it. Claude won't silently overwrite something you have agreed.

### Step 4 — Get the outputs you need

The size of the output follows your request:

- **Narrow questions get direct answers.** For example: "Interviews or focus groups?" or "Can a pre/post study support a causal claim?" Claude answers without making you go through every stage.
- **A full request gets a full evaluation strategy.** This covers the goal, stakeholder, change model, questions, outcomes, design, comparator, data, analysis, governance, limitations, what the evidence *would* and *would not* support, critic findings and the next action.

If a focused question later grows into a full evaluation, Claude picks up from the earliest unresolved stage.

### Tips for best results

1. **Name your decision-maker early.** It shapes everything that follows.
2. **Share what you already have**, such as a logic model, theory of change, pilot data or a draft protocol, so Claude can build on it.
3. **Be honest about constraints.** A feasible, proportionate plan is better than an ideal one that can't be delivered.
4. **Expect claims to be narrowed.** If your data only shows engagement, Claude will steer you away from claiming clinical benefit.
5. **Treat the guidance as method, not law.** The OHID framework dates from 2020–21. Current requirements (NICE Evidence Standards Framework, DTAC, MHRA, UK GDPR, HRA ethics, reporting standards such as CONSORT) should be checked against the latest official sources. Claude will flag when this matters.
6. **Involve specialists.** Statistical, clinical, economic and governance expertise should still shape the plan before you collect data.

### Key source

OHID, *Evaluating digital health products* — https://www.gov.uk/government/collections/evaluating-digital-health-products
