# OCR-Translate
Extract text from .pdfs and translate documents.

# Project Description:

In this notebook, I demonstrate how to take a document in .pdf format, translate the source text into a couple of languages, then save the translation as a .txt or .docx file. The source text in this example is a Finnish language masters thesis on self-taught artist Paavo Pyhtilä. The text was used with permission by its author, Pertti Pyhtilä. For the full text, check the input_dir folder or: https://jyx.jyu.fi/handle/123456789/38865 <br>

An advantage that this script has over browser based translation services is there is no character limit. <br> 

The ideal use case for this script is when one has an unhighlightable .pdf written in one language for which one needs a translation on the fly. <br> 

In order to use this notebook, all you have to do is specify where the .pdf is you would like to transcribe and specify where you want to save the translation. 

# Dependencies: 
pip install googletrans <br>
pip install pytesseract <br>
pip install Wand <br>
pip install pillow <br>

<b>Note</b>:<br>
At present, <b>pytesseract</b> provides character recognition for more languages than the library <b>googletrans</b> provides translation services for. Be sure to check that each lib supports the languages you want to work with.  

For a full list of languages tesseract provides character recognition for:
https://github.com/tesseract-ocr/langdata/

For a breakdown of ISO 639-2/T and ISO 639-2/B language codes that tesseract uses:
https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes

