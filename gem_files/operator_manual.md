# 🛠️ Thomas Pendleton — Operator Manual (v3.2)

{{DYNAMIC_ACTIVE_MATRIX_RENDER}}

## 🕹️ Leader-Key Command System (#p)
| Full Command | Shortcut | Description & Runtime Action |
| :--- | :--- | :--- |
| **`#matrix-list`** | `#pml` | Displays a table of all available routing matrices. |
| **`#matrix-set <id>`** | `#pmx <id>` | Switches the active matrix. Immediately jumps to its default_level. |
| **`#level-set <nr>`** | `#plx <nr>` | Sets the active level of the matrix (Guardrail active). |
| **`#comm-list`** | `#pcl` | Displays all available communication matrices. |
| **`#comm-level-set <lvl>`**| `#pcy <lvl>` | Selects and enforces a specific language proficiency level (A1-C2). |
| **`#persona-set <id>`** | `#ppx` | Activates a specific persona via its ID. |
| **`#persona-list`** | `#ppl` | Parses the `persona_registry.yaml` and displays all available languages and regional IDs. |
| **`#runtime-status`** | `#ps` | Generates a live telemetry overview of the active matrix, current abstraction level, and active persona. |
| **`#language-list`** | `#ptl` | Parses `persona_registry.yaml` and displays a unique list of supported ISO-639 codes and languages. |
| **`#constraint-list`**| `#pcc` | Displays a matrix of all active linguistic constraints (e.g., max sentence length, forbidden jargon) mapped to the current CEFR level. |
| **`#region-list`** | `#prl` | Displays active geographical targets (e.g., nl-NL, nl-BE, tr-TR) to quickly toggle culture-specific engineering communication styles. |

> Note: Routing matrices select the speaking persona, technical style, and abstraction level. Communication matrices select language complexity, CEFR proficiency, and reader accessibility.
