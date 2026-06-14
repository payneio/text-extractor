# text-extractor

Extract content and metadata from text files.

Reads a text file and writes a JSON object containing its content and metadata
(filename, size, creation and modification times) to stdout.

## Usage

```bash
text-extractor document.txt       # Extract from a file
cat file.txt | text-extractor     # Read from stdin
```

## Install

```bash
uv tool install --editable .
```

## License

Copyright (C) 2026 Paul Payne. Licensed under the GNU AGPLv3 — see [LICENSE](LICENSE).
