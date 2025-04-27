Editor - A Lightweight Text Editor
===========================================

Overview
--------
Editor is a simple, fast, and lightweight text editor for Linux. 
It mimics some of the most important features of Nano while adding extra 
powerful capabilities such as Undo/Redo, mouse support, and syntax highlighting 
(for Python files).

Features
--------
- Open, create, edit, and save text files easily
- Word wrapping for long lines
- Line numbers display
- Full keyboard shortcuts
- Undo (Ctrl+Z) and Redo (Ctrl+Y) support
- Cut (Ctrl+K) and Paste (Ctrl+U) entire lines
- Search (Ctrl+W) and Search-Replace (Ctrl+\)
- Jump to specific line (Ctrl+_)
- Mouse click support to move the cursor
- Auto-backup existing files before overwriting (filename~)
- Detects filetype (.py files highlight keywords)
- Recent files menu (via --recent option)
- Title Bar showing current file or buffer name

Usage
-----
To open a file:
    python3 editor.py filename.txt

To create a new empty buffer:
    python3 editor.py

To open a recent file:
    python3 editor.py --recent

Controls / Keyboard Shortcuts
------------------------------
| Shortcut  | Action                              |
|-----------|-------------------------------------|
| Ctrl+G    | Show help                           |
| Ctrl+O    | Write out (save file)                |
| Ctrl+X    | Exit the editor                     |
| Ctrl+W    | Search for text                     |
| Ctrl+\    | Search and Replace text             |
| Ctrl+_    | Jump to a specific line              |
| Ctrl+K    | Cut (remove) the current line       |
| Ctrl+U    | Paste the last cut line             |
| Ctrl+Z    | Undo the last change                |
| Ctrl+Y    | Redo the undone change              |
| Arrow Keys| Move cursor                         |
| Tab       | Insert 4 spaces                     |
| Backspace | Delete character or merge lines     |
| Mouse     | Click inside text to move cursor    |

Requirements
------------
- Python 3.x
- Curses library (default installed on most Linux systems)

Idea
-------
Built for speed, simplicity, and real Linux use.

License
-------
This project is free to use, modify, and redistribute.
MIT License or public domain.

