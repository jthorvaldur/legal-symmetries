# Legal Symmetries

**How Legal Systems Process Death, Default, and the Erasure of Personhood**

> The person who understands the defaults controls the outcome.
> The person who doesn't understand the defaults *is* the outcome.

Every legal system is a complete function: for every input state (alive/dead, married/single, parent/non-parent, solvent/insolvent), there is a defined output. There are no gaps. The system always produces a result.

"Dead" is not an end state. It is a **trigger event** that activates defaults. This project maps those defaults — and the floor mechanisms that prevent total erasure — across every major legal tradition.

**Live site:** [jthorvaldur.github.io/legal-symmetries](https://jthorvaldur.github.io/legal-symmetries/)

## Progress

| Legal Family | Jurisdictions | Status |
|---|---|---|
| **Common Law** | United States | 1 / 7 |
| **Civil Law — Germanic** | Germany | 1 / 3 |
| **Civil Law — Napoleonic** | France | 1 / 5 |
| **Nordic** | Sweden | 1 / 5 |
| **Islamic Law** | — | 0 / 6 |
| **Other Traditions** | — | 0 / 3 |
| **East Asian** | — | 0 / 3 |
| **International** | — | 0 / 4 |
| **Historical** | — | 0 / 1 |
| **Mixed Systems** | — | 0 / 3 |
| **Dictionary Analysis** | — | 0 / 9 term groups |

**Total: 4 / 35 jurisdictions researched**

## Six Types of Death

| Type | Trigger | What Activates |
|---|---|---|
| Biological | Medical certification | Inheritance, estate, guardianship defaults |
| Civil | Court order, felony conviction | Loss of legal capacity |
| Parental | Allocation judgment, termination of rights | Loss of parental capacity |
| Financial | Bankruptcy, insolvency | Loss of financial capacity |
| Corporate | Dissolution, charter revocation | Entity ceases to exist |
| Digital | Account termination | Loss of digital identity |

## Key Findings So Far

- **Germany:** The Pflichtteil (forced share) is constitutionally protected — BVerfGE 112, 332 (2005). It cannot be legislated away. Four layers prevent debtors' prison.
- **France:** Children cannot be disinherited (50-75% reserved). Napoleon's 1804 design is still actively defended — a 2021 amendment closed international forum-shopping.
- **Sweden:** No imprisonment for child support non-payment. Debtors' prison abolished 1879. ~35% of children with separated parents live in alternating residence. Joint custody survives separation as the default.
- **United States:** Domestic support obligations are the only category of debt with no discharge mechanism in American law. Title IV-D creates a 66% federal reimbursement incentive for enforcement.

## Dictionary Analysis

Traces definitional divergences across 7 dictionaries for 9 term groups:

**Dictionaries:** Black's Law Dictionary, Bouvier's, Ballentine's, Words & Phrases, Stroud's, Jowitt's, Oxford Dictionary of Law

**Terms:** death, default, custody, person, parent, forced heirship, civil death, contempt, discharge

## Structure

```
docs/                              # GitHub Pages (live site)
  index.html                       # Hub page with framework + navigation
  common-law.html                  # US (+ planned: UK, AU, CA, IN, ZA)
  civil-germanic.html              # Germany (+ planned: Austria, Switzerland)
  civil-napoleonic.html            # France (+ planned: IT, ES, BR, LA)
  nordic.html                      # Sweden (+ planned: IS, NO, DK, FI)
  islamic.html                     # Planned: 5 schools + overview
  other-traditions.html            # Planned: Jewish, Hindu, Canon
  east-asian.html                  # Planned: JP, CN, KR
  international.html               # Planned: ECHR, ICCPR, Hague, CRC
  dictionary.html                  # Planned: 9 term groups × 7 dictionaries
  exhibit.html                     # Planned: court-ready synthesis

research/                          # Markdown source (verified citations)
  framework.md                     # Core theory
  jurisdictions/{family}/{country}.md
  dictionary/{term_group}.md
  synthesis/{topic}.md
```

## Citation Standard

Every statutory reference in this project was verified against primary sources via web search. No hallucinated legal citations. Sources include Cornell LII, Legifrance, gesetze-im-internet.de, riksdagen.se, and official government publications.

---

Managed by [policy-orchestrator](https://github.com/jthorvaldur/policy-orchestrator). Category: legal.
