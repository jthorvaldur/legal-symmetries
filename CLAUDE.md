# CLAUDE.md — Legal Symmetries

## Project Overview

Comparative law research mapping how every legal system processes "death" as a trigger event that activates defaults. Public-facing GitHub Pages site.

## Key Constraints

1. **No PII** — No real names, case numbers, specific dollar amounts, attorney names, or identifiable facts. Structural parallels only.
2. **Cite sources** — Every jurisdiction must reference actual statutes, codes, or case law. No hallucinated legal citations.
3. **Verify via web search** — Before writing a jurisdiction's analysis, search for the current statute text. Laws change.
4. **Anonymized parallels** — Use patterns like "a parent signs an allocation judgment" not specific cases.

## File Conventions

- Research files in `research/` use the jurisdiction template (see research/framework.md)
- HTML pages in `docs/` are generated or hand-authored
- CSS in `docs/assets/style.css` is the shared design system

## Directory Layout

```
research/
  framework.md                    # Core theory
  jurisdictions/{family}/{jurisdiction}.md
  dictionary/{term_group}.md
  synthesis/{topic}.md
docs/
  index.html                      # Hub page
  {family}.html                   # Sub-pages per legal family
  dictionary.html                 # Term comparison
  exhibit.html                    # Court-ready summary
  assets/style.css
scripts/
  build_html.py
```

## GitHub Pages

- Served from `docs/` on main branch
- Public, unencrypted
- No build step required for static HTML
