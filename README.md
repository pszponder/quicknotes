# QuickNotes

## Description

This application serves as a way to take and manage quick notes from the CLI


## Requirements

- Be able to save a string of text as a note
  - Save a single-line string of text
  - Save a multi-line string of text
  - Tag a note with one or more tags during note creation
- Be able to view a list of saved notes
  - Retrieve last x notes
  - Retrieve notes from today
  - Retrieve notes from yesterday
  - Retrieve notes from last x days
  - Retrieve notes based on specific timestamp
  - Retrieve notes older than specified timestamp (from beginning to timestamp)
  - Retrieve notes newer than specified timestamp (from timestamp to end)
  - Retrieve notes based on timestamp range
  - Retrieve x random notes
  - Retrieve a note based on note id
  - Retrieve notes based on one or more tags
- Be able to edit a note
  - Edit note just retrieved from a search
  - Select a note to edit from a list of notes returned from a retrieval (if retrieving multiple notes)
  - Be able to update the text of a note
  - Be able to add one or more tags to a note
  - Be able to remove one or more tags from a note
  - Be able to edit tags in a note
- Be able to remove a note
  - Remove note by id
  - Remove note(s) based on tag(s) 
  - Remove note(s) based on timestamp range
  - Remove note based on specific timestamp
  - Select notes in a list to remove
- Enable option to warn user before deleting note(s)

## Credit / Inspiration

This project is inspired by [Nap](https://github.com/maaslalani/nap)

## References
- [nap - code snippet manager for your terminal](https://github.com/maaslalani/nap)
- [Charm CLI - Nap: your new Leetcode BFF](https://www.youtube.com/watch?v=G1U4e1u-Sfc)
- [SQLite](https://www.sqlite.org/index.html)
- [Bubble Tea - Go framework for building TUI](https://github.com/charmbracelet/bubbletea)
