# TranscriptAnalysis
### The ultimate goal of TranscriptAnalysis is to transform grades in the Chinese grading scale into those in the Norwegian grading scale.
### Extract_Convert_Trans.ipynb: This code firstly extracts the transcript from scanned PDF files and generates a csv file with the extracted text in tables. Then update the csv file with the corresponing Norweigian grads.
### ocr_textdection.ipynb: Extracting text using different libraries including google cloud vision (https://cloud.google.com/vision), kraken (https://kraken.re/main/index.html), easyocr (https://github.com/JaidedAI/EasyOCR), and pytesseract (https://pypi.org/project/pytesseract/).
### en_best.mlmodel: the pre-trained deep learning model used by kraken, and it can be downloaded from https://zenodo.org/record/2577813#.ZEL0oexBy0t
### optimal-via.json: the file is one's Google Cloud service account key file
