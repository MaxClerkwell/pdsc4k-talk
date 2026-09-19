# Everything, Everywhere, All at Once

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.22850096.svg)](https://doi.org/10.5281/zenodo.22850096)

Keynote on automated data collection, held at the Practical Data Science
Conference (PDSC4k) in 2026.

The talk walks through the full path from the measurement in the field to the
analysed result in four zones, with one owner per box: acquisition at the edge,
transport, storage, and analysis.

## Building

```sh
make                              # builds main.pdf (English)
latexmk -pdf main-de.tex          # builds the German version
```

Requires a TeX Live installation with `latexmk` and the `beamer` class.

Pushing a `v*` tag builds the slides in CI and attaches the PDF to the
corresponding GitHub release.

## Citing

The DOI badge above always resolves to the latest version. Each tagged release
also gets its own DOI on the Zenodo record, for citing an exact state.

## Author

Stephan Bökelmann, [maxclerkwell.tech](https://maxclerkwell.tech)

## License

[CC BY 4.0](LICENSE)
