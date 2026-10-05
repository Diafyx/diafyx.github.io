# diafyx.github.io

Source for the Diafyx studio website: **https://diafyx.github.io**

A static site: plain HTML and CSS, with no build step, no JavaScript and no dependencies.

## Structure

| Path | Contents |
|---|---|
| `site/` | Everything that gets published |
| `site/assets/` | Stylesheet, self-hosted font, logo and social preview image |
| `.github/workflows/pages.yml` | Checks local links, then deploys `site/` to GitHub Pages on every push to `main` |

## Preview locally

The site uses root-relative paths, so serve it rather than opening the file directly:

```bash
python3 -m http.server 8000 --directory site
```

Then open http://localhost:8000.

## Contributing

Changes go through a pull request to `main`. See the organization's [contributing guide](https://github.com/Diafyx/.github/blob/main/CONTRIBUTING.md).

## License

The code is released under the [MIT License](LICENSE). The Diafyx name and logo are not covered by that license.

The [Sora](https://github.com/sora-xor/sora-font) typeface is used under the [SIL Open Font License 1.1](site/assets/fonts/OFL.txt).
