# Release notes template

Copy the section below into a new GitHub Release description. Replace `VERSION` and the bracketed prompts, and remove sections that do not apply. Describe only changes included in that build.

Use a matching release tag such as `v0.1.2` for app version `0.1.2`.

---

## Streamr vVERSION

[One short sentence describing the main improvement in this release.]

### Highlights

- [A new feature or meaningful improvement.]
- [Another confirmed change.]

### Fixes

- [The user-visible problem that was fixed.]

### Download

Choose the installer for your computer from **Assets** below:

| Architecture | Installer |
| :--- | :--- |
| Intel / AMD 64-bit | `Streamr-Setup-VERSION-x64.exe` |
| Windows on ARM | `Streamr-Setup-VERSION-arm64.exe` |

Requires Windows 10 or Windows 11 and an internet connection for catalog browsing and playback.

### Updating

Export a backup from **Settings → Export JSON**, close Streamr, and run the new installer.

[State whether this version supports automatic update checks. Do not claim automatic updates work until the published update path has been tested.]

### Known issues

- [List confirmed limitations specific to this version, or remove this section.]

---

<details>
<summary><strong>Publishing checklist — remove from the release description</strong></summary>

- Match the application version, release tag, installer filenames, and notes.
- Attach the tested x64 and ARM64 installers.
- Once the updater is integrated, attach its generated metadata and matching `.blockmap` files. Preserve generated filenames and checksums.
- Verify that each architecture receives its matching installer and update metadata.
- State signing and update support accurately for this version.
- Add the confirmed changes to `CHANGELOG.md`.
- Upload only release artifacts and public documentation. Exclude source code, `.env` files, credentials, and personal backups.
- Publish the release only after its assets are ready.

</details>
