
# Pegasus-Allink

Pegasus-Allink is a Python script designed to extract all hyperlinks from a given webpage and save them to a file named `myLinks.txt`.

## Features

- Extracts all hyperlinks from a provided URL.
- Saves the first 10 extracted hyperlinks to `myLinks.txt`.
- Automatically handles URLs with or without the `http` or `https` scheme.

## Requirements

- Python 3.x
- `requests` library
- `beautifulsoup4` library

## Installation

To install the required libraries, you can use `pip`:

```sh
pip install requests beautifulsoup4
```

## Usage

1. Clone or download the repository.
2. Navigate to the directory containing `pegasus-allink.py`.
3. Run the script:

```sh
python pegasus-allink.py
```

4. When prompted, enter the URL of the webpage you want to extract links from.

## Example

```sh
Enter Link: example.com
```

This will fetch the content of `https://example.com` (if `http` or `https` is not specified, `https://` is assumed), extract all hyperlinks, and save the first 10 links to `myLinks.txt`.

## Notes

- The script appends the extracted links to `myLinks.txt` by default. To overwrite the file each time the script is run, change the file mode from `'a'` to `'w'` in the `open` function.
- Ensure that the entered URL is valid and accessible.

## License

This project is licensed under the MIT License.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## Author

Letda Kes Dr. Sobri - [sobri3195@gmail.com](mailto:sobri3195@gmail.com)
