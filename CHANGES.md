Markdown Writer FX Change Log
=============================

## 0.4
- Show line numbers in editor (if enabled in Options dialog).
- Automatically reload externally changed markdown files (on window activation).

## 0.3
- Replaced Markdown processor [pegdown] with [commonmark-java]
  and [flexmark-java], which are much faster and implement the [CommonMark] specification.
  [flexmark-java] is always used in the editor for syntax highlighting. 
  The preview can use [commonmark-java] or [flexmark-java] (switchable in the toolbar).
- Redesigned main window UI (modern flat look).
- Removed the tabs "Preview", "HTML Source" and "Markdown AST" from the bottom
  of the preview. Instead added actions to "View" menu and toolbar (at the right side).
- Possibility to hide the Preview (deselect toggle button in toolbar).
- Quickly enable/disable markdown extensions with popover window from toolbar.
- Syntax highlighting improved.
- Use monospaced font in editor.
- Increase/decrease editor font size with `Ctrl++`/`Ctrl+-`. Reset with `Ctrl+0`.
- Configurable editor font family and size in Options dialog.
- Configurable Markdown filename extensions in Options dialog (fixes #2).
- Support \*.svg in image chooser dialog.
- RichTextFX updated to version 0.7-M2.

## 0.2
- RichTextFX (and dependencies) updated to version 0.6.10 (fixes bugs and memory leaks).
- pegdown Markdown parser updated to version 1.6.
- Added five new pegdown 1.6 extension flags to Markdown Options tab.
- Minor improvements.

## 0.1
- Initial release

[CommonMark]: http://commonmark.org/
[commonmark-java]: https://github.com/atlassian/commonmark-java
[flexmark-java]: https://github.com/vsch/flexmark-java
[pegdown]: https://github.com/sirthias/pegdown
