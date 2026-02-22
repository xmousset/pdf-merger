# PDF Merger

A simple Python GUI application to merge multiple PDF files using Tkinter and PyPDF2.\
The app provides two main options:

- **Select Files** : Opens a dialog to pick multiple PDF files to merge.
- **Select Folder** : Opens a dialog to pick a folder; all PDFs in that folder will be merged.

After selection, you are prompted to choose the output file location. The selected PDFs are merged into a single PDF at the chosen location.

## Information
Either use the application or run the `main.py` python code after installing PyPDF2.
The application is created using the following command in the appropriate directory:
``` powershell
pyinstaller --onefile --windowed --icon=res/pdf_merger.ico main.py
```
