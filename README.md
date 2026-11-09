# Teal

A [Spicetify](https://spicetify.app) theme for Spotify: Catppuccin Mocha with a teal accent.

- floating, rounded panels on a dark background;
- playlist and album headers without a band: a soft glow from the cover;
- the same rounded corners for covers, lists, fields and buttons;
- translucent, blurred menus; thin scrollbars; a focus ring for the keyboard.

![Teal](preview.png)

## Install

From the [Marketplace](https://github.com/spicetify/marketplace), or by hand:

```sh
mkdir -p ~/.config/spicetify/Themes/Teal
cp user.css color.ini ~/.config/spicetify/Themes/Teal/
spicetify config current_theme Teal color_scheme Teal
spicetify apply
```

The first time, Spicetify needs `spicetify backup apply`.

## After a Spotify update

Spotify renames some of its classes: if a part of the theme stops applying, run
`spicetify backup apply`. The selector that changed is then to be updated in `user.css`.
