# PDF Merger
## 📝 Description

A simple Python script that merges multiple PDF files into a single PDF using the `PyPDF2` library.

## 🚀 Features
- Merge two or more PDF files into one

- Automatically adds all pages from each PDF

- Easy to modify for larger batch processing

- Command-line output confirming successful merge

## 🧠 Technologies Used
- Python 3

- PyPDF2

## 📥 Input
- A list of PDF file paths that you want to merge.

- Example:

      input_pdfs = ["part1.pdf", "part2.pdf"]
  
- These files should exist in your project folder or provide full paths if stored elsewhere.

## 📤 Output
- A single merged PDF file containing all pages from the input files.

- The name of the output file is set by:

      output_pdf = "output.pdf"
- After execution, you'll see a success message like:

      ✅ Successfully merged 2 PDF files into 'output.pdf'.
