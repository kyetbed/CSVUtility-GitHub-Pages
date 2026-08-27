<!-- sparkle-sign-warning:
IMPORTANT: This file was signed by Sparkle. Any modifications to this file requires updating signatures in appcasts that reference this file! This will involve re-running generate_appcast or sign_update.
-->
# CSV Utility 1.4.1

This hotfix makes spreadsheet dragging safer and adds control over the default
size of newly opened grids.

- Fixes a crash when moving a multi-cell selection that crossed from populated
  rows into the sheet's empty displayed rows.
- Applies the same boundary-safe snapshot handling to fill-handle drags.
- Adds **Default amount of columns** and **Default amount of rows** controls to
  Grid Editor settings.
- Keeps the standard defaults at 26 columns (A–Z) and 100 rows, while allowing
  new sheets to use a custom visible minimum without allocating empty cells.
