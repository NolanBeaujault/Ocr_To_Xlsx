
---

# Project Overview

This project is divided into two main parts, each implemented in a separate Jupyter Notebook (`.ipynb`):

1. **OCR Recognition with OpenCV and Tesseract**
2. **CSV Data Processing with ChatGPT**

## Part 1: OCR Recognition with OpenCV and **Tesseract**

### Description
This part of the project focuses on Optical Character Recognition (OCR) using OpenCV and Tesseract. The goal is to extract text from images and process it for further analysis.

### Key Features
- **Image Preprocessing**: Techniques such as grayscale conversion, thresholding, and noise removal to enhance image quality.
- **Text Extraction**: Using Tesseract to recognize and extract text from preprocessed images.
- **Result Visualization**: Displaying the original image with the recognized text overlaid.

### Requirements
- OpenCV
- Tesseract-OCR
- pytesseract

### Usage
1. Install the required libraries:
   ```bash
   pip install opencv-python pytesseract
   ```
2. Ensure Tesseract-OCR is installed on your system and properly configured.
3. Run the Jupyter Notebook `ocr_recognition.ipynb` to see the OCR process in action.

## Part 2: CSV Data Processing with ChatGPT

### Description
This part of the project involves processing a CSV file provided by ChatGPT, so we use GPT's OCR. The goal is to read, analyze, and manipulate the CSV data for various purposes.

### Key Features
- **CSV Reading**: Using `pandas` to read and load CSV data into a DataFrame.
- **Data Analysis**: Performing basic data analysis and manipulation tasks.
- **Data Export**: Saving the processed data into a new CSV or Excel file.

### Requirements
- pandas
- openpyxl

### Usage
1. Install the required libraries:
   ```bash
   pip install pandas openpyxl
   ```
2. Run the Jupyter Notebook `csv_processing.ipynb` to see the data processing steps.

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/yourproject.git
   ```
2. Navigate to the project directory:
   ```bash
   cd yourproject
   ```
3. Install the required libraries for both parts of the project:
   ```bash
   pip install -r requirements.txt
   ```
4. Open the Jupyter Notebooks and follow the instructions provided in each notebook.
