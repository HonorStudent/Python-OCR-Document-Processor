# Python OCR Document Processor

A Python application that automates text extraction from image files using Optical Character Recognition (OCR) and exports the extracted text into Microsoft Word documents.

## Overview

This project was created to simplify the process of converting screenshots and scanned documents into editable text. Instead of manually typing information from images, the application automatically processes image files, extracts text using OCR, and generates a formatted Microsoft Word document.

## Features

- Extracts text from images
- Supports OCR using Tesseract
- Creates Microsoft Word (.docx) documents automatically
- Processes multiple images
- Simple and easy-to-use workflow

## Technologies Used

- Python
- Tesseract OCR
- Pillow
- python-docx

## How It Works

1. Load one or more image files.
2. The application prepares the images for OCR.
3. Tesseract extracts the text.
4. The extracted text is organized into a Microsoft Word document.
5. The completed document is saved automatically.

## Installation

Clone the repository:

```bash
git clone https://github.com/YourUsername/Python-OCR-Document-Processor.git
```

Install the required packages:

```bash
pip install pillow pytesseract python-docx
```

Install Tesseract OCR on your computer and configure the executable path if necessary.

## Usage

Run the program:

```bash
python main.py
```

Follow the prompts to select your images. The program will generate a Word document containing the extracted text.

## Future Improvements

- PDF support
- Graphical user interface (GUI)
- Batch folder processing
- Improved image preprocessing
- Automatic spelling correction
- Export to PDF and plain text

## What I Learned

While developing this project, I gained experience with:

- Optical Character Recognition (OCR)
- Python automation
- File processing
- Image manipulation
- Microsoft Word document generation
- Working with third-party Python libraries

## Author

Joshua Thomas
