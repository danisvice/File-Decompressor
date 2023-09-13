## Rust Archive Extractor

This is a Rust-based command-line tool for extracting files from zip archives. It provides a simple and efficient way to extract files from zip archives and preserves their directory structure.

## Features

- Extract files from zip archives.
- Preserve the directory structure of the archived files.
- Display file comments, if available.

## Prerequisites

Before you can use this tool, make sure you have the following installed:

- Rust: You can install Rust from [https://www.rust-lang.org/](https://www.rust-lang.org/).

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/rust-archive-extractor.git
   ```

2. Change into the project directory:

   ```bash
   cd rust-archive-extractor
   ```

3. Build the project:

   ```bash
   cargo build --release
   ```

## Usage

To extract files from a zip archive, run the following command:

```bash
./target/release/rust-archive-extractor <filename>
```

Replace `<filename>` with the path to your zip archive.

Example:

```bash
./target/release/rust-archive-extractor example.zip
```

## Output

The tool will display the following information for each extracted file:

- File index.
- Extracted file path.
- File size (in bytes).
- File comment (if available).

Directory structure will be preserved during extraction.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

This tool is powered by the Rust programming language and uses the `zip` crate for zip archive handling.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or create a pull request.

## Author

- Your Name
- GitHub: [https://github.com/yourusername](https://github.com/yourusername)

## Disclaimer

This tool is provided as-is without any warranty. Use it at your own risk.

---

*Note: This README is a template and should be customized to fit your project's specific details.*
