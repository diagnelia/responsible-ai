# Responsible AI at Diagnelia

How the AI in [Diagnelia](https://diagnelia.com) is designed: what it does, what it does not do and the rules we follow.

> **Stage: in development.** Diagnelia is not yet available to the public. This document describes how we are designing the AI and will change as we learn. Diagnelia organises health information. It does not diagnose, treat or replace a doctor. **In an emergency, call 112.**

## What the AI does

Diagnelia turns years of symptoms, visits and documents into one clear, sourced page that the next doctor can read in two minutes. It works in six steps, from your words to one page:

| Step | What happens |
|---|---|
| 1. Listen | Your story, in a guided conversation at your pace |
| 2. Read | Scans and PDFs are read and dated |
| 3. Order | One timeline, with gaps shown |
| 4. Translate | Your words into clinical terms (standard phenotype terms such as HPO) |
| 5. Check | Warning signs: see a doctor now |
| 6. Hand over | One page, every line sourced |

What you leave with: a one-page chronology for any doctor, questions for your next visit, the kind of specialist who may help, and European expert networks (ERNs) to ask about.

## What the AI does not do

- **It never names a disease to you.** Guessing scares people and answers nothing. Diagnosis stays with your doctor.
- **It does not replace your doctor.** It prepares the visit. The doctor decides.
- **It does not sell your data.** Not to advertisers, not to anyone else.
- **It does not learn from you in secret.** Your story never trains an AI unless you say yes.

## The rules it works under

- **It stops at warning signs** and tells you to call 112 or see a doctor today.
- **It shows its sources.** Every line links to your words or a document.
- **It says when it is unsure.** Unclear dates are marked, never guessed. Missing dates and unread documents are flagged, never made up.
- **Doctors write its questions.** Our medical lead checks every one.

## Who decides

**The final word is always a doctor's.** In Stage 1 the patient tool only organises information. In Stage 2 the clinician tool will suggest rare conditions worth considering and the tests that could confirm or exclude them, and the clinician decides.

## Data and consent

- Stored on servers in the European Union, under the GDPR.
- Encrypted in transit and at rest.
- Health data is processed only with your explicit consent (GDPR Art. 9(2)(a)).
- Not used for AI training unless you opt in. You can withdraw at any time.
- Yours to export or delete in one step.
- Never sold. No ads, no data brokers.

## Rules we are building for

| Area | Rule |
|---|---|
| Data protection | GDPR |
| Stage 2 clinician tool | Developed as a medical device under the EU MDR |
| Quality system | ISO 13485 |
| Risk management | ISO 14971 |
| Software lifecycle | IEC 62304 |
| Market access | CE marking through conformity assessment with a notified body |

The path to Stage 2: a clinical advisory board of rare disease clinicians and geneticists, a retrospective study on anonymised cases where the diagnosis is already known, a prospective pilot alongside usual care, then CE marking.

### Industry funding

Diagnelia takes industry money only for early detection programmes, under five published rules:

1. Funding never buys access to a patient.
2. Nothing is promoted inside Diagnelia.
3. Only anonymous totals, only with consent.
4. Every funder is named.
5. An independent ethics advisor can say no.

## Contact

Questions or suggestions about how the AI should behave: open an issue in this repository or email [info@diagnelia.com](mailto:info@diagnelia.com). Please never include real personal or medical data. Security problems: see our [security policy](https://github.com/diagnelia/.github/blob/main/SECURITY.md).

## Licence

This document is licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](LICENSE). You may share and adapt it with credit to Diagnelia.
