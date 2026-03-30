# Contributing to Awesome Real-World Problems

Thanks for contributing.

This repository exists to help developers build more meaningful portfolio and open-source projects by focusing on **real-world problems**, not generic app ideas.

We welcome contributions that make this collection more useful, more realistic, and more actionable for the community.

---

## What belongs in this repository?

This project is for **real-world pain points** that developers can explore through software, data, automation, workflows, or digital tools.

Good contributions usually describe:

- a clear operational problem
- who is affected by it
- why it matters
- the real-world context around it
- constraints that make the problem interesting
- enough detail to inspire different implementation approaches

Examples of good entries:

- Patients are hard to monitor after they leave the clinic
- Small businesses often lack reliable inventory control
- Sales and marketing teams rely on conflicting lead numbers
- Volunteers are hard to coordinate across schedules and responsibilities

---

## What does **not** belong here?

Please avoid contributions that are only:

- generic app ideas
- product clones
- feature lists without a real problem behind them
- vague startup concepts
- “build an app for X” without context
- over-engineered solution proposals

Examples of weak entries:

- Build a to-do app
- Create a CRM
- Make a marketplace
- Build a school platform
- Create an AI assistant for everything

These may be valid projects, but they are **not problem statements**.

---

## Core editorial principles

### 1. Problem-first, not solution-first
Describe the pain point before suggesting what could be built.

Prefer this:
- Parents lack clear visibility into a student’s actual progress

Instead of this:
- Build an app for parents to track students

---

### 2. Focus on reality
Entries should feel connected to actual workflows, operations, and constraints.

Try to include:
- who experiences the problem
- where it happens
- what makes it difficult
- why current approaches fail

---

### 3. Keep it broad enough for creativity
A good problem should allow multiple possible solutions.

Do not lock contributors into only one format or one product idea.

Prefer:
- Communication is fragmented between importers, brokers, suppliers, and carriers

Avoid:
- Build a dashboard with a Kanban board, AI chatbot, map, and blockchain tracking

---

### 4. Be descriptive, not inflated
Clear and practical language is better than buzzwords.

Avoid:
- Revolutionary digital transformation pain point for next-gen ecosystems

Prefer:
- Donation tracking is messy for small NGOs with limited staff

---

### 5. Optimize for portfolio and open-source value
The best entries usually involve:
- real users
- real workflows
- role-based interactions
- messy or fragmented data
- operational decisions
- meaningful MVP opportunities

---

## What you can contribute

You can contribute by:

- adding a new problem
- improving an existing problem statement
- refining wording for clarity and realism
- adding a new category
- translating documentation or category pages
- improving documentation and contribution guidelines
- finding duplicates or overlapping entries

---

## Repository structure

```text
awesome-real-world-problems/
├── .github/
├── categories/
│   ├── daily-life/
│   ├── education/
│   ├── healthcare/
│   ├── hr/
│   ├── international-trade/
│   ├── local-commerce/
│   ├── logistics-transport/
│   ├── ngos-social-impact/
│   ├── pets/
│   └── sales-marketing/
├── docs/
├── templates/
├── CONTRIBUTING.md
├── CONTRIBUTING.pt-BR.md
├── README.md
└── README.pt-BR.md
```

Each category folder currently contains:

- a README.md in English
- a README.pt-BR.md in Portuguese
- individual problem files in English

Example:

```
categories/
  pets/
    README.md
    README.pt-BR.md
    disorganized-pet-history.md
    difficulty-monitoring-basic-pet-health.md
```

## How to add a new problem

### 1. Check for duplicates

Before opening a PR, make sure the same problem is not already listed in another category or with slightly different wording.

### 2. Choose the right category

Add the problem to the category where it most naturally belongs.

If no category fits well, open an issue suggesting a new one.

### 3. Create the problem entry

Create a new file inside the appropriate category folder:

```categories/<category>/<problem-slug>.md```

Example:

```categories/healthcare/patient-follow-up-breaks-down-between-appointments.md```

Use the problem template in: [Templates](./templates/)

### 4. Update the category index

Add the new problem to the category’s [README.md](README.md).

If the category’s [README.pt-BR.md](README.pt-BR.md) includes mirrored examples or listing structure, update it too when appropriate.

### 5. Keep the entry realistic and useful

Make sure the problem is grounded in real-world context and not just a thin app idea.

#

## Problem Writing guidelines

Each problem entry should aim to answer these questions:

- What is the problem?
- Who experiences it?
- Why does it matter?
- In what context does it happen?
- What makes it hard?
- Why is it a good portfolio/open-source - problem?

A strong entry usually contains:

- a concise title
- a short summary
- a first-person real-world report
- why the problem is difficult
- why it matters
- open-source opportunity
- technical requirements
- suggested MVP
- possible extensions

#

## Title guidelines

Titles should describe the problem, not the product.

Good examples:

- Patient progress is hard to track outside the clinic
- Lead information is scattered across multiple platforms
- Small business owners end up managing everything alone

Avoid:

- Clinic dashboard
- CRM for sales teams
- Volunteer management app

#

## Writing style

Please keep entries:

- clear
- practical
- descriptive
- realistic
- human
- jargon-light

Prefer concrete language over abstract business language.

Good:

- Delivery delays are hard to anticipate and communicate

Weak:

- Logistics stakeholders experience visibility challenges in operational ecosystems

The entry should feel like a person is genuinely describing a real problem, not pitching a startup idea.

#

## Good contribution checklist

Before submitting, check that your entry:

- describes a real-world problem, not just a product idea
- explains who is affected
- explains why the problem matters
- includes useful context
- leaves room for multiple implementation approaches
- is not a duplicate
- is written clearly in English
- is placed in the correct category folder
- is linked from the category README.md

##

### Categories and overlap

Some problems can fit more than one category. That is normal.

Choose the category based on the main context of the pain point.

Example:

- “Fragmented communication between clinics and patients” belongs more naturally in healthcare
- “Fragmented communication between importers and carriers” belongs more naturally in international-trade

If needed, mention cross-category relevance in the entry, but avoid duplicating the same problem in many places.

#

## Translation contributions

The main language of this repository is English.

At the moment, the canonical problem files live in English inside the category folders.

Portuguese (Brazil) is currently used in supporting materials such as:

- README.pt-BR.md
- category-level README.pt-BR.md
- CONTRIBUTING.pt-BR.md

If you contribute a translation:

- preserve the original meaning
- adapt naturally instead of translating word by word
- keep terminology clear and practical
- maintain the same structure as the English version

If the project later adopts translated problem files, contributors should follow the structure defined by the maintainers at that time.

#

### Pull requests

When opening a pull request, please include:

- what you added or changed
- the affected category
- whether it is a new problem, translation, improvement, or new category
- any possible overlap with existing entries

Small, focused pull requests are preferred.

#

## Suggestions for strong contributions

The best contributions usually come from:

- lived experience
- work experience in a domain
- observing operational pain points in real businesses or communities
- translating invisible manual work into visible problem statements

You do not need to provide a complete business analysis.

You do need to make the problem feel real.

Strong

Parents lack clear visibility into a student’s actual progress

- clear users
- real context
- real pain
- multiple solution paths

Weak

Build an app for parents and teachers

- solution-first
- vague
- little context
- no specific pain point

Strong

Small NGOs struggle to coordinate volunteers across schedules and activities

- realistic
- operational
- multi-user
- good portfolio potential

Weak

Volunteer platform

- too broad
- no context
- no pain described

#

## Respect the spirit of the project

This is not a startup idea dump.

This is not a random app-idea list.

This is not a “100 projects to practice React” repository.

This project is about helping developers build things that are closer to the messy, real, constrained problems found in actual life, work, and communities.

#

## Need help?

If you are unsure whether a contribution fits, open an issue first.

Good issue types:

- problem suggestion
- category suggestion
- duplicate discussion
- wording improvement
- translation proposal

#

## License

By contributing, you agree that your contributions will be licensed under the same licenses used by this repository.

See:

- [LICENSE-CONTENT](LICENSE-CONTENT).
- [LICENSE-CODE](LICENSE-CODE).