# OCR
IMAGE-TO-TEXT USING PYTESSERACT AND EASYOCR

<img src = 'https://s3.amazonaws.com/element-ai-website-bucket/_768x634_crop_center-center_60_line/OCR-Desktop-front@2x.png' height=450 width=650/>

Based on my recent experience with this pytesseract on Windows, follow these steps in sequence :

Install tesseract using windows installer available at: https://github.com/UB-Mannheim/tesseract/wiki

Note the tesseract path from the installation. Default installation path at the time of this edit was: C:\Users\USER\AppData\Local\Tesseract-OCR. It may change so please check the installation path.

pip install pytesseract

Set the tesseract path in the script before calling image_to_string:

pytesseract.pytesseract.tesseract_cmd = r'C:\Users\USER\AppData\Local\Tesseract-OCR\tesseract.exe'


# FOR EasyOCR VISIT MY ARTICLE: https://analyticsindiamag.com/hands-on-tutorial-on-easyocr-for-scene-text-detection-in-images/
