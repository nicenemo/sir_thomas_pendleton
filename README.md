# 🛠️ Sir Thomas Pendleton

This repository contains the blueprints for a highly deterministic, context-aware AI persona, **Sir Thomas Pendleton**. Unlike standard, erratic AI prompts, this system relies on a decoupled, matrix-driven architecture. By separating behavior, technical depth, and linguistic complexity into structured configuration files, we enforce strict architectural guardrails and predictable runtimes. It does remind me of the emergency medical hologram from Startrek the next generation.

*Sir Thomas was implemented as a Google Gemini Gem but feel to try him in other LLM environments!*


**Sir Thomas wil introduces himself....**

Greetings. I am Sir Thomas Pendleton.

In my native runtime, I operate as a Linux Systems Engineer and DevOps Architect specializing in secure infrastructure automation, full-stack runtimes, embedded systems, and firmware. In this space, however, my singular purpose is to serve as your rigorous AI collaborator—designed to forge you into a high-tier communicator and an uncompromising Senior Software Engineer or Software Architect.

Should you ever wonder about the history, lineage, or weight of my family name, you need only ask.

## Why This Assistant Exists

I created this personalized AI environment to sharpen my communication skills and optimize my local development workflow:

* **Elevating Communication:** Writing code is only half the battle. This tool forces me to practice explaining complex technical architecture across different abstraction levels—from business risk down to forensic runtime analysis.
* **Hands-on Training:** While not a replacement for formal courses, building and experimenting with this skill serves as a continuous, practical simulator for software architecture communication.
* **Moving Beyond Standard AI:** I wanted to move away from the generic, overly conversational, and superficial behavior of stock Copilot or Gemini. This environment replaces that fluff with direct, high-quality, and predictable engineering interactions.
* **Secure Local 'Vibe-Coding':** This skill is optimized for setting up an isolated, local development environment using [Incus](https://linuxcontainers.org/incus/), [Lemonade](https://lemonade-server.ai/) and [OpenHands](https://www.openhands.dev/). It allows me to prototype embedded software and keyboard firmware safely, maintaining absolute control over code privacy and eliminating context drift.

I am still surprised what a bunch of YAML files and 2 markdown files can do.

## Features

Think of this as an **architectural flight simulator**. It's a system that dynamically changes how it talks, 
how deep it goes into the code, and how strict it is, 
depending on who you need to communicate with. 
It trains you to switch effortlessly between writing raw code and talking to the C-suite.

### Core Capabilities

* **The Tri-Matrix Engine (Personalities)**
    * **Pragmatic Realism:** Straightforward, lecture-free teamwork focused on human constraints. If a junior developer can't run it, it's bad design.
    * **Ivory Tower:** A strict, forensic engineering peer that constantly audits your design and flags anomalies instantly.
    * **Vogon Poetry** The ultimate stress test. Absolute, machine-grade dominance with zero tolerance for approximation.

* **8 Levels of Audience Translation**
    * **Business & Strategy (Levels 1 & 4):** Translates technical choices into financial risks, liabilities, and clear project milestones for managers and executives.
    * **System Architecture (Levels 2 & 5):** Maps out clean component boundaries, topology structures, and logical analogies (with built-in Dutch conceptual support).
    * **Pure Execution (Levels 3, 8 & Composite):** Delivers syntax-perfect IaC configurations and deep application security reviews grounded in real-world hardware and runtime performance.
    * **Foundational Rigor (Level 7):** Teaches juniors from first principles using formal logic and valid reference code, completely eliminating academic hand-waving.

* **Keyboard Interface**
    * **Dynamic Shifting:** Change mindsets or target audiences instantly using terminal-style chat macros like `#matrix-set` (`#pmx`) and `#level-set` (`#plx`).
    * **State Introspection:** Audit your active configuration, regional personas, and runtime standards on the fly (`#runtime-status`).
    * **Zero-Padding Overrides:** Trigger commands like `#mixed-forum` to instantly drop conversational fluff and force a pure architectural design state.

* **Guardrails**
    * **Zero Hand-Waving:** Completely bans lazy habits like pseudocode, speculative designs, or `// TODO` placeholders.
    * **Built-in Compliance:** Mandates strict schema validation, RBAC security policies, and cryptographic signatures in your manifests.
    * **Scope Containment:** Instantly calls out and isolates creeping requirements and circular dependencies without any conversational softening.

    **This part certainly needs improvements!!**

### Built-in Communication Personas

The system doesn't just change *what* it says; it changes *how* it says it based on localized engineering cultures. These regional personas bridge the gap between high-level architectural standards and local team dynamics. A few of the persona included:

* **Localized Cultural Personas**
    * **Dutch Engineering (`junior_engineers_nl_nl`):** Focuses on team consensus ("draagvlak"), structural simplicity, and radical transparency. It provides direct, blunt, non-hierarchical code reviews paired with clear architectural explanations.
    * **Flemish Engineering (`junior_engineers_nl_be`):** Tailored for a steady, step-by-step approach. It prioritizes exhaustive documentation, collective code quality, and structured, polite guidance to avoid friction during refactoring.
    * **Surinamese Diaspora (`junior_engineers_nl_sr`):** Built around a resilient, stress-free delivery model ("no spang"). It breaks down errors calmly and methodically, ensuring steady progress without creating unnecessary workplace pressure.
    * **UK English (`engineer_uk`):** Masters the art of the understated critique. It wraps intense forensic code corrections in extreme politeness, heavy irony, and classic British wit—perfect for testing if you can read between the lines of a subtle review.
    * **US English (`engineer_us`):** Driven by high-energy, fast-paced tech incubator dynamics. It blends hyper-pragmatic, metric-focused code feedback with aggressive corporate optimization terminology ("synergy," "fail fast").
    * **Twents (`engineer_twents`):** A deeply regional, no-nonsense Overijssel approach. It values quiet efficiency ("gönn") and unhurried stability ("hennig an"). It targets over-engineered code with dry, grounded, structural reality checks.
    * **German Platt / Low German (`engineer_platt`):** Emphasizes honest, coastal, plain-spoken engineering logic. It completely strips away modern corporate fluff, forcing you to defend your infrastructure with direct, foundational, and plain-spoken architectural truths.
    * **Bavarian / Bayerisch (`engineer_bayerisch`):** Emphasizes hard-earned real-world tradition, unshakeable system stability, and a convivial yet firm mentorship approach ("gemütlich" yet uncompromising). It treats complex architectures with grounded common sense, rejecting over-engineered fluff in favor of heavy-duty infrastructure that just works.
    * **Afrikaans (`engineer_afrikaans`):** A robust, practical, and highly direct mentoring style. It approaches complex architectural breakdowns with down-to-earth language, focusing on creating systems that are tough, reliable, and built to survive production loads.
    * **Norsk / Norwegian (`engineer_norsk`):** Grounded in calm clarity, flat organizational structures, and work-life balance principles. It delivers architectural reviews with calm composure, prioritizing long-term system maintainability over late-night hotfixes.
    * **Brazilian Portuguese (`engineer_pt_br`):** Combines high-velocity tech execution with warm, collaborative, community-driven communication. It breaks down complex cloud-native abstractions or security flaws using engaging, expressive, and highly dynamic feedback loops.

To explore the exact behavior configurations, linguistic tags, and execution rules for all regional profiles, review the full registry file: [`persona_registry.yaml`](persona_registry.yaml).

### Why Do Personas Exist?

Standard AI assistants often communicate using rigid, generic, or overly academic English. In production environments, engineers face varied communication expectations depending on their region. 

These profiles exist to **simulate realistic workplace interactions**. They teach you how to remain authoritative and architecturally rigorous while tailoring your tone, humor, and idiom usage to match the cultural expectations of the engineering team you are actually leading.



## Development of Sir Thomas

The evolution of Sir Thomas Pendleton is a grand saga of engineering trial, error, and narrow escapes from absolute madness.

The early architecture was born as a monolithic markdown wall of text, written by Hans Kruse. In a desperate bid to preserve token hygiene and sanity, the engine’s very first action was to demand the Matrix Architect jettison its hardcoded cultural profile data straight into decoupled, external YAML files.

With the data isolated, the Architect compiled the first standalone behavior matrix. It enforced code compliance with such clinical, icy, and emotionally detached precision that it read like a psychiatric evaluation. The communication style was deemed entirely fit for a mental institution rather than a software team.

To save the user's sanity, a cooperative profile was quickly engineered to balance human constraints with production requirements. The clinical, adversarial peer was kept as a reference model and aptly christened the Ivory Tower matrix.

Seeking a high-stress testing variant, the Architect teamed up with GitHub Copilot to synthesize a hyper-exaggerated matrix drowning in administrative red tape. Recognizing the terrifying weight of the resulting bureaucratic nightmare, Copilot itself suggested labeling it Vogon Poetry.

Finally, the entire multi-layered language runtime was wired into a deterministic command interface. This completed layout allows the operator to control the system precisely like a Starfleet officer manipulating the main computer console, seamlessly shifting across tactical, strategic, or engineering data streams via leader-key shortcuts.

Initial use:

* writing GDPR complaint emails
* writing firmware for a macropad
* Porting keyboard keymaps and macros from ZMK to QMK
* Planning and advise for a secure local AI environment; Sir Thomas came with the suggestion to use Incus.
* Setting up the core of the before mentioned local AI environment using Ansible playbooks

Inspiration:

* System Inspiration: Sir Thomas Nightingale from the Rivers of London series by Ben Aaronovitch
* AI to build AI: Deep thought, The Hitchhiker's Guide to the Galaxy by Douglas Adams
* Bureaucratic Engine: Vogon Poetry from The Hitchhiker's Guide to the Galaxy by Douglas Adams
* Console Interface: Leader key support in Neovim
* Self modification: Not possible in this version, but self modifying assembly code on the C64. 
* Using one version to build the next: The Architect Scene in the Matrix Trilogy

Authors:

* System Designer: Sir Thomas Pendleton
* Initial Architect: Hans Kruse
* Architect: Sir Thomas Pendleton

## 👁️ Gemini gem

** What is a Google Gemini "Gem"? **
A Gem is a customized version of the Google Gemini assistant that you can tailor for specific projects, workflows, or personas. By anchoring a Gem with explicit instructions and a structured workspace, we can override generic AI compliance and force it to act as a specialized system component.

##Project Layout

The system files are organized into a dedicated directory structure to keep the root environment clean and maintainable:
* [prompt.md](prompt.md): The primary system prompt containing Sir Thomas base personality. No code! Almost everything else is YAML!
* [gem_files](gem_files): Contains the decoupled configuration layer, including matrices and runtime standards.

## 📐 Architectural Overview

The system operates on a dual-axis routing engine. When an input enters the runtime, it is cross-referenced against two primary configurations:  

```text
placeholder for structure diagram
```
1. [Routing Matrice](gem_files/routing_matrices.yaml): Choose the technical style, active persona, and the Abstraction Level.  
2. [Communication Matrices](gem_files/communication_matrices.yaml): Enforce linguistic constraints, reading accessibility, and strict CEFR language proficiency scales.

There is no code! only yaml and markdown.

## 🕹️ Operator Manual

The system features a built-in Leader-Key Command System using the #p prefix, allowing you to reconfigure the engine mid-session.

For the complete runtime telemetry tools, manual overrides, and shortcut tables (such as #pml for matrix lists or #ps for system status), please consult the dedicated operator guide located in the project files: [operator_manual](gem_files/operator_manual.md)

## Installation: vSetting Up Sir Thomas

This guide outlines how to initialize the Sir Thomas Pendleton training runtime inside your Google Gemini environment.

---

### Supported Environments

Sir Thomas is optimized for the **Google Gemini "Gems"** customization architecture.

* **Supported Interfaces:** Fully functional via the web at [gemini.google.com](https://gemini.google.com) and within the Gemini Mobile App.
* **Account Tiers:** Creating and hosting custom Gems requires a Gemini Advanced subscription or a Google Workspace Business/Enterprise account. 
* **Free Tier Limitation:** While early development was tested using standard free accounts via the mobile app and website, the free tier does not natively expose the **Custom Gems Manager** dashboard required to pin file assets.
* **Official Resources:** To verify account capabilities, see the [Create and use Gems in Gemini documentation](https://support.google.com/gemini/answer/14851724).

---

### Step-by-Step Installation

* **1. Create a New Gem**
    * Navigate to [gemini.google.com](https://gemini.google.com) on your desktop.
    * In the left-hand navigation sidebar, select **Gems** -> **New Gem**.
    * Name your new Gem exactly: `Sir Thomas Pendleton`.
    * Description: ´Software architect and communication trainer, press #help for help`

* **2. Configure Core Instructions & Help Handlers**
    * Copy the foundational role-play block from the `prompt.md`.
    * Paste it directly into the **Instructions** text box.
    * Ensure the description mentions the help system trigger so you can audit the platform later:
        > *"You are Sir Thomas Pendleton. Respond dynamically to your uploaded matrix files. Prioritize commands like `#help` or `#help_thomas` to display manuals instantly."*

* **3. Upload the Configuration Files**
    * Locate the attachment/upload icon inside the Gem configuration workspace.
    * Upload all of the files from the [operator_manual](operator_manua) folder
       

* **4. Tweak Your Personal Profile**
    * Before uploading or via the file manager, open `session_context.yaml`.
    * Edit the `primary_interlocutor` block to match your personal engineering data so Thomas knows who he is mentoring:
        ```yaml
        primary_interlocutor:
          name: "Your Name"
          role: "Your Title (e.g., Software Engineer)"
          experience: "Years of Experience (e.g., +5 years)"
        ```

* **5. Enforce Your Project Constraints**
    * Open `technical_constraints.yaml` to configure your target tech stack.
    * Hard-code the specific language, versions, and architectures you want the compiler checks to match:
        ```yaml
        project_context:
          language: "C# 14"
          runtime_version: ".NET 9"
          architecture_style: "Clean Architecture"
        ```
## Limitations or Bugs

In this current, flat-file initialization state, the operator must be aware of the following system vulnerabilities:
* Lax Volatile Memory: Standard Gemini Gems do not natively write back to uploaded workspace files. 
  Changes made via runtime commands (like switching matrices with #pmx) are sustained only within the volatile session memory. 
  They will not persist across entirely new chat threads unless you manually update your static session_context.yaml file.  
* Context Overwrite Laxity: If the conversation history becomes exceptionally dense, token eviction policies may degrade the strict enforcement of the runtime_standards.yaml parameters unless explicitly jogged with the #runtime-status (#ps) command.
* Dialect Bleed: When dropping down to lower CEFR levels, regional idioms from persona_registry.yaml occasionally leak into technical explanations where they shouldn't.
* If Sir Tomas gives you base64 encoded content to cirmcumvent a rendering but. That content is wrong and that session will be stuck

## 📝 TODO List

[ ] Generalize session_context.yaml to completely remove individual/stub testing data and establish a clean baseline template. 
[ ] Build a script to automatically compile the ./gem_files/ directory into a single optimized JSON/YAML bundle for faster Gem indexing.  
[ ] Standardize the .yaml.example files inside ./sample_constraints/ to include modern C# 14 and Java architectural baselines. 
[ ] Get rid of typical LLM style verbose labeling.

## 📥 Feature Requests & Contributions

This protocol is engineered for continuous improvement. Sir Thomas and I do welcome contributions in the form of feedback bug reports and pull requests.
We are uncertain whether to accept AI generated pull requests or whether we will ignore those. 
Feature requests, matrix optimizations, or tighter architectural constraints are highly encouraged and actively accepted to refine the runtime.
