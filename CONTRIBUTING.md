Thanks for contributing to xz/fonts!

## Guidelines
- Only open-source fonts will be accepted
- Make sure the font's license allows republication!

## Contributing

Font stylesheets are stored in `/serve`, and font files are stored in `/serve/src`.

Adding a font:

1. Upload all weights to https://transfonter.org/. The format you upload them in doesn't matter
2. Use these settings: ![transfonter settings](https://i.imgur.com/8eefUiF.png)
3. Press "Convert" and download the archive
4. Clone the GitHub repository to your device: `git clone https://github.com/xz/fonts.git`
5. Open the archive downloaded from transfonter
6. Create a new folder in `/fonts/serve/src` for the name of the font. Only lowercase letters/numbers and dashes, please! I'll use `font-name` in this example.
7. Move the `.woff` and `.woff2` files to `/fonts/serve/src/font-name`
8. Move the `.css` file to `/fonts/serve` and rename to `font-name.css`
9. Open the `.css` file. Do a find-and-replace for all instances of `url('`, and replace it with `url('src/font-name/`. Use the same font name as above.
