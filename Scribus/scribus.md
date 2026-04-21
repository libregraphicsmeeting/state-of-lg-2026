# Scribus

## scribus-0.png

Scribus is a Desktop Publishing (DTP) application which lets you create professional page layouts for PDF (Portable Document Format) files.

## scribus-1.png

The Scribus 1.6 stable branch is in maintenance mode.

The recent 1.6.6 release fixes a few bugs and makes sure that Scribus can be compiled with the current version of some dependencies (Poppler).

Warnings:

- Among other things, support for dark themes and Hi-DPI monitors is limited.
- Due to the dependency on Qt5 the stable branch might not be availble in some Linux distributions.

The development now only happens in the 1.7 branch.

## scribus-2.png

During the last year, three development previews have brought:

- Text Search & Replace in the full document.  
  This removes the previous limitation where text could only be searched inside of the "story" (a.k.a chain of text frames).
- Text styles can by applied with "shortcuts" and the unused styles can be removed.  
  The "shift-esc" shortcut opens a dialog letting the user search through the text styles and apply them: you get keyboard shortcuts for styles, without the need to define them.  
  Loading formatted documents in text frames and mergin Scribus document might add styles that are not actually in use: it's now possible to remove them in one go.
- Live Spell Checker.  
  Scribus now has an on canvas spell checker highlighting mispelled words and providing a context menu for fixing them.
- Polishing the overhauled UI.  
  There have been multiple small refinement and improvements in the new UI launched with Scribus 1.7.0.
- On canvas node editing of Bezier curves.  
  It's now possible to move, add and delete nodes without the need to first activate the specific tools in the Nodes palette.
- Search topics in the preferences.  
  The Preferences and Document Setup dialogs have much grown over the years. It's now possible to filter the settings by typing a search term.
- A logging system in the UI.  
  A new window for logging has been introduced: it will allow inspecting issues with Scribus and the layout without having to rely on the output in the terminal.

The 1.7 development branch:

  - Is based on Qt 6.
  - Reworked most of the important parts of the UI: compact, intuitive, usable, coherent, nicer (WIP): most panes can be kept docked all the time.
  - Support for Hi-DPI (SVG icons) and dark themes.
  - Has a style based table of contents and indexing.
  - Scripting covers most Scribus features and scripts can be started from the menus or the "Action search".
  - Documents can be saved to older file formats.
