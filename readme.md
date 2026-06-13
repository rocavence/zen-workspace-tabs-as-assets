# Workspace Tabs as Assets — a Zen Browser Mod

Pinned tabs in a workspace are **assets**, not disposable tabs. This mod removes
the hover `×` close button on **pinned tabs** so they can't be dismissed by an
accidental click. Normal (unpinned) tabs are unaffected and keep their `×`.

![preview](./image.png)

## Closing a pinned tab on purpose

Right-click → **Close Tab**, or **middle-click** the tab.

## Optional: also stop cmd+w from closing pinned tabs

Zen Mods are CSS-only and can't rebind keys. If you want cmd+w to leave pinned
tabs alone, set `zen.pinned-tab-manager.close-shortcut-behavior` in
`about:config` to e.g. `reset-unload-switch` — Zen will reset/unload the pinned
tab instead of closing it, while cmd+w keeps working normally on other tabs.

## Install (local)

Copy `chrome.css` and `readme.md` into a folder under your Zen profile's
`chrome/zen-themes/<uuid>/`, add an entry for it in `zen-themes.json`, and
restart Zen.

## License

[CC BY-NC-SA 4.0](./LICENSE).
