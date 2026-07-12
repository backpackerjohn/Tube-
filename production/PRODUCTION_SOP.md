# Production SOP

## Purpose

This SOP turns one approved topic into an original, source-auditable faceless video. It is designed to avoid inauthentic/reused-content traps and to keep fast-changing vehicle advice current. YouTube’s policy requires original, authentic content and rejects mass-produced, repetitive or minimally transformed material. [S05]

## Folder structure per episode

```
/episodes/EVSO-###-slug/
  00_brief.md
  01_source_log.md
  02_claim_ledger.md
  03_script.md
  04_visual_plan.md
  05_assets/
  06_project/
  07_exports/
  08_rights_and_licenses/
  09_post_publish.md
```

The repository contains strategy artifacts, not episode media. Use this structure in the production workspace when launching.

## Roles

A single creator can perform all roles, but each role must be completed:

- **Opportunity editor:** validates demand and audience decision.
- **Researcher:** gathers official, manufacturer and market evidence.
- **Skeptic:** attempts to disprove the premise.
- **Writer:** builds the decision narrative.
- **Visual producer:** creates original diagrams, charts and annotated screens.
- **Fact checker:** verifies every claim after the script is locked.
- **Editor:** assembles and mixes.
- **Publisher:** performs metadata, rights and freshness checks.

The skeptic and fact checker should use separate passes even when they are the same person.

## Phase 1 — Greenlight

Complete the topic score in [CONTENT_ENGINE.md](../content/CONTENT_ENGINE.md).

Required outputs:

- one-sentence decision;
- named use case;
- search/API evidence;
- at least one primary source;
- initial title and thumbnail promise;
- original decision tool;
- known safety/legal sensitivity.

Reject the topic if its main value requires copied footage, access to a vehicle the creator does not have, or claims that cannot be verified.

## Phase 2 — Source stack

Use this hierarchy:

1. Government regulator or official database.
2. Manufacturer warranty/manual/service campaign.
3. Standards body or peer-reviewed research.
4. Reputable market reporting with named data.
5. Specialist commercial dataset with disclosed limitations.
6. Owner reports only as questions or examples, never prevalence.

For each source record:

- URL;
- title;
- publisher;
- publication/update date;
- accessed date;
- exact claim supported;
- relevant quote or paraphrase;
- reliability grade;
- limitations;
- screenshot/file name if retained.

No source is added merely to make the list look longer.

## Phase 3 — Claim ledger

Create a table:

| Claim ID | Script wording | Type | Source | Status | Freshness |
|---|---|---|---|---|---|
| C01 | ... | verified / observed / inference / unknown | URL/source ID | pass/fail | A/B/C |

Rules:

- **Verified:** directly supported by a reliable source.
- **Observed:** true of a dated sample, not necessarily the whole market.
- **Inference:** reasoning from evidence; say so.
- **Unknown:** cannot be established without the individual vehicle or buyer input.

Delete claims that are interesting but unsupported.

## Phase 4 — Adversarial check

The skeptic answers:

1. Is the title technically true?
2. Is the video confusing correlation with causation?
3. Is a dashboard estimate being mistaken for battery health? [S09]
4. Is a current warranty page being applied to the wrong model year? [S06]
5. Is a clean NHTSA result being treated as complete history? [S04]
6. Is a national average being applied to a local buyer?
7. Is depreciation framed as a guaranteed bargain?
8. Is the conclusion influenced by an affiliate or sponsor?
9. Is a rare failure made to look common through visuals?
10. What evidence would reverse the verdict?

The brief cannot proceed until the reversal conditions are written.

## Phase 5 — Script

Target structure for an 8–13 minute video:

| Section | Approx. time | Purpose |
|---|---:|---|
| Hook | 0:00–0:25 | cost or decision tension |
| Verdict preview | 0:25–0:45 | tell viewer what will be decided |
| Method | 0:45–1:15 | evidence categories and use case |
| Evidence block 1 | 1:15–3:30 | highest-impact gate |
| Evidence block 2 | 3:30–6:00 | second gate and counterargument |
| Evidence block 3 | 6:00–8:30 | cost/fit and unknowns |
| Verdict | 8:30–10:00 | buy/wait/walk conditions |
| Checklist/bridge | final 30 sec | next action and playlist |

Writing rules:

- Put source IDs in the working script.
- Read all numbers aloud in a listener-friendly way.
- Repeat a number only when its meaning changes.
- State limitations near the claim, not in a distant disclaimer.
- Avoid false suspense; preview the real conclusion.
- Do not copy source phrasing except a necessary short quote.
- No high-voltage repair steps.

## Phase 6 — Visual plan

Every paragraph receives a visual purpose, not merely a stock-footage search term.

Priority order:

1. original chart/table;
2. original diagram/animation;
3. source document with annotated line;
4. original screen recording of recall, route or calculator workflow;
5. licensed still/stock to establish context;
6. text card only when clarity improves.

A-roll is narration plus the channel’s visual system. There is no requirement for a human face.

### Originality minimum

Each video must include at least:

- one custom decision matrix or calculation;
- one source-document walkthrough;
- one model/use-case-specific diagram;
- one explicit unknown/reversal card;
- one conditional verdict built from the episode evidence.

This prevents a generic voiceover-over-stock pattern.

## Phase 7 — Rights and asset control

For every non-original asset record:

- source URL;
- creator/owner;
- license or permission basis;
- download date;
- required attribution;
- intended duration/use;
- proof file or receipt.

Do not assume “press image” means unrestricted use. Use the minimum necessary for commentary and replace with original diagrams whenever possible.

## Phase 8 — Narration

- Human-review all pronunciations: model names, agencies, connector standards and chemistry terms.
- Mark uncertainty with vocal emphasis: “may,” “in this sample,” “for this use case.”
- Keep pace roughly conversational; do not compress dense legal text.
- Export clean WAV before music.
- Retain commercial-use rights for any contracted or synthetic voice.

## Phase 9 — Edit template

Track layout:

1. narration;
2. source/document cards;
3. original charts/diagrams;
4. contextual licensed visuals;
5. captions/lower thirds;
6. sound effects;
7. music.

Editorial rhythm:

- new meaningful visual every 4–8 seconds during the hook;
- slower document holds when the viewer must read;
- no visual change merely to reset attention;
- score animation only after evidence;
- use the three-truths box before the verdict.

## Phase 10 — Fact-check lock

After the picture is nearly locked, the fact checker:

- opens every current URL again;
- verifies each on-screen number and unit;
- checks model year, trim and region;
- confirms dates in source footers;
- verifies calculations independently;
- confirms that narration and graphics say the same thing;
- checks that “observed” and “inference” labels remain visible;
- searches for a newer official source;
- records corrections made.

Tax, incentive, recall, warranty and connector claims receive a final check within 24 hours of upload.

## Phase 11 — Safety and legal review

- Educational information is not a substitute for a mechanic, electrician, tax professional, insurer or attorney.
- The disclaimer does not excuse careless advice; unsafe steps are removed.
- High-voltage components are never opened, probed or bypassed.
- Any electrical-installation discussion stops at questions to ask a licensed professional.
- Allegations about a seller or manufacturer require documentary evidence and a fair description.
- Listing screenshots are minimized, annotated and stripped of personal information.

## Phase 12 — Export and technical QC

Recommended baseline:

- 3840×2160 or 1920×1080, 16:9;
- 24 or 30 fps, consistent within episode;
- captions supplied and manually checked;
- narration intelligible on phone speaker;
- no clipped audio;
- source footers readable at 1080p;
- thumbnail checked at 10% scale;
- spelling check on all verdict cards.

## Phase 13 — Metadata

Description follows the template in [LAUNCH_PLAN.md](../content/LAUNCH_PLAN.md).

Title rules:

- under roughly 70 characters when possible;
- decision and model/problem appear early;
- no year unless the episode is genuinely year-specific/current;
- no “shocking,” “destroyed” or “scam” unless precisely supported.

Tags are optional support, not a strategy. The first two description lines must explain the decision.

## Phase 14 — Post-publish review

At 24 hours, 7 days and 30 days record:

- impressions and traffic source;
- CTR by source;
- first 30-second retention;
- average percentage viewed;
- subscribers per 1,000 views;
- returning viewers;
- end-screen clicks;
- corrections/questions.

Do not remove a poorly performing video solely to protect averages. Its data is part of the experiment.

## Correction protocol

When a meaningful error is found:

1. Verify it with the best available source.
2. Add a pinned correction with date and timestamp.
3. Update description and downloadable checklist.
4. Use YouTube’s editor or replace the video only when the error materially harms the viewer and cannot be corrected in context.
5. Log the cause: stale source, model-year mismatch, calculation, wording or edit.
6. Add a prevention rule to the SOP.

## Completion checklist

- [ ] Decision and audience are explicit.
- [ ] Demand was validated.
- [ ] Source hierarchy was followed.
- [ ] Claim ledger is complete.
- [ ] Skeptic pass is complete.
- [ ] Original decision tool is visible.
- [ ] No unsupported claim remains.
- [ ] Rights log is complete.
- [ ] Fact check occurred after edit.
- [ ] Description contains last-verified date.
- [ ] Thumbnail/title match conclusion.
- [ ] Next-decision bridge is present.