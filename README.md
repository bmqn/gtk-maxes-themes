# gtk-maxes-themes

A snap that exports Max's custom GTK themes, icons and sounds.

## How To - Firefox

```bash
snapcraft
snap install gtk-maxes-themes_*.snap --dangerous
snap connect firefox:gtk-3-themes gtk-maxes-themes:gtk-3-themes
snap connect firefox:icon-themes gtk-maxes-themes:icon-themes
snap connect firefox:sound-themes gtk-maxes-themes:sound-themes
```
