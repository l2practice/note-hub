# Note Hub

A small, browser-based notebook for collecting notes, ideas, and to-dos. The interface is in Vietnamese and is designed around the familiar notebook → section → page structure.

## Run locally

The app has no build step or package dependencies. From this directory, run:

```sh
python3 -m http.server 4173
```

Then open <http://localhost:4173>.

## Features

- Create notebooks, sections, and pages.
- Edit formatted notes with headings, emphasis, lists, highlights, and a quick to-do mark.
- Search note titles and text; sort pages by their last edit.
- Auto-save to `localStorage` in the current browser profile.
- Responsive desktop and mobile navigation, keyboard search shortcut (`⌘K` / `Ctrl+K`), and reduced-motion support.

## Storage and privacy

This is a static client-side app. Note content stays in the browser's local storage on the device and browser profile where it was written. There is no account, server database, cloud sync, encryption, or automatic backup. Clearing browser data can delete notes. A hosted copy on another origin has a separate local store; it will not automatically share notes with a local copy or another device.

The app starts with a synthetic welcome note. Do not use it as the sole copy of important information.
