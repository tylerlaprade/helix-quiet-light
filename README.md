# Quiet Light for Helix

A port of VSCode's built-in [Quiet Light](https://github.com/microsoft/vscode/tree/main/extensions/theme-quietlight)
theme to the [Helix editor](https://helix-editor.com).

<img width="3456" height="2234" alt="image" src="https://github.com/user-attachments/assets/fe7ca20c-7403-4348-ba01-c1923ea0f7f4" />
<img width="3456" height="2234" alt="image" src="https://github.com/user-attachments/assets/fc0b2c18-9310-4afb-a56e-d8f4b12a5194" />
<img width="3456" height="2234" alt="image" src="https://github.com/user-attachments/assets/e73350b0-0e03-4532-a42f-24b40b891d91" />
<img width="3456" height="2234" alt="image" src="https://github.com/user-attachments/assets/3b1ce62a-6d83-481e-b5fc-ef89c6315606" />

## Install

Drop `quiet_light.toml` into your Helix themes directory:

```sh
curl -fsSL https://raw.githubusercontent.com/tylerlaprade/helix-quiet-light-theme/main/quiet_light.toml \
  -o ~/.config/helix/themes/quiet_light.toml
```

Then in `~/.config/helix/config.toml`:

```toml
theme = "quiet_light"
```

Or activate live: `:theme quiet_light`.

## Upstream PR

An upstream PR to bundle this theme with Helix itself is in flight:
[helix-editor/helix#TBD](https://github.com/helix-editor/helix/pulls?q=quiet+light).
Once merged, this repo becomes redundant for Helix ≥ that release — install directly
from Helix's built-in themes.

## Credits

- Original VSCode theme: [Microsoft / occlure](https://github.com/microsoft/vscode/tree/main/extensions/theme-quietlight)
- Original TextMate theme: Ian Beck
- Helix port: Tyler Laprade

## License

MIT — see [LICENSE](LICENSE).
