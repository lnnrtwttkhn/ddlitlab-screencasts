# DDLitLab Screencasts

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

Screencasts of the teaching project "Version Control with Git", funded and supported by the "Digital and Data Literacy in Teaching Lab" initiative at University of Hamburg.

The screencasts are **[available from UHHCloud](https://cloud.uni-hamburg.de/s/dXNSwSpeQztXxpH)** (NextCloud).

## Screecasts

Screencasts were recorded with size 1260 x 100 on macOS using the [Screenshot toolbar](https://support.apple.com/en-us/102618).

- Screencast of the "Version Control Book"
- Screencast of the exercises in the "Version Control Book"
- Screencast of the Version Control Course website
- Screencast of Lennart's `recipes` repository
- Screencast of Matteo Carpi's pull request in Lennart's `recipes` repository

## Configuration

This repository is a DataLad dataset and has a WebDAV sibling:

```bash
datalad create-sibling-webdav \
  --dataset . \
  --name uhhcloud \
  --mode filetree \
  'https://cloud.uni-hamburg.de/remote.php/dav/files/bbc5706/ddlitlab-screencasts'
```

## License

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

## Contact

[Lennart Witttkuhn](mailto:lennart.wittkuhn@tutanota.com)
