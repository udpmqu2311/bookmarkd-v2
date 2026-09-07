# bookmarkd-v2

Learning project: clean Express API structure

Started as a weekend hack, grew on me.

## Getting started

```bash
npm install
npm run dev
```

## Highlights

- In-memory store with optional JSON persistence
- Request validation helpers, no framework magic
- Ready for Render/Fly deploy with PORT env
- REST endpoints: list / create / delete / search
- Morgan logging and centralized error handler

## How to use

```bash
curl -X POST localhost:3000/api/bookmarks \
  -H 'content-type: application/json' \
  -d '{"url": "https://example.com", "tags": ["reading"]}'
```

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   ├── dependabot.yml
│   └── pull_request_template.md
├── docs/
│   ├── faq.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── src/
│   ├── config.js
│   ├── index.js
│   └── store.js
├── .editorconfig
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── SECURITY.md
└── package.json
```

## Development

```bash
npm install
npm test
```
