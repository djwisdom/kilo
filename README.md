# Kilo

Kilo is a originally a small text editor in less than 1K lines of code (counted with cloc).

Usage: kilo `<filename>`

Keys:

  CTRL-S: Save
  
  CTRL-Q: Quit
  
  CTRL-F: Find string in file (ESC to exit search, arrows to navigate) 
  
  CTRL-N: Toggles line number (Off, Normal, Relative)


Kilo does not depend on any library (not even curses). It uses fairly standard
VT100 (and similar terminals) escape sequences. 

This is a work-in-progress and is primarily updated as a learning tool.  

Version
- 0.0.3 No longer errors out if filename does not exist. Empty file is opened.
- 0.0.2 Added line number toggle. Syntax highlighting disabled by default. Cosmetic updates.
- 0.0.1 Initial commit. Source is somewhat similar to original kilo from antirez.

Inhale. Exhale. Repeat.
