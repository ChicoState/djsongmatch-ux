# Sketches

![UX Team's different pages on DJ Song Match](sketch-1.png)

# Home Page
- The Home Page is the starting page the user is presented with when they start the app.
- For the icons for YouTube/Spotify/Filesystem, the currently selected one is the largest/longest

# Loading Page
After the user selects a input type and source, a loading page consumes the entire screen, with information about current progress in analysis.

# Main Page
- The main page displays playlist/song information in a table
- Provides options for "Locking" a song in position (doesn't move from 2nd song in list when generating a playlist order)
- Option to drag and drop songs to change their order manually
- Delete button "removes" songs from playlist (doesn't actually remove, just grays out, moves it to bottom, and doesn't consider it in algorithm with option to add it back if the user wants to)
- Table has a scrollbar

## Undo, Redo, History
- Goes back and forth between different generated playlist orders
- Keeps a history that lasts for the current session

## Main Page Dropdown
- Initially hidden menu
- Appears when `SORT` button at the top is pressed
- Menu pushes the table down, doesn't cover it

# Preset Menu
- Options to select different presets for combinations of metrics like key, bpm, energy, etc.
- Also has option to save a custom preset
- Custom presets will have a scrollbar in case user saves a lot of presets
