# scriptux-tube-repo
Applying YouTube tutorials to be implemented in script form via terminal emulator 

## Scriptux-Tube v1.0

**Purpose:** A Termux-based utility script that converts the steps from YouTube tutorials into a repeatable, menu-driven terminal workflow on Android.

### Package contents (to be committed to the `Master` branch)
| File | Description |
|---|---|
| `Scriptux-Tube.sh` | Main executable script (interactive menu: init Termux → install tools → clone/create script → chmod +x → run) |
| `README.txt` | Detailed purpose, usage, collaborators, and license index |
| `LICENSE-Unreal-1.0.txt` | Custom owner license (Unreal Realty) — terms to be finalized by owner |
| `LICENSE-GPL-2.0.txt` | GNU General Public License v2.0 |
| `LICENSE-Apache-2.0.txt` | Apache License v2.0 |
| `LICENSE-CC-BY-3.0.txt` | Creative Commons Attribution 3.0 |

### Collaborators
- **Unreal Realty** — project owner / author
- **Google Gemini / Genspark** — AI collaborator (design, documentation, packaging)

### Workflow implemented (from the source document)
1. **Initialize Termux** — `termux-setup-storage`, `pkg update && pkg upgrade -y`
2. **Install tools** — `pkg install git nano curl wget -y`
3. **Get or create the script** — `git clone <repository-url>` + `cd <folder-name>`, or `nano script.sh` (Ctrl+O / Enter to save, Ctrl+X to exit)
4. **Set permissions & run** — `chmod +x name_of_script.sh`, `./name_of_script.sh`

### Remaining setup checklist
- [ ] Commit all 6 files to the 'main` branch
- [ ] Confirm repo name (`scriptux-tube-repo` vs requested `Scriptux-Tube-Repo` — rename in Settings if desired)
- [ ] Finalize custom Unreal License v1.0 terms
- [ ] Review multi-license compatibility (GPL-2.0 / Apache-2.0 / CC-BY-3.0)
- [ ] Tag release `v1.0`

*Posted by Genspark on behalf of the project owner.*