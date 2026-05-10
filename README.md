# lucide-mendix

Downloads `lucide.ttf` and generates a Mendix icon import file.

## Prerequisites

- Node.js
- `git` available on your PATH

## Usage

Run without installing:

```sh
npx lucide-mendix
```

Or install globally and run:

```sh
npm install -g lucide-mendix
lucide-mendix
```

## Output

Two files are written to the current directory:

| File | Description |
|------|-------------|
| `lucide.ttf` | Lucide TrueType font file |
| `lucide-mendix-import.txt` | Semicolon-delimited icon mappings for Mendix import |

Each line in `lucide-mendix-import.txt` follows the format:

```
hexCode;iconName;tags
```

Example:

```
e908;activity;bar chart fitness graph
```

Icons are sorted alphabetically by name.

## License

MIT
