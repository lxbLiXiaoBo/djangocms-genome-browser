Revision History
================

0.1.1 2015-05-01

- Add support for Tabix index files:

  - Rename ``Track.bai_file`` field to ``Track.index_file``
  - Validate that index file (``.bai``/``.tbi``) is used only when required

- Improve Genome Browser styling:

  - Add left/right margins to genome browser to allow for easier vertical scrolling
  - Align 'Info' button with genome browser buttons
  - Allow genome browser to expand to full height of window
  - Default to reverse-scrolling mode for trackpads
  - Collapse left margin on small screens


0.1.0 2015-04-25

- A Django app for incorporating a Dalliance genome browser into a Django site with django CMS-specific features
