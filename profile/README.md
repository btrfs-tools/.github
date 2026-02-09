# btrfs-tools

Curated tools, scripts, and extensions for Btrfs-based Linux systems.

[English](#english) · [Deutsch](#deutsch)

---

## English

### Purpose

This organization collects **useful, popular, and practical** open-source components around **Btrfs**:
- original tools
- curated forks (kept in sync where feasible)
- installation helpers and system integration snippets
- reproducible “one command” bundles

Goal: make it easy to **find, install, and maintain** reliable Btrfs tooling for real systems.

### What you’ll find here

- **Layout & provisioning**  
  Subvolume layouts, bootstrap scripts, best-practice defaults.
- **Snapshots & rollback workflows**  
  Helpers for snapshot automation, rotation, and restore paths.
- **Maintenance & rescue**  
  Tools for troubleshooting, cleanup, and safe repair flows.
- **Integrations**  
  systemd units/timers, udev rules, desktop helpers where applicable.
- **Curated forks**  
  Upstream projects mirrored/forked when we add fixes, packaging, or OS-friendly defaults.

### Naming conventions

To keep things searchable:
- Repos often start with a **scope prefix** (e.g. `btrfs-`, `systemd-`, `udev-`, `cli-`)
- Desktop-specific helpers use their target as a prefix (e.g. `nautilus-...`)

### Quick start

1. Open the repo you need (start with the pinned repositories).
2. Read the **README** and check requirements.
3. Prefer packages/releases when available; otherwise follow the install steps.
4. If you’re unsure: open an issue with your distro + Btrfs layout + goal.

### Bundles (one-shot installs)

We also maintain “bundle” repositories that combine multiple useful components:
- single installer entrypoint
- modular selection (install only what you want)
- idempotent behavior where possible

### Contributing

Contributions are welcome:
- bug reports with reproducible steps
- PRs that improve safety, docs, or portability
- packaging and integration improvements

Please keep changes:
- **reversible** (uninstall/rollback path)
- **explicit** (no hidden behavior)
- **safe by default**

### Security

If you discover a security issue, please open a private report if possible (or contact maintainers via the org profile links).

### License

Each repository keeps its own license. See the license file in the respective repo.

---

## Deutsch

### Zweck

Diese Organisation sammelt **nützliche, populäre und praxistaugliche** Open-Source-Bausteine rund um **Btrfs**:
- eigene Tools
- kuratierte Forks (wenn möglich mit Upstream-Sync)
- Installationshilfen und System-Integration
- reproduzierbare „ein Befehl“-Bundles

Ziel: Btrfs-Werkzeuge für echte Systeme **leicht auffindbar, installierbar und wartbar** machen.

### Was du hier findest

- **Layout & Provisioning**  
  Subvolume-Layouts, Bootstrap-Skripte, bewährte Defaults.
- **Snapshots & Rollback-Workflows**  
  Helfer für Snapshot-Automatisierung, Rotation und Wiederherstellung.
- **Wartung & Rescue**  
  Tools für Troubleshooting, Cleanup und sichere Reparatur-Abläufe.
- **Integrationen**  
  systemd-Units/Timer, udev-Regeln, Desktop-Helfer (wo sinnvoll).
- **Kuratierte Forks**  
  Upstream-Projekte als Mirror/Fork, wenn wir Fixes, Packaging oder OS-freundliche Defaults pflegen.

### Namenskonventionen

Damit man schnell findet, was man sucht:
- Repos nutzen oft ein **Scope-Prefix** (z. B. `btrfs-`, `systemd-`, `udev-`, `cli-`)
- Desktop-Helfer starten mit dem Ziel (z. B. `nautilus-...`)

### Schnellstart

1. Öffne das Repo, das du brauchst (am besten bei den „Pinned“ starten).
2. Lies das **README** und prüfe Voraussetzungen.
3. Wenn verfügbar: Packages/Releases nutzen, sonst Installationsschritte befolgen.
4. Bei Unsicherheit: Issue mit Distro + Btrfs-Layout + Ziel erstellen.

### Bundles (Installation in einem Rutsch)

Es gibt außerdem „Bundle“-Repos, die mehrere nützliche Komponenten zusammenfassen:
- ein Installer-Einstiegspunkt
- modulare Auswahl (nur installieren, was du willst)
- möglichst idempotentes Verhalten

### Mitmachen

Beiträge sind willkommen:
- Bug-Reports mit reproduzierbaren Schritten
- PRs für mehr Sicherheit, bessere Doku, mehr Portabilität
- Packaging- und Integrations-Verbesserungen

Bitte Änderungen so gestalten, dass sie:
- **rückgängig** zu machen sind (Uninstall/Rollback)
- **transparent** sind (kein verstecktes Verhalten)
- **sicher** per Default bleiben

### Sicherheit

Wenn du eine Sicherheitslücke findest: bitte wenn möglich privat melden (oder über die Kontaktwege im Org-Profil).

### Lizenz

Jedes Repo hat seine eigene Lizenz – siehe jeweilige Lizenzdatei im Repo.
