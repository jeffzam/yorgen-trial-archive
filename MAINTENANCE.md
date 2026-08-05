# Maintenance rules

## Source and legal framing

1. Use MaltaToday’s court reporting as the factual source for trial updates.
2. Read the full report; never rely on a search snippet or social-media paraphrase.
3. Attribute testimony, allegations, denials, evidence descriptions and judicial rulings precisely.
4. Preserve the presumption of innocence and the accused’s not-guilty plea.
5. Use short quotations only, with the speaker and courtroom context.
6. If nothing materially new has been reported, make no file change and no commit.

## Hourly update pattern

- Amend the existing court-day record as a live report changes; do not create hourly duplicate days.
- Before the first substantive change in a run, snapshot the prior page under `archive/YYYY/MM/DD/HH00/index.html`.
- Log the source URL, byline, publication/update time and verification notes under `sources/YYYY-MM-DD.md`.
- Keep the latest dashboard, counts, court-day range and footer synchronized.
- Update the daily infographic with 3–5 exact, sourced takeaways. Prefer concrete counts, sequences, evidence categories or rulings. Do not invent scores or imply guilt.

## Relationship cloud

- Green: reported friendship, family, closeness, cooperation or association.
- Red: conflict, adverse testimony, alleged harm or accusation.
- Grey dashed: official, professional or investigative contact.
- Line thickness reflects repeated or strongly supported reporting, not moral importance.
- Add a node for every materially named trial character and a concise role, description and relevant day reference.
- Add an edge only when the relationship itself is supported by the source material.

## Images

- Use only correctly identified images with a clear reuse licence or explicit permission.
- Record the creator, licence and source page in `assets/people/LICENSES.md` and the profile panel.
- Do not copy publisher photographs when their terms prohibit reproduction.
- Use initials when no safe, verified portrait is available.

## Validation

- JavaScript parses without errors.
- Day numbers and source URLs are unique and chronological.
- Every relationship endpoint resolves to a person node.
- New links use MaltaToday HTTPS URLs.
- The Latest, Relationships and Timeline views work at desktop and phone widths.

