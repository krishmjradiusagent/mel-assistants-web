# Mel assistants web

Design snapshot of the Mel copilot web flows (Radius). 8 flows, 180 screens, 1440 × 900, light theme.

**Live site:** https://krishmjradiusagent.github.io/mel-assistants-web/

## Flows

| Flow | Screens |
|---|---|
| Onboarding | 11 |
| Chat intimation | 8 |
| MEL chat | 6 |
| Mel voice | 28 |
| CRM skill | 45 |
| Campaign skill | 17 |
| Client experience skill | 17 |
| Marketing skill | 48 |

## Folders

- `index.html`, `p/`, `a/`: the site. Home, flow pages, screen viewer.
- `boards/`: live screens and the runtime they need (Radius UI, Mel brand layer).
- `png/`: one PNG per screen.
- `html/`: one standalone HTML per screen. Opens on its own, offline except web fonts.
- `zip/`: one ZIP per flow, holding its HTML and PNG files.
- `source/`: raw design canvas files (`.dc.html`, `canvas.json`, CSS, tokens, image assets). `/_blob/<id>` references map to `source/assets/<id>.*`.

Links between screens are removed in the standalone HTML. Interactions inside a screen work.
