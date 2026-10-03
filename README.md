# Search Notes for Tropy

Search all notes associated with a Tropy item, including notes across multiple photos and image selections.

## AI declaration

Forked from [Tropy Note Tools](https://github.com/graytape/tropy-note-tools) by Graytape. Additional features were added with assistance of Claude Code (Sonnet 5.5).

## Features

- A search bar with a magnifier icon sits at the top of the notes pane. It is always visible by default.
- Results appear in their own pane below the note editor, so the editor does not move.
- Ctrl+F / Cmd+F moves the cursor to the search bar. Esc clears the search.
- Highlights all matches and displays a result list.
- Selecting a result opens the corresponding photo and note.
- Enter / Shift+Enter navigates between results.
- Case-sensitive and regular-expression search.
- English, Italian, French and Spanish, following Tropy’s language.
- No changes to note content or formatting.

## Installation

Install the ZIP through **Preferences → Plugins** and enable it. Use **Uninstall** in the same panel to remove it. The ZIP must contain a single folder (for example `search-tropy-notes/`) holding `package.json`, `index.js`, `style.css`, `icon.svg` and `lib/`. If the plugin does not appear straight away, close and reopen Preferences.

## Settings

Click **Settings** on the plugin in **Preferences → Plugins**.

- **Always show the search bar** (on by default). On: the search bar is always shown above your notes. Off: the search bar appears only when you press Ctrl+F / Cmd+F, and a × button or Esc hides it again. If the view does not change after you switch the setting, restart Tropy.

Tropy also shows a **Name** field and +/− buttons for every plugin. They are built into Tropy and are meant for import and export plugins. This plugin needs only one entry, so leave the Name field alone and do not add extra copies with +.

## Compatibility

Tested with Tropy **1.17.3** and **1.18.0-beta.6**.

Requires CSS Highlight support. Uses internal Tropy APIs that may change in future versions.

No build step is needed. The plugin is plain JavaScript and runs as it is.

**Plugin version:** 1.4.1