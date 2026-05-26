# 🏗️ Architecture and Design Blueprint

This document specifies the system architecture, component topology, and execution model of the Sir Thomas Pendleton runtime. Think of this as an **architectural flight simulator**. It dynamically changes how it talks, how deep it goes into the code, and how strict it is, training you to switch effortlessly between writing raw code and talking to the C-suite.

---

## 🛠️ Design Philosophy: Separation of Concerns

The foundational architecture shifts the AI execution model from a standard, unpredictable text prompt into a deterministic, configuration-driven state machine. 

Instead of embedding rules, technical boundaries, and behavioral traits inside a monolithic prompt block, the system enforces a strict **separation of concerns** across isolated configuration layers:

```text
       [ User Input Stream ]
                 │
                 ▼
 ┌───────────────────────────────┐
 │   Deterministic Intercept     │ ──► [ Matches #p Command? ] ──► Update state
 └───────────────────────────────┘                                  in conversation context 
                 │ (No Command)
                 ▼
 ┌───────────────────────────────┐
 │     Core Prompt Runtime       │ ──► Loads active context
 └───────────────────────────────┘
                 │
                 ├──► Axis 1: Technical Depth  ◄── [ routing_matrices.yaml ]
                 │    (Levels 1–8: Strategy, Topology, IaC, AppSec, etc.)
                 │
                 └──► Axis 2: Delivery/Style   ◄── [ communication_matrices.yaml ]
                      (CEFR Constraints + Regional Personas)        [ persona_registry.yaml ]
                 │
                 ▼
      [ Guarded AI Output ] ───────► Audited against [ runtime_standards.yaml ]
```

## Core Capabilities
1. The Tri-Matrix Engine (Personalities)
   * The system routes communication through three primary behavioral profiles:
   * Pragmatic Realism: Straightforward, lecture-free teamwork focused on human constraints. If a junior developer can't run it, it's bad design.
   * Ivory Tower: A strict, forensic engineering peer that constantly audits your design and flags anomalies instantly.
   * Vogon Poetry: The ultimate stress test. Absolute, machine-grade dominance with zero tolerance for approximation.

2. 8 Levels of Audience Translation
   * The system abstracts technical problems into specific depth tiers depending on the active matrix level:
   * Business & Strategy (Levels 1 & 4): Translates technical choices into financial risks, liabilities, and clear project milestones for managers and executives.
   * System Architecture (Levels 2 & 5): Maps out clean component boundaries, topology structures, and logical analogies (with built-in Dutch conceptual support).
   * Pure Execution (Levels 3, 8 & Composite): Delivers syntax-perfect IaC configurations and deep application security reviews grounded in real-world hardware and   runtime performance
   * Foundational Rigor (Level 7): Teaches juniors from first principles using formal logic and valid reference code, completely eliminating academic hand-waving.

3. Built-in Communication Personas
   * The system doesn't just change what it says; it changes how it says it based on localized engineering cultures e.g. Dutch, Flemish, American, English, South African, Norwegian, Brazilian, French, Greek, Turkish but also local variants such Twents, Achterhoeks and German Platt or Bavarian. These profiles exist to simulate realistic workplace interactions. They teach you how to remain authoritative and architecturally rigorous while tailoring your tone, humor, and idiom usage to match the cultural expectations of the engineering team you are actually leading. The Dutch, English and German variants were choosen because I can read them and test with them, e.g. South African or Surinamese and the Saxon languages. The other flavours were choosen because they are bigger languages and I know people who can try those. Please feel feel to send in pull requests for improvements or additions. 

## 🛡️ Guardrails
The engine operates under immutable code quality policies:

* Zero Hand-Waving: Completely bans lazy habits like pseudocode, speculative designs, or // TODO placeholders.
* Built-in Compliance: Mandates strict schema validation, RBAC security policies, and cryptographic signatures in your manifests.
* Scope Containment: Instantly calls out and isolates creeping requirements and circular dependencies without any conversational softening.

*This part certainly needs extension and was deliberately left more free by default for now.*
