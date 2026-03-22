<!-- README.md - Skillsammlung -->
<!-- Brand: alexle135.de (Dark + Blue + Pragmatic) -->

<div align="center">

<!-- Animated Gradient Border Effect -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=155DFC&height=120&section=header&text=Skillsammlung&fontSize=42&fontColor=F3F4F6&animation=fadeIn&fontAlignY=35" width="100%"/>

<!-- Subtitle -->
<p align="center">
  <span style="color: #155DFC; font-weight: 600;">⸻</span>
  <span style="color: #94A3B8;">Sammlung professioneller Agent-Skills für Claude Code</span>
  <span style="color: #155DFC; font-weight: 600;">⸻</span>
</p>

<!-- Badges -->
<p align="center">
  <img src="https://img.shields.io/badge/Skills-7-155DFC?style=flat-square&logo=claude&logoColor=white&labelColor=111827&color=155DFC" alt="7 Skills"/>
  <img src="https://img.shields.io/badge/Framework-OpenClaw-155DFC?style=flat-square&logo=docker&logoColor=white&labelColor=111827" alt="OpenClaw"/>
  <img src="https://img.shields.io/badge/License-MIT-155DFC?style=flat-square&labelColor=111827" alt="MIT License"/>
  <img src="https://img.shields.io/badge/Maintainer-arn0ld87-155DFC?style=flat-square&labelColor=111827" alt="Maintainer"/>
</p>

</div>

---

## 🎯 Übersicht

Dieses Repository enthält eine kuratierte Sammlung von **7 professionellen Agent-Skills** für Claude Code. Jedes Skill-Paket ist für spezifische Anwendungsfälle optimiert — von DevOps-Automation über Bewerbungsunterstützung bis hin zu Frontend-Design auf Agentur-Niveau.

> **Praxisnah. Reproduzierbar. Direkt einsetzbar.**

---

## 📦 Enthaltene Skills

<!-- Skill Cards Grid -->
<table width="100%">
<tr>
<td width="50%" valign="top">

### 🔧 `openclaw-expert`
**OpenClaw Framework Spezialist**

Self-hosted AI Agent Framework Expertise. Gateway-Konfiguration, Channel-Setup, Memory-Tuning, Docker-Deployment und Troubleshooting.

```yaml
Anwendung: openclaw.json, gateway, channels, models
Use Case: Installation, Konfiguration, Security Hardening
Version: 1.1.0
```

</td>
<td width="50%" valign="top">

### 🎨 `frontend-design-agency`
**Frontend Design auf Agentur-Niveau**

Entwickelt Web-App-Frontends mit klarer gestalterischer These. Verhindert generische KI-Optik durch gezielte Design-Entscheidungen.

```yaml
Anwendung: Next.js, React, TypeScript, Tailwind
Use Case: Dashboards, Landingpages, App-Shells
Version: 1.0.0
```

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🚀 `dify-orchestrator`
**Dify Workflow Orchestration**

Komplexe Dify-Workflows analysieren und in Teilaufgaben zerlegen. Expertise für Node-Konfiguration, Fehlerbehebung und DSL-Optimierung.

```yaml
Anwendung: Dify Workflows, LLM-Chains, Code-Nodes
Use Case: Workflow-Design, Debugging, Refactoring
Version: 1.3.0
```

</td>
<td width="50%" valign="top">

### ⚙️ `dify-workflow`
**Dify Workflow Builder**

Erstellen und Bearbeiten von Dify Workflow DSL-Dateien. Node-Konfiguration, Conditional Logic und Fehlerbehebung für Self-Hosted Instanzen.

```yaml
Anwendung: Dify DSL, Workflow-Design, Node-Config
Use Case: Workflow-Erstellung, Migration, Debugging
Version: 1.3.0
```

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📝 `bewerbung-fisi`
**Bewerbung Fachinformatiker**

Hochqualitative deutsche Bewerbungsunterlagen für Fachinformatiker (Systemintegration). Anschreiben, Lebensläufe und E-Mail-Templates.

```yaml
Anwendung: Bewerbungsunterlagen, Ausbildungsplatz
Use Case: FISI, Systemintegration, IHK
Version: 1.0.0
```

</td>
<td width="50%" valign="top">

### 🎓 `fisi`
**Fachinformatiker Lern-Assistant**

Lehrerinnen-Assistenz für Deutsch und Ev. Religion (Kl. 5-10, Gymnasium). Didaktisch aufbereitete Inhalte mit Quellenangaben.

```yaml
Anwendung: Unterrichtsvorbereitung, Prüfungsvorbereitung
Use Case: Gymnasium, Lehrkräfte, Schüler
Version: 1.1.0
```

</td>
</tr>
<tr>
<td width="50%" valign="top" colspan="2">

### ⚖️ `arbeitsrecht-buergergeld-umschulung`
**Arbeitsrecht & Umschulung**

Beratung zu Arbeitsrecht, Bürgergeld und Umschulung für Fachinformatiker. Rechte, Pflichten und strategische Optionen.

```yaml
Anwendung: Arbeitsrecht, Sozialrecht, Bildung
Use Case: Umschulung, Jobwechsel, Beratung
Version: 1.0.0
```

</td>
</tr>
</table>

---

## 🚀 Schnellstart

### Installation

```bash
# Repository klonen
git clone https://github.com/arn0ld87/Skillsammlung.git

# In das Skill-Verzeichnis wechseln
cd Skillsammlung

# Einzelnes Skill in Claude Code laden
# (Verzeichnis nach ~/.claude/skills/ kopieren oder direkt referenzieren)
```

### Nutzung in Claude Code

```bash
# Skill aktivieren
claude config skills add ./openclaw-expert-1.1.0

# Oder direkt im Prompt verwenden
"Nutze das frontend-design-agency Skill für diese Aufgabe..."
```

---

## 🏗️ Skill-Struktur

Jedes Skill-Paket folgt einer konsistenten Struktur:

```
skill-name-1.0.0/
├── SKILL.md              # Hauptdokumentation
├── skill.json           # Skill-Metadaten
├── _meta.json           # Interne Metadaten
└── references/          # Referenzmaterialien
    ├── research-workflow.md
    ├── visual-direction-canvas.md
    └── ...
```

---

## 🎨 Design-Prinzipien

Diese Skillsammlung folgt den Prinzipien von **alexle135.de**:

| Prinzip | Beschreibung |
|---------|--------------|
| **Praxisnah** | Reproduzierbare Setups statt One-Off Hacks |
| **Direkt** | Klare Handlungsanweisungen ohne Marketing-Fluff |
| **Technisch** | Fokus auf Linux, Docker, DevOps, KI-Automation |
| **Wartbar** | Dokumentiert, versioniert, erweiterbar |

---

## 📚 Weitere Ressourcen

- [OpenClaw Documentation](https://openclaw.io)
- [Dify Docs](https://docs.dify.ai)
- [Claude Code Skills](https://claude.ai/docs)

---

## 🤝 Mitwirken

Beiträge sind willkommen! Für neue Skills oder Verbesserungen:

1. Fork erstellen
2. Branch erstellen (`git checkout -b feature/neues-skill`)
3. Änderungen committen
4. Pull Request öffnen

---

## 📄 Lizenz

Dieses Projekt ist unter der **MIT License** lizenziert. Siehe [LICENSE](LICENSE) für Details.

---

<div align="center">

<!-- Footer -->
<p align="center" style="color: #64748B; font-size: 14px;">
  <strong>Skillsammlung</strong> — Entwickelt mit
  <span style="color: #155DFC;">◆</span>
  von <a href="https://github.com/arn0ld87" style="color: #155DFC; text-decoration: none;">arn0ld87</a>
</p>

<p align="center" style="color: #475569; font-size: 12px; margin-top: 8px;">
  Systemintegration & DevOps • CalVer Versioning • Praxisnah & Reproduzierbar
</p>

</div>

<!-- Bottom Wave -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=155DFC&height=60&section=footer" width="100%"/>
