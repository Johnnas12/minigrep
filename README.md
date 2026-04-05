# minigrep

`minigrep` is a small Rust command-line tool that searches for a query string in a text file.

## Usage

```bash
cargo run -- <query> <file_path>
```

Example:

```bash
cargo run -- body poem.txt
```

Set `IGNORE_CASE=1` to search without case sensitivity:

```bash
IGNORE_CASE=1 cargo run -- body poem.txt
```