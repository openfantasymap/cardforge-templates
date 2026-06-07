# CardForge templates

Shared, global starter templates for [CardForge](https://www.fantasymaps.org/cardsapi.designer/).

`index.json` lists templates the app offers under **New Project → Start from**.
Each entry is a full layout:

```json
{
  "version": 1,
  "templates": [
    { "id": "magic", "label": "Magic-style", "description": "…", "template": { /* CardTemplate */ }, "rows": [ /* sample rows */ ] }
  ]
}
```

These are generic, homebrew-friendly **layouts** (element placement + bound
`{{columns}}`) — no logos, official art, or trademarked assets. Add or edit a
template by committing to `index.json` (PRs welcome). Users can also save their
own templates privately to their `cardforge-index` repo from within the app.
