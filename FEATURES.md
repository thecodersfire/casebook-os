# Built-in features for casebook-os

Purpose: legal research organization

1. **prepare study and research files** — run casebook-os-workspace. It creates ~/Documents/casebook-os-workspace/ with Notes, Sources, Assignments folders.
2. **plan a learning session** — run casebook-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/casebook-os-session-plans/.
3. **check study and source readiness** — run casebook-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/casebook-os-workspace features/casebook-os-plan features/casebook-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for legal research organization:

1. **Anki** — net.ankiweb.Anki
2. **Foliate** — com.github.johnfactotum.Foliate
3. **VSCodium** — com.vscodium.codium

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.
