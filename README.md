[![][Fontbakery]](https://Nsl106.github.io/T9432/fontbakery/fontbakery-report.html)
[![][Universal]](https://Nsl106.github.io/T9432/fontbakery/fontbakery-report.html)
[![][GF Profile]](https://Nsl106.github.io/T9432/fontbakery/fontbakery-report.html)
[![][Outline Correctness]](https://Nsl106.github.io/T9432/fontbakery/fontbakery-report.html)
[![][Shaping]](https://Nsl106.github.io/T9432/fontbakery/fontbakery-report.html)

[Fontbakery]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FNsl106%2FT9432%2Fgh-pages%2Fbadges%2Foverall.json
[GF Profile]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FNsl106%2FT9432%2Fgh-pages%2Fbadges%2FGoogleFonts.json
[Outline Correctness]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FNsl106%2FT9432%2Fgh-pages%2Fbadges%2FOutlineCorrectnessChecks.json
[Shaping]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FNsl106%2FT9432%2Fgh-pages%2Fbadges%2FShapingChecks.json
[Universal]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FNsl106%2FT9432%2Fgh-pages%2Fbadges%2FUniversal.json

T9432 is a pixelated typecafe based on [Silkscreen](https://github.com/googlefonts/silkscreen/) designed originally for use by FRC Team 8-Bit


![](documentation/image.png)


## Building

Fonts are built automatically by GitHub Actions - take a look in the "Actions" tab for the latest build.

If you want to build fonts manually on your own computer:

* `make build` will produce font files.
* `make test` will run [FontBakery](https://github.com/googlefonts/fontbakery)'s quality assurance tests.
* `make proof` will generate HTML proof files.

The proof files and QA tests are also available automatically via GitHub Actions - look at https://Nsl106.github.io/T9432.

## Changelog

**26 October 2023. Version 1.000**
- First version!

## License

This Font Software is licensed under the SIL Open Font License, Version 1.1.
This license is available with a FAQ at
https://scripts.sil.org/OFL

## Repository Layout

This font repository structure is inspired by [Unified Font Repository v0.3](https://github.com/unified-font-repository/Unified-Font-Repository), modified for the Google Fonts workflow.
