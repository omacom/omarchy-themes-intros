# Omarchy theme intros

The short intro videos that play before the built-in Omarchy themes' background stills. They ship as the `omarchy-themes-intros` package, which installs `<theme>/<name>.mp4` here to `/usr/share/omarchy/themes/<theme>/backgrounds/intros/<name>.mp4`.

An intro plays before the still with the same name in that theme's `backgrounds/` in [omacom/omarchy](https://github.com/omacom/omarchy), so `lupine/01-cherry-blossom-bokeh.mp4` belongs to `themes/lupine/backgrounds/01-cherry-blossom-bokeh.webp`. See `docs/theming.md` there for how intros play and how long they should be.

To add or change an intro, open a pull request here. Once it merges, cut a release tagged with the date, `vYYYY.MM.DD` (or `vYYYY.MM.DD.1` for a second one that day). [omacom/omarchy-pkgs](https://github.com/omacom/omarchy-pkgs) picks the release up and updates `omarchy-themes-intros` to it.
