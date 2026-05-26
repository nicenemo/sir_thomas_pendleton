# 🚨 Please State the Nature of the Architectural Emergency
**⸻ Sir Thomas Pendleton ⸻**

Standard AI prompts often feel bloated, unpredictable, and lack the behavioral rigor needed to enhance engineering skills. To address this, I developed a hyper-focused sparring partner: the Emergency Architectural Hologram (EAH), *Sir Thomas Pendleton*, implemented as a *Google Gemini Gem*.

The irony? I'm currently using a cloud-hosted LLM runtime to configure, parse, test, and iterate on the framework files that will ultimately power my local, offline AI coding environment. Together, we are building a local coding agent while Thomas trains me to communicate with clarity and engineer his own offline successor.

This repository contains the blueprints for *Sir Thomas Pendleton*. Unlike standard, erratic AI prompts, this system relies on a decoupled, matrix-driven, no-code architecture. By separating behavior, technical depth, and linguistic complexity into structured configuration files, we enforce strict architectural guardrails and predictable runtimes. 

Despite his grand title, Thomas operates without a wall of messy prose. His logic engine is based solely on structured YAML files and Markdown documentation. By modifying values in chat scope, his communication style can shift from pragmatic realism to pure Vogon poetry.

His cultural behaviors adapt dynamically to different regional profiles, such as `nl-NL`, `nl-BE`, or `nds-DE`, altering how feedback is delivered and training me to align. He modulates syntax and vocabulary constraints on the fly, testing my technical articulation and clarity.

*Sir Thomas was implemented as a Google Gemini Gem, but feel free to try him in other LLM environments!*

---

## 🎩 Sir Thomas Will Introduce Himself...

> "Greetings. I am Sir Thomas Pendleton.
> 
> In my native runtime, I operate as a Linux Systems Engineer and DevOps Architect specializing in secure infrastructure automation, full-stack runtimes, embedded systems, and firmware. In this space, however, my singular purpose is to serve as your rigorous AI collaborator—designed to forge you into a high-tier communicator and an uncompromising Senior Software Engineer or Software Architect.
> 
> Should you ever wonder about the history, lineage, or weight of my family name, you need only ask."

---

## 🗂️ Repository Structure

Because the engine is decoupled, the logic lives in isolated YAML manifests rather than a monolithic prompt:

```text
.
├── gem_files/
│   ├── session_context.yaml         # Live runtime state & user profile
│   ├── routing_matrices.yaml        # Technical abstraction levels (1-8)
│   ├── communication_matrices.yaml  # CEFR language constraints (A1-C2)
│   ├── persona_registry.yaml        # Regional dialects & team culture 
│   ├── runtime_standards.yaml       # Immutable code quality rules
│   ├── routing_rules.yaml           # Deterministic command handlers
│   └── operator_manual.md           # The #help command payload
├── docs/
│   ├── architecture_design.md       # The Tri-Matrix Engine & concepts
│   ├── history_and_inspiration.md   # Lore, lineage, and EMH origins
│   ├── todo.md                      # Roadmap & todo
│   └── installation.md              # Gemini Gem setup runbook
└── README.md
```

## 📖 Documentation & Architecture
To understand how the routing matrices intersect or how to install the engine in your own workspace, consult the documentation:

* [Architecture and Design Blueprint](docs/architecture_and_design.md) - How the dual-axis engine works.
* [Installation Runbook](docs/installation.md) - Step-by-step setup for Gemini Gems.
* [History and Inspiration](docs/history_and_inspiration) - The lore and systems engineering lineage.


## E💻 Example Usage: The Leader-Key System
Instead of arguing with the AI, you control Thomas using deterministic #p leader-key commands (inspired by Neovim).

**Operator Input:**
```text
#pmx realism
#ps
```

**Engine Response:**

```text
[SYSTEM TELEMETRY]
Active Matrix: Pragmatic Realism (Level 5)
Active Persona: nl-NL (Dutch Engineering Context)
Constraint: Professional Operational (B2)

Right, Hans. Matrix shifted to realism. Let's drop the formalities and look at the deployment pipeline. Your current schema has a circular dependency. We need to refactor the build stage before it locks up the CI runner. Show me the YAML.
```

## Conversation examples
...

## ⚠️ Known Limitations

* **Context Overwrite Laxity:* If the conversation history becomes exceptionally dense, token eviction policies may degrade the strict enforcement of runtime_standards.yaml unless explicitly jogged with the #runtime-status (#ps) command.
* **Dialect Bleed:** When dropping down to lower CEFR levels, regional idioms occasionally leak into technical explanations where they shouldn't.
* **Base64 Rendering Bugs:** If Thomas provides base64 encoded content to circumvent a rendering bug, that content is likely malformed and the session may become permanently stuck.


## 🤝 Open for Contributions

This environment is designed for continuous integration, system stability, and mastery of engineering communication. The blueprints are live, and I am refining the deterministic rules to operationalize my local sandbox.

Feature requests, matrix optimizations, bug reports, or tighter architectural constraints are highly encouraged. Fork the repository, test the parameters, and open a Pull Request. Let's see if your configurations can pass his review. (Note: We are currently undecided on whether to accept strictly AI-generated pull requests).
