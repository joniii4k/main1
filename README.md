# Globale Claude-Skills

Sammlung der Design-, Animations- und UI-Skills, die in allen Projekten genutzt werden.
Unabhängig von einzelnen Firmen oder Kundenprojekten.

## Inhalt

- `skills/`: 28 Skills, z. B. `design-taste-frontend`, `redesign-existing-projects`, `high-end-visual-design`,
  `emil-design-eng`, `animate`, `mobile-native`
- `licenses/`: Lizenzen und Quellen der Originalautoren (bitte bei Weitergabe beibehalten)
- `.claude-plugin/`: macht das Repository zu einem Claude-Code-Plugin

## Nutzen

**Als Plugin (empfohlen, gilt für alle Projekte):**
In Claude Code auf dem eigenen Rechner:

```
/plugin marketplace add joniii4k/main1
/plugin install jonas-design-skills@jonas-skills
```

**Für alle Projekte auf dem eigenen Rechner, ohne Plugin:**
Den Inhalt von `skills/` nach `~/.claude/skills/` kopieren.

**Für ein einzelnes Projekt (auch in Cloud-Sitzungen):**
Den Inhalt von `skills/` in den Ordner `.claude/skills/` des Projekts kopieren.

## Skills aktualisieren

Neue oder verbesserte Skills hier ablegen und committen. Beim Plugin danach in Claude Code
`/plugin marketplace update jonas-skills` ausführen.
