# Maintenance rules

## Source and legal framing

1. Search and cross-check MaltaToday, Times of Malta, The Malta Independent and TVM News. Use official material where available for consequential claims.
2. Read the full report; never rely on a search snippet or social-media paraphrase.
3. Attribute testimony, allegations, denials, evidence descriptions and judicial rulings precisely.
4. Preserve the presumption of innocence and the accused’s not-guilty plea.
5. Use short quotations only, with the speaker and courtroom context.
6. Record outlet, URL, byline and publication/update time for every article used. If accounts differ, attribute each version and do not silently reconcile them.
7. If nothing materially new has been reported, make no trial-content change and no no-op trial commit.

## Hourly update pattern

- Amend the existing court-day record as a live report changes; do not create hourly duplicate days.
- Before the first substantive change in a run, snapshot the prior page under `archive/YYYY/MM/DD/HH00/index.html`.
- Log the source URL, byline, publication/update time and verification notes under `sources/YYYY-MM-DD.md`.
- Keep the latest dashboard, counts, court-day range and footer synchronized.
- Update the daily infographic with 3–5 exact, sourced takeaways. Prefer concrete counts, sequences, evidence categories or rulings. Do not invent scores or imply guilt.
- Publish a separate Daily Visual edition for every new court day. Rotate the subject materially—people dossier, evidence map, quote anatomy, timeline, courtroom explainer, curiosity, ruling or communications network—and choose a professional visual/interactive treatment that fits the subject. Preserve previous editions and link the underlying report.

## Relationship cloud

- Green: reported friendship, family, closeness, cooperation or association.
- Red: conflict, adverse testimony, alleged harm or accusation.
- Grey dashed: official, professional or investigative contact.
- Line thickness reflects repeated or strongly supported reporting, not moral importance.
- Add a node for every materially named trial character and a concise role, description and relevant day reference.
- Add an edge only when the relationship itself is supported by the source material.

## Images

- Use only correctly identified images. A published photograph requires a clear reuse licence or explicit permission.
- An original AI editorial illustration may be created from a visually verified identity reference, but it must use a new pose, clothing, composition and background and be clearly labelled as an illustration—not a photograph.
- Record the creator/workflow and reference source in `assets/people/LICENSES.md` and the profile panel. Do not publish the identity-reference file.
- Do not copy publisher photographs when their terms prohibit reproduction. Use initials when identity cannot be safely verified.

## Validation

- JavaScript parses without errors.
- Day numbers and source URLs are unique and chronological.
- Every relationship endpoint resolves to a person node.
- New source links use HTTPS URLs from the permitted local outlets or official material.
- The Latest, Daily Visual, Relationships and Timeline views work at desktop and phone widths, and every Daily Visual control is keyboard accessible.
