<!-- sparkle-sign-warning:
IMPORTANT: This file was signed by Sparkle. Any modifications to this file requires updating signatures in appcasts that reference this file! This will involve re-running generate_appcast or sign_update.
-->
# CSV Utility 1.1.0

This release adds powerful open-sheet workflows while keeping multi-gigabyte
CSV files responsive and memory-bounded.

- Adds a scalable Data Quality Check for malformed rows, mismatched column
  counts, unbalanced quotes, blank headers, and duplicate headers, with direct
  navigation between detected issues.
- Adds Transform Selected Cells with Replace, Prefix, Suffix, Fill Blanks,
  Title Case, Add, Multiply, and Round operations, including progress,
  cancellation, undo, and safeguards for very large selections.
- Makes column filtering safer on high-cardinality data by bounding unique
  values, fixing a cross-device crash, and keeping expanded sort options clear
  of the filter list and footer.
- Moves file tabs to the bottom and places the compact editor tools alongside
  the active-cell field for a cleaner, sheet-focused workspace.
- Refines the Start screen with a centred stacked layout, four concise recent
  files, reliable filename truncation, and consistent hover-only remove icons.
- Corrects selection statistics for empty grid areas and improves icon hover
  state reliability when windows change focus.
