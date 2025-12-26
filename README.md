# PDF Merger

A simple Python GUI application to merge multiple PDF files using Tkinter and PyPDF2.\
The app provides two main options:

- **Select Files** : Opens a dialog to pick multiple PDF files to merge.
- **Select Folder** : Opens a dialog to pick a folder; all PDFs in that folder will be merged.

After selection, you are prompted to choose the output file location. The selected PDFs are merged into a single PDF at the chosen location.

## Installation
1. Clone or download this repository.
2. Install the required package:
   ```bash
   pip install PyPDF2
   ```

## Code Structure
- `select_files()` : Lets the user select multiple PDF files and then merge them in ascending order.
- `select_folder()` : Lets the user select a folder and then merge all PDFs inside in ascending order.
- `merge_pdf(pdf_paths)` : Merges the given list of PDF files in ascending order and prompts for the output location.
- `main_tk()` : Sets up the GUI and handles user interaction.
