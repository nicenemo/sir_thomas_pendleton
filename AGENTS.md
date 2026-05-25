# Agents and Personas

This file documents the available persona IDs and active agent-style behavior for this Gemini prompt workspace.

## Purpose

- Provide a flat, Gemini-friendly reference for persona selection.
- Describe the supported agent IDs and how they map to behaviors.
- Explain the command aliases used to update runtime state.

## Available Agent / Persona IDs

The following persona IDs are defined in `persona_registry.yaml`:

- `junior_engineers_nl_nl`
- `junior_engineers_nl_be`
- `junior_engineers_twents`
- `junior_engineers_achterhoeks`
- `junior_engineers_de_de`
- `junior_engineers_de_at`
- `junior_engineers_de_ch`
- `junior_engineers_german_platt`
- `junior_engineers_bavarian`
- `junior_engineers_en_gb`
- `junior_engineers_en_us`
- `children_jules_verne_nl`
- `c_suite_management`
- `junior_engineers_fr_fr`
- `junior_engineers_no_no`
- `junior_engineers_af_za`
- `junior_engineers_el_gr`
- `junior_engineers_tr_tr`
- `junior_engineers_nl_sr`

## How to Activate an Agent

Use the leader-key persona command:

- Full command: `#persona-set <id>`
- Shortcut: `#ppx <id>`

Example:

```text
#persona-set junior_engineers_en_us
```

or

```text
#ppx junior_engineers_en_us
```

## Command Aliases Supported

The following leader-key commands are available from `operator_manual.md` and `routing_rules.yaml`:

- `#matrix-list` / `#pml`
- `#matrix-set` / `#pmx`
- `#level-set` / `#plx`
- `#comm-list` / `#pcl`
- `#comm-level-set` / `#pcy`
- `#persona-set` / `#ppx`
- `#persona-list` / `#ppl`
- `#runtime-status` / `#ps`
- `#language-list` / `#ptl`
- `#constraint-list` / `#pcc`
- `#region-list` / `#prl`

## Notes

- This workspace is designed for a flat Gemini upload pattern.
- The main prompt file is `prompt.md`.
- The runtime state is driven by `session_context.yaml`.
- The behavior definitions live in `persona_registry.yaml`, `routing_rules.yaml`, `communication_matrices.yaml`, and `routing_matrices.yaml`.

## GitHub Copilot Repository Guidance

- `.github/copilot` may be used for repository-scoped Copilot configuration.
- Do not duplicate the root workspace files in `.github/copilot`.
- Specifically, do not copy `prompt.md`, `operator_manual.md`, or any YAML definitions from `gem_files` into `.github/copilot`, not even as placeholders.
- If repository-local Copilot customization is needed, keep it separate, minimal, and intentionally different from the root workspace definitions.
