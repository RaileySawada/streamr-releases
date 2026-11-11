# What's new in Streamr

Changes to the desktop app, collected in one place.

For installers and version-specific notes, visit **[Releases](../../releases)**.

---

## 0.1.2 · Fullscreen playback

- Fixed fullscreen playback to fill the window, hide Streamr headings, and exit with Esc.
- Kept the fullscreen guidance visible for 3.5 seconds.
- Made the Next episode prompt compact and show it only during the final 30 seconds when the player reports progress.
- Added Railey Dela Peña as the publisher in Windows installed-app details.
- Kept the existing app identity and local library across the update.

## 0.1.1 · Player and updates

- Background update downloads with a dismissible notification and user-controlled restart.
- A changelog dialog shown once per installed version.
- Fixed Electron player fullscreen and compacted the season/search controls.
- Fixed Everything search requests, including those from installed v0.1.0 apps.
- Moved the episode queue and season selection beside the player for episodic titles.
- Grouped watchlist, watched status, and server selection below the player.
- Kept the synopsis visible and collapsed additional title details by default.
- Removed duplicate synopsis content and adapted the watch layout for narrow windows.

## 0.1.0 · Initial release

- Automatic checks for stable releases after startup and every six hours in installed Windows builds.
- Settings controls to check, download, and restart to install an update.
- Download progress and clear messages for unavailable releases or connection problems.
- Separate update metadata for x64 and ARM64 installers.
- Public release downloads; the source repository can remain private.

Install this first release manually. The checker requires the release assets and matching metadata to be published.

### Discover more

- Combine genre and year filters for movies, TV series, and anime.
- Sort by popularity, highest rating, newest releases, or oldest releases.
- Browse additional results with infinite scroll.
- Explore expanded TMDB information, including cast, crew, production details, country ratings, images, and reviews when available.

### Settle in

- Choose between three playback providers: VSEmbed, VidLink, and VidSrc.
- Save individual titles' playback server selections.
- Continue watching from saved progress when the provider reports playback updates.
- Export and import your watchlist, history, progress, searches, and preferences.

### Make it yours

- Choose light, dark, or system appearance.
- Use a circular theme reveal on supported graphics configurations, with an immediate change for reduced motion or software graphics.
- Keep your preferred window position, normal size, maximized state, and fullscreen state across launches.
- Install using a compact Windows setup wizard with Streamr branding.

### Release notes

- Windows 10 and Windows 11 installers are available for x64 and ARM64 builds.
- Installers are currently unsigned.
- Automatic checks are included; downloads and installation require your action.
- Title information and playback features depend on the external services providing them.

---

Use [the release notes template](./RELEASE_TEMPLATE.md) when publishing the next version. Add its confirmed changes above this entry.
