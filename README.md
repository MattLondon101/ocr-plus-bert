# ocr-with-bert
OCR improvement with BERT typo recognition and correction

# Installation
`$ sudo apt install tesseract-ocr`

`$ sudo apt install libtesseract-dev`


With Ubuntu, change the tesseract_cmd path in your code:

`pytesseract.pytesseract.tesseract_cmd = r'/usr/bin/tesseract' # config line`


# Running and Visualizing results

In order to plot the example results of OCR model, run `draw.py` function. You can test on the single image or on the whole directory, e.g.

`python draw.py examples/1.png`

or

`python draw.py examples/`
