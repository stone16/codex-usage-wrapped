# Codex Wrapped

Generate a Spotify Wrapped-style summary of your Codex CLI usage and a shareable PNG.

<img width="1800" height="1840" alt="codex-wrapped" src="https://github.com/user-attachments/assets/8ac6faf1-fab3-4157-be2c-10d163312c2f" />


## Quick Start

```bash
npx codex-usage-wrapped
```

## Outputs

- `./codex-wrapped/codex-wrapped.png` — shareable image
- `./codex-wrapped/index.html` — dashboard view
- `./codex-wrapped/data.json` — aggregated usage data

Use `--out` to change the output directory and `--image` to override the PNG path:

```bash
npx codex-usage-wrapped --out ./my-wrapped --image ./my-wrapped/share.png
```

## Configuration

By default, Codex Wrapped reads `codex-wrapped.config.yaml`. Override the path with:

```bash
npx codex-usage-wrapped --config ./custom-config.yaml
```

See `codex-wrapped.config.yaml` for available options.
