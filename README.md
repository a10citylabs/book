# A10City Movement

Quest for digital authenticity

## Local Development

### Prerequisites

- [Pandoc](https://pandoc.org/installing.html)

### Build ePub locally

```bash
pandoc -o reader/book.epub metadata.yaml content/*.md
```

Then open `reader/index.html` in a browser.

