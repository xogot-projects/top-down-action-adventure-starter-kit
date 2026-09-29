# Pinned add-ons for Godot 4.7.2

- Dialogic [2.0-alpha-14](https://github.com/dialogic-godot/dialogic/tree/2.0-alpha-14): the version previously required by this project. Both `_get` overrides now return null on fall-through; the name-label `_set` override returns false for unhandled properties. Main-screen editor cleanup no longer removes an unregistered bottom-panel dock.
- Beehave [v2.9.3](https://github.com/bitbrain/beehave/tree/v2.9.3): message capture and delivery require an active EngineDebugger, so standalone/headless runs work.

Both add-ons retain their upstream MIT licenses. Only the upstream `addons` directories and licenses are included; generated `.godot` data is excluded.

Archive SHA-256 values:
- dialogic: `ef4ee2b31048adc169df5ce37305b8c6e7c81f64f9c95326f14adb70802cd630`
- beehave: `6299d8c42a29c2a44fabb2a43113067997fac5908c7748645da6958329c9951c`

Vendored text is normalized to remove trailing whitespace and extra blank lines at EOF so the upgrade diff passes `git diff --check`.
