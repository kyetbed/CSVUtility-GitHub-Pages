<!-- sparkle-sign-warning:
IMPORTANT: This file was signed by Sparkle. Any modifications to this file requires updating signatures in appcasts that reference this file! This will involve re-running generate_appcast or sign_update.
-->
# CSV Utility 1.2.0

This release brings everyday column editing to the sheet, keeping every
operation undoable, cancellable, and memory-bounded on multi-gigabyte files.

- Adds a complete set of column operations — Rename, Duplicate, Add Left,
  Add Right, Move Left, Move Right, Split, Combine Selected Columns, and
  Delete — from the column header's context menu and from Edit ▸ Column.
- Splits one column into as many columns as its widest value needs, and folds
  a selected span back into a single column under a header you choose, both
  with progress, cancellation, and safeguards for very large columns.
- Moves and deletes columns through the sheet's identity mapping, so
  rearranging a file-backed CSV stays instant and undo never has to hold an
  entire column in memory.
- Keeps a multi-column selection alive when the header is right-clicked inside
  it, and disables the commands a filtered or read-only sheet cannot perform
  rather than letting them quietly do nothing.
- Draws the Rename, Split, and Combine dialogs in the app's own panel style,
  with the document accent on their confirm buttons and focused fields.
- Aligns every item in the column header menu on a single leading edge.
