# Noto Nushu

[![][Fontbakery]](https://notofonts.github.io/nushu/fontbakery/fontbakery-report.html)
[![][Universal]](https://notofonts.github.io/nushu/fontbakery/fontbakery-report.html)
[![][GF Profile]](https://notofonts.github.io/nushu/fontbakery/fontbakery-report.html)
[![][Outline Correctness]](https://notofonts.github.io/nushu/fontbakery/fontbakery-report.html)
[![][Shaping]](https://notofonts.github.io/nushu/fontbakery/fontbakery-report.html)

[Fontbakery]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fnotofonts%2Fnushu%2Fgh-pages%2Fbadges%2Foverall.json
[GF Profile]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fnotofonts%2Fnushu%2Fgh-pages%2Fbadges%2FGoogleFonts.json
[Noto Profile]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fnotofonts%2Fnushu%2Fgh-pages%2Fbadges%2FNotoFonts.json
[Outline Correctness]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fnotofonts%2Fnushu%2Fgh-pages%2Fbadges%2FOutlineCorrectnessChecks.json
[Shaping]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fnotofonts%2Fnushu%2Fgh-pages%2Fbadges%2FShapingChecks.json
[Universal]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fnotofonts%2Fnushu%2Fgh-pages%2Fbadges%2FUniversal.json

### Which Noto fonts should I use for the Nüshu script?

Noto has two font families for the Nüshu script:

- Noto Sans Nushu, an unmodulated design in one weight, with a simplified, modernized skeleton and relatively large counters. It is suitable for shorter texts, especially in smaller font sizes and user interface contexts.

- Noto Traditional Nushu, an unmodulated design in three weights, with a more calligraphic skeleton and a more compact appearance. It is suitable for longer texts, especially those set in medium font sizes, and for headlines. Traditional Nushu was designed in China, and has support for vertical typesetting.

## Building

Fonts are built automatically by GitHub Actions - take a look in the "Actions" tab for the latest build.

If you want to build fonts manually on your own computer:

* `make build` will produce font files.
* `make test` will run [FontBakery](https://github.com/googlefonts/fontbakery)'s quality assurance tests.
* `make proof` will generate HTML proof files.

The proof files and QA tests are also available automatically via GitHub Actions - look at https://notofonts.github.io/nushu.

For information on how to work on Noto fonts, how the build process
works and how to maintain it, see [the README file of the
notofonts.github.io
repository](https://github.com/notofonts/notofonts.github.io/blob/main/README.md)

## License

This Font Software is licensed under the SIL Open Font License, Version 1.1.
This license is available with a FAQ at
https://scripts.sil.org/OFL
