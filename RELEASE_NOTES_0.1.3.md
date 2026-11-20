# Streamr 0.1.3

### Window controls

- Removed the native minimize, maximize, and close buttons from the top of the app.
- Added app fullscreen and close controls beside the theme switch in the sidebar.
- Added keyboard shortcuts for app fullscreen and closing Streamr.

### Keyboard shortcuts

- Added a shortcut reference in Settings.
- Use Ctrl/Cmd+K to focus catalog search and `/` to open Search.
- Use Ctrl/Cmd+1–5 to open Discover, Movies, TV Series, Anime, or My Library.
- Use F to toggle player fullscreen and N to play the next episode.
- Use Ctrl/Cmd+Shift+F to toggle app fullscreen, Ctrl/Cmd+Shift+Q to close Streamr, and Esc to exit app fullscreen or close mobile navigation.
- Shortcuts pause while typing. Embedded video providers may handle their own keys while focused.

### Series and anime playback

- Episode changes keep the watch page and player mounted instead of remounting the whole page.
- App fullscreen persists while the next episode loads, including transitions into another season.
- Per-episode playback progress resets correctly and resumes only when that episode has saved progress.

Upgrade from v0.1.2; your existing library and window preferences are kept.
