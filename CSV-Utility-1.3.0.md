<!-- sparkle-sign-warning:
IMPORTANT: This file was signed by Sparkle. Any modifications to this file requires updating signatures in appcasts that reference this file! This will involve re-running generate_appcast or sign_update.
-->
# CSV Utility 1.3.0

This release adds spreadsheet-style Functions, faster navigation, and clearer
import and export control while preserving CSV Utility's responsiveness on
multi-gigabyte files.

- Adds an optional experimental Functions menu with `SUM`, `AVERAGE`, `COUNT`,
  `MAX`, and `MIN`, stored as portable A1-style formulas such as
  `=SUM(F8:H8)`.
- Evaluates large file-backed formulas in the background with constant-memory
  aggregation and revision-aware caching, so selections and scrolling remain
  responsive while a result is calculated.
- Validates formulas as they are typed, using green for valid references and
  red for malformed or out-of-range expressions.
- Makes the active-cell reference clickable, opening a compact themed Go To
  panel for jumping directly to a cell, row, or column.
- Expands the row-number gutter automatically for very large sheets so
  eight-digit row labels and cell references remain legible.
- Reworks Settings into one continuous, searchable page whose sidebar links
  directly to General, Appearance, Grid Editor, Import & Export, Experimental,
  and Files & Performance sections.
- Adds persistent import defaults for delimiter and text encoding, plus export
  defaults for format, encoding, and line endings.
- Refines themed menus, formula controls, the select-all corner, and toolbar
  icon alignment throughout the sheet.
