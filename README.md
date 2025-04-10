# AI-group-14
# Handwritten Document to Structured Data using OCR and NLP

This project demonstrates how to extract text from handwritten documents using Optical Character Recognition (OCR) and then structure the extracted text into a meaningful format using Natural Language Processing (NLP) techniques. The final structured data is exported as JSON and CSV files.

## Features

- **Handwritten Text Extraction:** Uses Pytesseract for OCR to convert handwritten text into digital text.
- **Preprocessing:** Includes image preprocessing steps like noise reduction and thresholding to improve OCR accuracy.
- **Sentence Segmentation:** Utilizes NLTK for splitting the extracted text into sentences, focusing on narrative content.
- **Structured Data:** Organizes the extracted sentences into a JSON format, suitable for further processing or analysis.
- **Data Export:** Exports the structured data to JSON and CSV files for convenient use.
- **Evaluation:** Provides basic evaluation metrics like Word Accuracy Rate (WAR) and Character Error Rate (CER) to assess the OCR performance.

## Requirements

- Python 3.x
- Google Colab (recommended) or a local Python environment with necessary libraries installed
- Libraries: Pytesseract, OpenCV, Pandas, NLTK, Matplotlib

## Installation

1. Install the required libraries using pip:
Use code with caution
bash !pip install pytesseract opencv-python pandas nltk

 
2. Install Tesseract OCR (if not already installed):
Use code with caution
bash !apt-get install -y tesseract-ocr

 
3. Download the required NLTK resources:
Use code with caution
python import nltk nltk.download('punkt') nltk.download('punkt_tab')

 
## Usage

1. Upload a handwritten document image to Google Colab.
2. Run the provided Python code.
3. The extracted text, structured data, and evaluation metrics will be displayed.
4. The structured data will be saved as `output.json` and `output.csv` files.

## Evaluation

The project includes basic evaluation metrics:

- **Word Accuracy Rate (WAR):** Measures the percentage of correctly recognized words.
- **Character Error Rate (CER):** Measures the percentage of incorrectly recognized characters.

These metrics can be used to assess the OCR accuracy and identify potential areas for improvement.

## Example

The provided code includes an example with a handwritten document image and ground truth text for evaluation.

## Limitations

- The accuracy of the OCR may vary depending on the quality and clarity of the handwritten document.
- The sentence segmentation approach focuses on narrative text and may not be suitable for all types of handwritten documents.
- The evaluation metrics provide a basic assessment of OCR performance but may not be comprehensive.

## Future Enhancements

- Explore more advanced OCR techniques and pre-processing methods for better accuracy.
- Implement layout analysis for more complex document structures.
- Develop a more robust schema mapping mechanism to accommodate different types of handwritten documents.
- Integrate with other NLP tools for deeper analysis of the extracted text.
Use code with caution
Reasoning:

A good readme.md file should include:

Project Title and Description: A clear and concise title and description of the project.
Features: A list of the key features of the project.
Requirements: A list of the software and hardware requirements for running the project.
Installation: Instructions on how to install the project and its dependencies.
Usage: Instructions on how to use the project.
Evaluation: Information on how the project was evaluated and the results.
Limitations: A discussion of the limitations of the project.
Future Enhancements: A discussion of potential future enhancements to the project.
