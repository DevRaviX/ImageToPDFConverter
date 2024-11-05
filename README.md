## About the Project
```markdown
# Image to PDF Converter

A simple tool to convert selected images into a PDF file using Python and Tkinter. This utility allows you to choose multiple images and save them as a single PDF document, making it perfect for organizing scans, photos, or other image collections.

## Features
- **Select multiple images** (JPEG, PNG, GIF) and convert them into a single PDF.
- **Easy-to-use interface** built with Tkinter.
- **File dialog** for selecting images and saving the output PDF file.

## Requirements
To run this project, you’ll need:
- Python 3.x
- The following Python packages:
  ```plaintext
  img2pdf
  tkinter  # Usually included with Python
  ```

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/DevRaviX/ImageToPDFConverter.git
   ```
2. Navigate into the project directory:
   ```bash
   cd ImageToPDFConverter
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Run the script:
   ```bash
   python image_to_pdf_converter.py
   ```
2. Select the images you want to include in the PDF.
3. Choose a location and name for the output PDF file.
4. The PDF will be saved at your specified location.

## Code Overview
The main functions in the script are:
- `select_images()`: Opens a dialog to select multiple image files.
- `choose_pdf_save_location()`: Opens a dialog to specify the save location for the output PDF.
- `create_pdf_from_images()`: Converts the selected images into a single PDF.


## License
This project is open-source and available under the [MIT License](LICENSE).

## Author
Developed by [DevRaviX](https://github.com/DevRaviX).



