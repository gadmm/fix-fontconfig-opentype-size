## Synopsis

Fontconfig mixes fonts that have the same families but different
opentype 'size', and chooses one variant at random for you. This
configuration file fixes the situation by assigning different families
to different sizes.

Fonts fixed at the moment:
- Arno Pro
- EB Garamond
- Latin Modern

## Install

Install as `/etc/fonts/local.conf`.

## Use

Your software now displays a different font name for each 'size'.

## License

GNU Affero GPL v3.0. See `LICENSE`.

