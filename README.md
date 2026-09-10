# tfm-palette

Command palette for [tfm](https://github.com/anomalyco/tfm-tui) (terminal file manager):
a fuzzy list over everything dispatchable — all core keybind actions plus
every installed plugin's commands.

## Install

In tfm: `esc` → Plugins → `add plugins` → **Add from git URL…** → paste:

```
https://github.com/clarkarch/tfm-palette
```

Confirm, and the `palette` category appears in the Plugins view. No restart needed.

Manual install: copy `palette.ts` to `~/.config/tfm/plugins/palette/palette.ts`.

## Use

- Plugins view → `Command palette…` row, or
- right-click any file → `Command palette…`.

Updates: the plugin's `Update from git` row pulls the latest.

## License

MIT — see [LICENSE](LICENSE).
