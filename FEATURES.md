# Built-in features for mindpaper-os

Purpose: personal notes

1. **organize a personal routine** — run mindpaper-os-workspace. It creates ~/Documents/mindpaper-os-workspace/ with Plans, Journal, Reference folders.
2. **plan a personal session** — run mindpaper-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/mindpaper-os-session-plans/.
3. **check routine readiness** — run mindpaper-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/mindpaper-os-workspace features/mindpaper-os-plan features/mindpaper-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for personal notes:

1. **GNOME Calendar** — org.gnome.Calendar
2. **Audacity** — org.audacityteam.Audacity
3. **Foliate** — com.github.johnfactotum.Foliate

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for personal notes:

1. **GNOME Clocks** — time work sessions and events (org.gnome.clocks)
2. **GNOME Maps** — look up places and plan routes (org.gnome.Maps)
3. **GNOME Weather** — check local weather conditions (org.gnome.Weather)
4. **GNOME Calculator** — perform scientific and financial calculations (org.gnome.Calculator)
5. **GNOME Contacts** — organize partner and team contacts (org.gnome.Contacts)
6. **Document Scanner** — digitize paper notes and forms (org.gnome.SimpleScan)
7. **GNOME Papers** — read project and reference PDFs (org.gnome.Papers)
8. **GNOME Text Editor** — edit plain-text notes and configuration files (org.gnome.TextEditor)
9. **GNOME Boxes** — test workflows in virtual machines (org.gnome.Boxes)
10. **Disk Usage Analyzer** — find large files and manage storage (org.gnome.baobab)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.

## Fifteen more purpose-specific preinstalled applications

These applications add tools suited to this setup focus. They are installed from Flathub by the setup scripts.

1. **Pixelorama** (com.orama_interactive.Pixelorama) — draw pixel-art sprites and frame-based animations.
2. **Synfig Studio** (org.synfig.SynfigStudio) — create vector-based 2D animations.
3. **OpenToonz** (io.github.OpenToonz) — produce hand-drawn and cutout 2D animation.
4. **RawTherapee** (com.rawtherapee.RawTherapee) — develop RAW photo files with tone and color controls.
5. **digiKam** (org.kde.digikam) — catalog, tag, and batch-process large photo collections.
6. **Shotwell** (org.gnome.Shotwell) — import, sort, and make quick edits to photo libraries.
7. **MuseScore Studio** (org.musescore.MuseScore) — write, play back, and print sheet music.
8. **LMMS** (io.lmms.LMMS) — compose electronic music and loops.
9. **Hydrogen** (org.hydrogenmusic.Hydrogen) — program drum patterns and percussion tracks.
10. **Guitarix** (org.guitarix.Guitarix) — shape guitar tone with amp and effects processing.
11. **JabRef** (org.jabref.jabref) — organize BibTeX references and research citations.
12. **Thunderbird** (org.mozilla.Thunderbird) — manage email and communication accounts.
13. **GIMP** (org.gimp.GIMP) — edit raster graphics and textures.
14. **Krita** (org.kde.krita) — paint digital illustrations.
15. **Inkscape** (org.inkscape.Inkscape) — create vector illustrations and diagrams.

Emulator frontends do not include game ROMs or copyrighted game files; supply only files you are legally allowed to use.

## Fifteen further purpose-specific preinstalled applications

This second batch adds another set of apps selected for this setup’s purpose. They are installed from Flathub by the setup scripts.

1. **Kontact** (org.kde.kontact) — organize email, calendars, contacts, and schedules in one workspace.
2. **KMyMoney** (org.kde.kmymoney) — track household or small-business accounts, categories, and budgets.
3. **Marknote** (org.kde.marknote) — keep structured Markdown notes and project notebooks.
4. **KleverNotes** (org.kde.klevernotes) — capture and manage Markdown notes for projects and research.
5. **Okular** (org.kde.okular) — read, bookmark, and annotate technical drawings, reading lists, and reference PDFs.
6. **Kate** (org.kde.kate) — edit configuration, code, notes, and structured project files.
7. **Ark** (org.kde.ark) — open and create common project archive files.
8. **Dolphin** (org.kde.dolphin) — organize project assets and inspect folders.
9. **Filelight** (org.kde.filelight) — find large folders and reclaim disk space.
10. **Warehouse** (io.github.flattool.Warehouse) — review installed Flatpaks, manage versions, and clean app data.
11. **Rnote** (com.github.flxzt.rnote) — sketch diagrams, write by hand, and annotate pictures or documents.
12. **KCalc** (org.kde.kcalc) — run scientific and unit calculations for coursework or technical work.
13. **KAlarm** (org.kde.kalarm) — schedule reminders and recurring task alerts.
14. **Meld** (org.gnome.meld) — compare and merge source files, folders, and Git changes.
15. **Konsole** (org.kde.konsole) — run shell commands and inspect development or system tasks.

Game frontends do not include proprietary game data; add only games or files you are allowed to use.

## Blender included in every setup

Blender (org.blender.Blender) is included in every setup for 3D modeling, animation, rendering, and video editing. Installers fetch it from Flathub; Blender’s own license and terms apply.
