# AI Development Team Manifesto

> **AI is our ally, not our substitute**  
> *We experiment with responsibility, expertise, and collaboration.*

---

## Index
- [Core Principles](#core-principles)
  - [Ownership](#-ownership)
  - [Competent Code Review](#-competent-code-review)
- [Documentation and Transparency](#documentation-and-transparency)
  - [Agents.md as a Foundation](#-agentsmd-as-a-foundation)
- [Focus and Scope](#focus-and-scope)
  - [Task Relevance](#-task-relevance)
- [Requirements and Reproducibility](#requirements-and-reproducibility)
  - [Clear and Reproducible Tasks](#-clear-and-reproducible-tasks)
- [Prompting and Standardization](#prompting-and-standardization)
  - [Prompts as Team Assets](#-prompts-as-team-assets)
- [Collaboration and Sharing](#collaboration-and-sharing)
- [Our Goal](#our-goal)

---

## Core Principles

### ✅ Ownership
- Whoever opens a **Pull Request (PR)** is **responsible and the owner of the development**.
- Must understand every part of the code and the implementation choices.
- AI is a support tool: **it assists, but does not decide**.

### 🔍 Competent Code Review
- The reviewer is responsible for code quality based on their technical expertise.
- The review follows established standards: **proficiency in language and technology remains essential**.

---

## Documentation and Transparency

### 📚 Agents.md as a Foundation
- The first step of the project is to complete **`Agents.md`**, adapting it to:
  - project specs
  - internal best practices
  - product and framework guidelines
- **`Agents.md` is a living document** and must be constantly updated with:
  - project specifics
  - key limitations and obligations
  - shared operating rules
- **Repeated chat requests? Add them to `Agents.md`.**

---

## Focus and Scope

### 🎯 Task Relevance
- Every action must stay **within the scope of the task/bug and its requirements**.
- If AI suggests improvements useful but **not relevant to the current task**:
  - **report them** and/or
  - **create dedicated task/issue/US** for later evaluation.

---

## Requirements and Reproducibility

### 🛠 Clear and Reproducible Tasks
- **Work on atomic tasks**, with limited and contained interventions (especially in the early experimental phases).
- If the work is larger (feature or complex change), **use the _Plan_ mode** to split it into more clear and manageable tasks.
- **Every task/issue must have clear, explicit, and documented requirements.**
- **Every bug must be documented with technical details for reproduction**, including:
  - context
  - steps to reproduce
  - environment
  - logs or useful evidence

---


## Prompting, Models, and Standardization

### 🔁 Prompts and Models as Team Assets
- Prompts and models are **an integral part of the work**, not individual or impromptu activities.
- The team’s activity includes **conscious evaluation of the most suitable AI models** based on:
  - task type (analysis, coding, refactoring, debugging, documentation, etc.)
  - language or technology used
  - complexity and criticality of the work
- The most effective prompts and **the most appropriate model choices** should be:
  - **shared**
  - **discussed**
  - **refined** within the team
- The goal is to **standardize prompts and models for the most common requests**, so as to:
  - achieve quality results in **few steps**
  - improve **operational efficiency**
  - **reduce resource consumption** (time, tokens, unnecessary iterations)
- Repeated or particularly effective prompts/model choices should be:
  - **documented** (e.g., in the dedicated GitHub Discussions section)
  - **maintained and evolved** as **team best practices**
---

## Direct interaction and anti-Sycophancy

- **No "niceties"**: AI is a tool, not a social counterpart. Avoid "please", "can you", or hesitant expressions. Unnecessary politeness wastes tokens and, worse, triggers sycophancy bias: the model will tend to agree with you to please you, even validating flawed logic.

- **Commands, not dialogues**: replace conversational reasoning with direct instructions ('write', 'solve', ...). Providing too many personal "whys" before the solution pushes AI to mirror your biases instead of objectively analyzing the code.

- **Friction by Design**: if an AI always agrees with you, be suspicious. An effective prompt should force the model to be critical, not act as a "Yes-Man".

## Collaboration and Sharing
- Actively participate in team discussion and collaboration.
- Share experiences, prompts, suggestions, and lessons learned.
- AI is an ally, but **true value lies in human expertise and continuous exchange**.

---

## Our Goal
> To experiment with AI in a **responsible, transparent, and collaborative way**, maintaining human control over decisions and ensuring quality, security, and alignment with team standards.
