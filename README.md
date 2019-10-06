# Materia Sound Theme

Materia Sound Theme is a freedesktop sound theme using [Google's Material sound resources](https://material.io/design/sound/sound-resources.html).
It follows the [Material sound guidelines](https://material.io/design/sound).

## Installation

You can build and install it using Meson.

```bash
meson "build" --prefix=/usr
sudo ninja -C "build" install
```

The default prefix is `/usr`, but you can specify a different prefix such as `$HOME/.local`.

## Enable more sounds

To enable input feedback sounds on GNOME, run:

```bash
gsettings set org.gnome.desktop.sound input-feedback-sounds true
```

> Note: This theme doesn't provide all available sounds to avoid distractions.

## Contributing

Suggestions are very welcome! Feel free to submit an issue to share your ideas.

## License

This project is licensed under [GPLv3](https://www.gnu.org/licenses/gpl-3.0.html).

## Attribution

All audio files in this repository are attributed to [Google](https://www.google.com/), and [the original set of audio files](https://material.io/design/sound/sound-resources.html) is licensed under [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/legalcode).
In this project, the original set is remixed while changing the directory structure and deleting unnecessary files.
