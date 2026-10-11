# Change Log

All notable changes to the "immutable-theme" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.


## [1.0.0]

- **Complete theme overhaul.** Rebuilt both variants from the ground up with a consistent 5-tier elevation system (`#161616` → `#1E1E1E` → `#252525` → `#2E2E2E` → `#383838` for the lighter variant; one step darker for the darker variant).
- Renamed variants to **Immutable (Darker)** and **Immutable (Lighter)** — both are dark themes, distinguished by base background depth.
- Added `symbolIcon.*` colors (32 keys) so autocomplete and symbol-picker icons match the theme palette throughout.
- Added `editorInlayHint.*` colors so inline type/parameter hints in TypeScript, Rust, and Go render consistently with the comment tone rather than VS Code's defaults.
- Added `editorSuggestWidget.selectedForeground`, `selectedIconForeground`, and `focusHighlightForeground` so the highlighted autocomplete item is fully themed.
- Added `merge.*` colors for git conflict blocks (current branch = teal, incoming = blue, common ancestor = purple-tinted).
- Added `diffEditorGutter.*` and `diffEditorOverview.*` so the diff view gutter and scrollbar markers use the theme's add/remove colors.
- Added `searchEditor.*` find-match highlights.
- Added `notificationsErrorIcon`, `notificationsInfoIcon`, and `notificationsWarningIcon` foreground colors.
- Added `gitDecoration.renamedResourceForeground` for renamed files in Source Control.
- Added `editorGutter.commentGlyphForeground`, `commentRangeForeground`, and `foldingControlForeground`.
- Added `editorPane.background` and `editorGroup.emptyBackground` for empty editor splits.
- Added `editor.foldBackground` and `editor.linkedEditingBackground` (rename-symbol highlights).
- Added `breadcrumb.foreground`, `tab.hoverForeground`, and `keybindingTable.*`.
- Changed `focusBorder` from a flat gray to a teal tint (`#00D1D166`) so keyboard-focus rings match the accent color.
- Fixed `peekView.border` — was semi-transparent, now solid.
- Fixed `inputValidation.infoBackground` and `warningBackground` — were flush with the editor background, now lifted to the raised-widget tier.
- Semantic token colors (`semanticTokenColors`) fully cover TypeScript, Rust, Go, Java, and C# LSP tokens with the same palette as TextMate grammar scopes.

## [0.2.2]

- Fixed the GPT theme's editor tab bar so the active tab is visually distinct from inactive tabs, and hovering over a tab now shows a clear highlight.
- Added the **GPT theme** variant, inspired by the color palette used in the ChatGPT mobile app.
- Fixed a few inconsistent color codings in the GPT theme.

## [0.0.6]

- Refactored the main theme template for cleaner, more consistent color definitions.

## [0.0.5]

- Added the **Black - Green** variant: the same base theme with notification colors changed from yellow to blue/green.

## [0.0.4]

- Added the **Black - Green** color variant of the theme.

## [0.0.3]

- General color refinements to the base theme.

## [0.0.2]

- Minor color adjustments and fixes.

## [0.0.1]

- Initial release of the Immutable Theme, including the base **Black** variant.
