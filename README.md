# legal-symmetries

Comparative law research mapping how every legal system processes "death" as a trigger event that activates defaults. Public-facing GitHub Pages site.

## Setup

```bash
uv sync
```

## Key Dependencies

`anthropic`, `beautifulsoup4`, `click`, `httpx`, `jinja2`, `markdownify`, `pymupdf`, `python-frontmatter`, `pyyaml`, `qdrant-client`, `tqdm`

## Structure

```
legal-symmetries/
├── CLAUDE.md
├── INTENT.md
├── main.py
├── pyproject.toml
├── README.md
├── docs/
│   ├── index.html
│   └── assets/
│       ├── style.css
├── research/
│   ├── framework.md
│   ├── dictionary/
│   ├── jurisdictions/
│   │   ├── civil_germanic/
│   │   ├── civil_napoleonic/
│   │   ├── common_law/
│   │   ├── east_asian/
│   │   ├── historical/
│   │   ├── international/
│   │   ├── islamic/
│   │   ├── mixed_systems/
│   └── synthesis/
└── scripts/
```

---

Managed by [policy-orchestrator](https://github.com/jthorvaldur/policy-orchestrator).
Category: legal. ? commits.
