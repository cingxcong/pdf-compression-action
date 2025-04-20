# PDF Compression Action by URL

A GitHub Actions workflow to compress PDF files by downloading them from a URL and compressing them using Ghostscript, with options for compression level and target size.

## How It Works

- Provide a PDF URL.
- Select a compression level (`screen`, `ebook`, `printer`, `prepress`).
- Set a target file size in KB.
- The workflow will download, compress, and check if the size meets your target.
- If it does, it uploads the compressed PDF as an artifact.

## Usage

1. Fork this repository.
2. Go to the `Actions` tab.
3. Choose `Compress PDF by URL`.
4. Click `Run workflow`.
5. Enter your inputs.
6. Download the compressed PDF from the run artifacts.

## Requirements

- Uses Ghostscript on `ubuntu-latest` runner.
- Publicly accessible direct PDF URL.

## License

MIT
