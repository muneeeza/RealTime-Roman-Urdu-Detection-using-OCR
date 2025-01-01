# Real-Time Roman Urdu Text Recognition using OCR
This Jupyter Notebook demonstrates a system for recognizing Roman Urdu text using Optical Character Recognition (OCR). Developed as a final project for a Computer Vision course, the project involves capturing images, preprocessing them for clarity, extracting text with EasyOCR, and distinguishing between English and Roman Urdu words using a custom dictionary.

## Project Overview
This project is part of a deep learning course and aims to:

* Capture text from an image.
* Preprocess images to improve OCR accuracy.
* Extract text using OCR (EasyOCR).
* Classify extracted words as either English or Roman Urdu.
  
## Key Components
* Image Capture: Uses JavaScript in Google Colab to capture images from the webcam and saves captured images in a specified folder for further processing.
  
* Image Preprocessing: This converts images to grayscale, applies sharpening, and resizes for consistency. Preprocessing enhances OCR accuracy by making text features more distinguishable.

* Text Extraction (EasyOCR): EasyOCR extracts text from images and processes text to separate individual words for classification.

* Word Classification: Distinguishes between English and Roman Urdu words using the NLTK English dictionary for English words and a custom dictionary for Roman Urdu words.

## How to Use
* Run the Notebook: Open the notebook and run each cell sequentially.
* Capture Image: Use the webcam capture cell to take a photo.
* View Output: After running OCR and classification cells, view the output to see the extracted text and word classifications.

## Requirements
* Libraries: Ensure you have installed easyocr, Pillow, and nltk.

      pip install easyocr Pillow nltk
* Dataset:
  
      https://drive.google.com/drive/folders/1IhvN1C3lqs8WoDZd1Q9F1MY5wMFJiX1O?usp=sharing
  
More details in the report. 

## Contributers 
Hafsa Hafeez Siddiqui 
