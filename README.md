# python-tesseract
### python + tesseract to recognize text on jpg/pdf file

# Requirement
### on ubuntu
- `sudo apt install tesseract-ocr`
- `sudo apt install -qqy imagemagick`

### on python
- `pipenv`
- `pipenv install pdf2image`
- `pipenv install pytesseract`

# To run
### currently hardcoded for **POC DEMO** only
- `pipenv run python get_text.py`

### to convert pdf to jpg
- `pipenv run python pdf_to_jpg.py`
