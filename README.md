To create a `README.md` file with the same formatting, follow these steps:

1. Open a text editor of your choice (e.g., VS Code, Sublime Text, Notepad++).
2. Copy the content below into the text editor.
3. Save the file as `README.md` in your `pdf_book_search` repository.

```markdown
# PDF Book Search

Welcome to the PDF Book Search! This application allows users to search through a collection of PDF files efficiently. The application creates an index of the PDF files and uses this index to perform fast searches.

## Table of Contents

- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Functions](#functions)
- [License](#license)

## Requirements

To run this application, you need the following:

- Python 3.x

## Installation

1. Clone the repository:

   ```bash
   git clone <https://github.com/drzdsr/pdf_book_search.gitrl>
   cd pdf_book_search
   ```

2. Install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

3. Ensure you have the PDF files you want to index and search through in a directory.

## Usage

To use the PDF Book Search, follow these steps:

1. Run the script:

   ```bash
   python main.py
   ```

2. Follow the on-screen prompts:

   - You will be asked to specify the directory containing the PDF files.
   - You will also need to specify the directory where the index will be stored.

3. The application will create an index of the PDF files. This process may take some time depending on the number and size of the PDF files.

4. Once the index is created, the application will launch a GUI for searching through the PDFs.

## Functions

Here is a detailed description of the main functions in the application:

### `get_pdf_dir()`

Prompts the user to specify the directory containing the PDF files.

### `get_index_dir()`

Prompts the user to specify the directory where the index will be stored.

### `pdf_files_list(pdf_dir)`

Generates a list of all PDF files in the specified directory.

### `index_files_list(index_dir)`

Generates a list of all index files in the specified directory.

### `get_index(pdf_dir, pdf_files_list, index_files_list)`

Creates an index of the PDF files.

### `final_index_file(index_dir, index)`

Stores the final index in the specified directory.

### `index_file_sort(index_dir, index_files_list)`

Sorts the index files in the specified directory.

### `create_word_search_app(index_dir)`

Launches the GUI for searching through the PDFs using the created index.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Feel free to contribute to this project by submitting issues or pull requests. Happy searching!
```
