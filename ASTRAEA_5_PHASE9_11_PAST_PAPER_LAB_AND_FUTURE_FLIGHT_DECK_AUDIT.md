# ASTRAEA Phase 9 + Phase 11 Audit

## Scope
Development-only update based on the Phase 7 development build. The live GitHub Pages deployment was not changed.

## Phase 9 — Past Paper Laboratory
- Adds paper count, mean percentage and best logged attempt summaries.
- Adds subject-wise mean percentage bars and descriptive notes based only on recorded paper data.
- Adds a subject filter for the paper table.
- Adds optional topics/question numbers to revisit to paper records.
- Shows reflection and revisit notes in the record table.
- Validates that scores are between zero and the total marks.
- Clearly labels averages as descriptive, not predicted Cambridge grades or thresholds.

## Phase 11 — University & Future Flight Deck
- Adds an independent workspace for universities, scholarships, competitions, programmes and projects/internships.
- Saves optional deadlines, statuses, notes and official links.
- Counts saved opportunities and upcoming deadlines.
- Adds an achievement archive with date, category and evidence/notes.
- Supports deletion of individual opportunity and achievement records.
- Uses the existing ASTRAEA save/cloud-sync pathway; existing records are not intentionally reset.

## Validation performed
- JavaScript syntax checked for all inline scripts using Node.js.
- Verified view IDs and navigation title entries exist.
- ZIP integrity tested after packaging.

## Limitations
- Subject averages are unweighted means of logged paper percentages; they are not official weighted grades.
- Topic-level analytics rely on the user's optional notes, not automatic parsing of question marks.
- Links are stored by the user; ASTRAEA does not verify eligibility or submit applications.
- The package is a development build. User should test it before manually deploying to the live site.
