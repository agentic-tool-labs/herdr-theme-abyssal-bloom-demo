# Abyssal Bloom (demo)

A theme published for [Theme Studio](https://github.com/agentic-tool-labs/herdr-theme-studio), the
[Herdr](https://herdr.dev) app's theme editor. It exists to test importing from GitHub.

- **abyssal-bloom-demo**: deep-sea teal over art from *Abyssal Bloom: Ocean Drift*. A branded theme,
  with App Store, Google Play and Mac App Store links.

## Using them

In Theme Studio, open **Import** and either click **Browse themes** (this repo carries the topic
`herdr-mod-theme-studio`) or paste a link to this repo or to its `.json` file into the
GitHub field. It brings its whole look: colors, glass, fonts, cursor and agents list.

## Publishing your own

Save a theme in Theme Studio, then run its publishing script:

```sh
python3 ~/.config/herdr-app/mods/theme-studio/tools/publish-theme.py my-theme \
  --description "What it looks like" --author "You" --url https://example.com
```

Push the folder it writes to a GitHub repo and add the topic `herdr-mod-theme-studio`. Store links
(`--ios`, `--android`, `--macos`) make it a branded theme. The file format is described at the top
of `publish-theme.py`.

The Abyssal Bloom picture is © Bear Poppa Studios.
