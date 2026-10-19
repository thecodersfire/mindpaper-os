# Built-in features for mindpaper-os

Purpose: personal notes

1. **organize a personal routine** — run mindpaper-os-workspace. It creates ~/Documents/mindpaper-os-workspace/ with Plans, Journal, Reference folders.
2. **plan a personal session** — run mindpaper-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/mindpaper-os-session-plans/.
3. **check routine readiness** — run mindpaper-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/mindpaper-os-workspace features/mindpaper-os-plan features/mindpaper-os-check "$HOME/.local/bin/"
