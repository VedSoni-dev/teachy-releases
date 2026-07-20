# Teachy — Downloads & Courses

**Teachy** is a free macOS teaching companion: a 1:1 tutor in your menu bar that sees your screen, points at real UI, and coaches you until something actually ships.

**Website:** [vedsoni-dev.github.io/teachy](https://vedsoni-dev.github.io/teachy/)

## Download

**→ [Download Teachy.dmg](https://github.com/VedSoni-dev/teachy-releases/releases/latest/download/Teachy.dmg)**

### First open

1. Drag **Teachy** to Applications
2. **Right-click** → **Open** → **Open** (community build — macOS asks once)
3. Teachy walks you through permissions one at a time
4. Paste your free [OpenRouter](https://openrouter.ai) API key when asked — that's it. Bring your own key; Teachy is free.

Installed apps update automatically via Sparkle (`appcast.xml` in this repo).

## Courses

Free courses live in [`courses/`](courses/) and are indexed by [`registry.json`](registry.json). Browse them on the [Teachy Academy site](https://vedsoni-dev.github.io/teachy/) and install with one click — or paste a course JSON URL into Teachy's Learn tab.

Want to author a course? Course JSON is plain and human-readable — open any file in `courses/` to see the shape, then host yours anywhere and share the URL.

## What's in this repo

| File | Purpose |
|------|---------|
| `Releases` (sidebar) | Signed DMG downloads |
| `appcast.xml` | Sparkle auto-update feed |
| `registry.json` | Course catalog the app + website read |
| `courses/*.json` | The free course library |

Teachy's application code is proprietary; the app is free to use. Courses in this repo are free to use and share.
