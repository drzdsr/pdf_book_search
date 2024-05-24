
PDF Book Search
Welcome to the PDF Book Search! This application allows users to search through a collection of PDF files efficiently. The application creates an index of the PDF files and uses this index to perform fast searches.

Table of Contents
Requirements
Installation
Usage
Functions
License
Requirements
To run this application, you need the following:

Python 3.x
Required Python packages (listed in requirements.txt)
Installation
Clone the repository:

bash
Copy code
git clone <repository_url>
cd pdf_book_search
Install the required packages:

bash
Copy code
pip install -r requirements.txt
Ensure you have the PDF files you want to index and search through in a directory.

Usage
To use the PDF Book Search, follow these steps:

Run the script:

bash
Copy code
python main.py
Follow the on-screen prompts:

You will be asked to specify the directory containing the PDF files.
You will also need to specify the directory where the index will be stored.
The application will create an index of the PDF files. This process may take some time depending on the number and size of the PDF files.

Once the index is created, the application will launch a GUI for searching through the PDFs.

Functions
Here is a detailed description of the main functions in the application:

get_pdf_dir()
Prompts the user to specify the directory containing the PDF files.

get_index_dir()
Prompts the user to specify the directory where the index will be stored.

pdf_files_list(pdf_dir)
Generates a list of all PDF files in the specified directory.

index_files_list(index_dir)
Generates a list of all index files in the specified directory.

get_index(pdf_dir, pdf_files_list, index_files_list)
Creates an index of the PDF files.

final_index_file(index_dir, index)
Stores the final index in the specified directory.

index_file_sort(index_dir, index_files_list)
Sorts the index files in the specified directory.

create_word_search_app(index_dir)
Launches the GUI for searching through the PDFs using the created index.

License
This project is licensed under the MIT License. See the LICENSE file for details.