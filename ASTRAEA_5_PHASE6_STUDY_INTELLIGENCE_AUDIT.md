# ASTRAEA 5.0 — Phase 6: Study Intelligence

## Implemented in this isolated development copy

1. Added optional syllabus-topic linking when logging a study session.
2. Added optional syllabus-topic linking when logging a mistake.
3. Linked topics are shown in the study log and Mistake Vault.
4. Extended AETHER topic prioritisation to account for mastery, retention risk, linked unresolved mistakes, upcoming assessment pressure, subject-level past-paper performance, and logged topic-study evidence.
5. Added a ranked top-five Study Intelligence Queue with a readable explanation of the signals contributing to each recommendation.
6. Existing records with no topic link remain valid; topic links are optional.

## Validation

- Source-level changes were checked with a JavaScript syntax check.
- This is an isolated ZIP; the live GitHub Pages deployment was not changed.
- Browser interaction, Supabase persistence, and import/export still require testing in the user's environment before deployment.
- Past-paper performance is currently a subject-level signal, not a topic-specific score, because paper records do not store topic-level marks.
- Priority scores are heuristic guidance, not predictions of grades.
