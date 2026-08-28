# TOEIC Vocabulary — 3000 Words

The main vocabulary set for the TOEIC (Listening & Reading) test, grouped by **topic**
(not alphabetically). This set is built to sit beside the starter set in `../toeic-600/`.

## What is in each entry

Every word is a level-3 heading, followed by:

- **IPA** transcription (British RP / General American where they align; both forms shown when word stress shifts between noun and verb, e.g. `/ˈprɒdʒekt/` (n) · `/prəˈdʒekt/` (v))
- Part of speech: **(n)** noun · **(v)** verb · **(adj)** adjective · **(adv)** adverb · **(prep)** preposition · **(phr)** phrase
- **English meaning** — a short definition
- **Example** sentence(s)
- If a word has several common senses, only the **first 3 meanings** are given, each with its own example.

```markdown
### streamline
- **IPA:** /ˈstriːmlaɪn/
- **Meaning 1 (v):** To make a process or system simpler and more efficient.
  - *Example:* The new software helped [streamline](25-information-technology.md#streamline) the whole [approval](06-projects-and-deadlines.md#approval) process.
```

## Relationship to the 600-word set

This set is meant to *extend* `../toeic-600/`, so it mostly avoids repeating those words.
(A few dozen do appear in both, with the same meaning — harmless for navigation.)
Example sentences here **can and do link into `../toeic-600/`** when a word's entry lives there.

## Cross-links inside examples (ctrl / cmd + click)

Where an example sentence uses a word that has its own entry *elsewhere in this 3000-word set*,
that word is written as a relative Markdown link:

```
[surface form](FILE.md#anchor)
```

- **Ctrl + click** (Cmd + click on macOS) the link in VS Code, most IDEs, or a Markdown
  previewer to jump straight to that word's entry.
- Inflected forms link back to the base entry — e.g. `[suppliers](21-transportation-and-shipping.md#supplier)`,
  `[delivered](06-projects-and-deadlines.md#deliver)`.
- Links to a word in the **same file** still include the filename so they work in every editor.
- **Targets span both folders.** An example word links wherever its entry lives — a topic
  file in this set, **or** a file in `../toeic-600/` (written with a `../` path). When a word
  has an entry in both sets, the link points to the one in the same folder as the example.
- **What gets linked:** all multi-word terms (e.g. `supply chain`, `board of directors`) plus
  longer single words. Very short or highly ambiguous common words (e.g. *state*, *share*,
  *will*, *reach*) are **not** auto-linked, to avoid links to the wrong sense. At most 3 links
  per example, and an entry never links to itself. ~1,250 cross-links across the two sets;
  every one resolves.

### Anchor rule

Anchors follow the common GitHub / VS Code slug rule applied to the heading text:

1. lower-case everything
2. remove punctuation (`.`, `,`, `&`, `/`, `'` …)
3. replace each space with a hyphen

So `### follow up` → `#follow-up`, `### cost-effective` → `#cost-effective`,
`### board of directors` → `#board-of-directors`.

## Topic files

See [`word-index.md`](word-index.md) for the complete list of all 3000 words and the file each one lives in.

| Section | Files |
|---|---|
| **A. Corporate & Professional Life** | `01`–`10` |
| **B. Industry, Commerce & Economy** | `11`–`24` |
| **C. Science, Technology & Society** | `25`–`34` |
| **D. Daily Life & Personal Affairs** | `35`–`40` |

| # | File | Words |
|---|------|-------|
| 01 | career-and-professional-development.md | 75 |
| 02 | company-organization-and-departments.md | 75 |
| 03 | management-and-leadership.md | 75 |
| 04 | teamwork-and-workplace-relationships.md | 75 |
| 05 | business-strategy-and-planning.md | 75 |
| 06 | projects-and-deadlines.md | 75 |
| 07 | data-reports-and-analysis.md | 75 |
| 08 | business-communication.md | 75 |
| 09 | negotiation-and-persuasion.md | 75 |
| 10 | problem-solving-and-decision-making.md | 75 |
| 11 | economics-and-markets.md | 75 |
| 12 | banking-and-investment.md | 75 |
| 13 | accounting-and-auditing.md | 75 |
| 14 | law-and-compliance.md | 75 |
| 15 | taxation-and-regulation.md | 75 |
| 16 | retail-and-store-operations.md | 75 |
| 17 | manufacturing-and-engineering.md | 75 |
| 18 | construction-and-building-trades.md | 75 |
| 19 | energy-and-utilities.md | 75 |
| 20 | agriculture-and-food-supply.md | 75 |
| 21 | transportation-and-shipping.md | 75 |
| 22 | real-estate-and-property-development.md | 75 |
| 23 | hospitality-and-tourism-industry.md | 75 |
| 24 | advertising-pr-and-media.md | 75 |
| 25 | information-technology.md | 75 |
| 26 | telecommunications-and-networks.md | 75 |
| 27 | science-and-research.md | 75 |
| 28 | environment-and-sustainability.md | 75 |
| 29 | health-medicine-and-wellness.md | 75 |
| 30 | education-and-training.md | 75 |
| 31 | government-and-public-services.md | 75 |
| 32 | media-news-and-publishing.md | 75 |
| 33 | arts-culture-and-entertainment.md | 75 |
| 34 | weather-climate-and-natural-events.md | 75 |
| 35 | shopping-and-consumer-life.md | 75 |
| 36 | personal-finance-and-household-budget.md | 75 |
| 37 | home-housing-and-maintenance.md | 75 |
| 38 | food-cooking-and-dining-out.md | 75 |
| 39 | leisure-hobbies-and-sports.md | 75 |
| 40 | travel-commuting-and-getting-around.md | 75 |

**Total: 3000 words**

## Build status

- [x] `README.md`
- [x] `word-index.md` (full 3000-word registry, kept in sync with the topic files)
- [x] Topic files `01`–`40` — **complete**, 75 entries each = 3000 words

All 3000 headwords are unique across this set, so every cross-link resolves to exactly one entry.
Example sentences link across topic files and across into `../toeic-600/`.
