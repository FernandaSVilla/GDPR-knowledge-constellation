# The GDPR Constellation

A night-sky reading of what the GDPR actually asks an organisation to do. Forty-five
practical obligations arranged as nine constellations, where every star starts dark and
lights up as you implement it. The unlit regions are your gaps, visible before you read
a word.

**Live → [fernandasvilla.github.io/GDPR-knowledge-constellation](https://fernandasvilla.github.io/GDPR-knowledge-constellation/)**

---

## Why constellations

Article numbers do not tell you what they are for. Article 30 is "records of processing
activities", but what it *does* is oblige you to remember, and to prove that you
remembered. So it sits in **Memoria**.

The nine domains carry Latin names because the name describes the function rather than
the number:

| | Domain | What it covers |
|---|---|---|
| **Licentia** | Lawful basis | Art. 6 basis register, consent, special categories, legitimate interests, purpose compatibility |
| **Transparentia** | Notice and fairness | Art. 13 and 14 notices, intelligibility, layered and just-in-time disclosure |
| **Iura** | Data subject rights | Access, rectification, erasure, restriction, portability, objection, automated decisions, the one-month clock |
| **Memoria** | Accountability and records | RoPA, governance framework, DPO, training, demonstrable accountability |
| **Praevisio** | Risk and design | DPIA, prior consultation, data protection by design, minimisation and retention |
| **Vinculum** | Processors and sharing | Art. 28 contracts, sub-processors, joint controllers, due diligence, confidentiality |
| **Custodia** | Security and breach | Art. 32 measures, detection, the 72-hour notification, communication to individuals, the breach register |
| **Transitus** | International transfers | Adequacy, SCCs, transfer impact assessments, BCRs, derogations |
| **Vigilantia** | Supervision and enforcement | Lead authority, cooperation, complaints and remedies, fine exposure, EU representative |

Naming the function rather than the number is what makes the framework stay in your head.

---

## What it does

**Self-assessment.** Mark each obligation as implemented, in progress, not started or not
applicable. The star brightens as you go, and the tool computes maturity per domain and
overall.

**Fine-tier exposure.** Every obligation carries the statutory maximum category under
Art. 83, 2% or 4%, and the tool flags how many 4%-tier obligations remain open. That is a
prioritisation aid, **not** an estimate of any fine: the tiers are ceilings assigned to
categories of infringement, while actual amounts are set case by case under the eleven
Art. 83(2) criteria.

**Source tagging.** Not everything a supervisory authority expects is written in the
Regulation. Of the 45 obligations selected here, 41 come from the express text, one comes
from *Schrems II*, and three come from EDPB guidance built on a recital or a general duty.
Each is tagged accordingly, because collapsing that distinction is how a useful tool
becomes a misleading simplification.

**Evidence, not intentions.** Every obligation states the artefact a supervisory authority
would expect to see, with concrete examples, plus a suggested review frequency and an
editable owner field.

**Study mode.** Hides the explanation and asks a recall question first, tracking what you
know. Useful for CIPP/E preparation or an interview.

**Gap report.** Exports your assessment as a prioritised report in Markdown or CSV, ordered
by fine exposure, with what each article requires and what evidence is missing.

Citations run down to paragraph and sub-paragraph level: `Art. 30(1)(a)–(g)`,
`Art. 22(1)–(4) · Rec. 71 · Art. 13(2)(f), 14(2)(g), 15(1)(h)`.

---

## Your data

Everything stays in your browser's local storage. No account, no backend, nothing
transmitted. Clearing your browser data clears your progress.

For a project about data protection, that seemed like the only defensible architecture.

---

## Companion project

**[AI & Data Governance Maps](https://fernandasvilla.github.io/AI-and-Data-Governance-map/)**
maps the wider European landscape: 53 instruments and 80 typed relations across EU law and
Council of Europe treaties. Where this tool is a diagnosis of one regulation, that one is
the panorama.

---

## Limits

Not legal advice. This encodes the Regulation's obligation structure, not national
implementing law, sectoral overlays or the case law of any particular supervisory
authority. Several judgements here are contestable and the tool says so where they are.

Verify against the consolidated text on EUR-Lex and current EDPB guidance before relying
on anything. Guidance is revised, and amendments to the GDPR are under negotiation in the
Digital Omnibus.

AI-assisted. Made by **Fernanda S. Villa**, August 2026.

---

## Citation

This work is archived on Zenodo and has a permanent DOI.

> Sánchez-Villa, M. F. (2026). *The GDPR Constellation: a compliance star map*
> (Version 1.0.0) [Software]. Zenodo. https://doi.org/10.5281/zenodo.21872518

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.21872518.svg)](https://doi.org/10.5281/zenodo.21872518)

A `CITATION.cff` file is included, so GitHub shows a **Cite this repository** button in
the sidebar with the citation preformatted in APA and BibTeX.

## Licence

Licensed under [Creative Commons Attribution 4.0 International](LICENSE) (CC BY 4.0).
You may share and adapt this work, including commercially, provided you give credit and
indicate any changes.

---

## Running locally

A single self-contained HTML file. No build step, no dependencies. Open `index.html` in a
browser, or serve the folder:

```bash
python3 -m http.server 8000
```
