# 📑 Installation Runbook: Setting Up Sir Thomas Pendleton

This runbook outlines the exact procedure required to initialize the Sir Thomas Pendleton training runtime inside your Google Gemini environment.

---

## 🎛️ Supported Environments

Sir Thomas is optimized specifically for the **Google Gemini "Gems"** customization architecture.

* **Supported Interfaces:** The runtime is fully operational via the web interface at gemini.google.com and within the Gemini Mobile App.
* **Account Tiers:** Provisioning and hosting custom Gems requires an active Gemini Advanced subscription or a corporate Google Workspace Business/Enterprise account.
* **Free Tier Limitation:** The free tier tier does not natively expose the **Custom Gems Manager** dashboard required to pin and process local file assets.
* **Official Reference:** For account capability verification, consult the official Google support documentation for creating and using Gems.

---

## 🚀 Step-by-Step Setup Protocol

### Step 1: Initialize the New Gem Container
1. Navigate to [gemini.google.com](https://gemini.google.com) using a desktop browser.
2. In the left-hand navigation sidebar, select **Gems** and click **New Gem**.
3. Set the Gem name exactly to: `Sir Thomas Pendleton`.
4. Set the description field to: `Software architect and communication trainer, press #help for help`.

### Step 2: Configure Core Instructions
1. Copy the foundational role-play system block from your root `prompt.md` file.
2. Paste the text directly into the **Instructions** text box inside the Gem configuration workspace.
3. Ensure the core description explicitly anchors the help system handlers to allow for immediate runtime auditing:
   > *"You are Sir Thomas Pendleton. Respond dynamically to your uploaded matrix files. Prioritize commands like `#help` or `#help_thomas` to display manuals instantly."*

### Step 3: Provision Configuration and Control Assets
1. Locate the attachment/upload icon within your Gem configuration workspace.
2. Upload the control manifests from your local workspace repository. You must include all structural engine files located in the `gem_files/` directory, including the operational manuals.

### Step 4: Inject Interlocutor Profile Context
1. Open your local copy of `session_context.yaml` before uploading it to the workspace.
2. Modify the `primary_interlocutor` block to accurately map your engineering parameters so the engine knows its target profile:
   ```yaml
   primary_interlocutor:
     name: "Your Name"
     role: "Your Title (e.g., Senior Software Engineer)"
     experience: "Years of Experience (e.g., +26 years)"
   ```
   
### Step 5: Enforce Target Project Constraints
1. Open your local copy of `technical_constraints.yaml` to specify your execution framework and tech stack.
2. Hard-code your target parameters to lock down architectural and compiler compliance:

   ```yaml
   project_context:
     language: "C# 14"
     runtime_version: ".NET 9"
     architecture_style: "Clean Architecture"
   ```
### ⚡ Post-Deployment Runtime Verification
Once the workspace files are pinned and the Gem is saved, initialize the runtime by executing a system status check. Paste the following macro command into the chat window:

```text
#runtime-status
```

*Note:* 

You may also use the abbreviated terminal shortcut #ps. The engine must return a comprehensive telemetry read-out detailing your active configuration files, regional persona settings, and runtime standard guardrails. If the engine fails to read the state or reverts to generic LLM behavior, verify that session_context.yaml was uploaded properly.
