# PDF to Text Coversion using Optical Character Recognition

I've used a library called Tesseract which converts Image to Text using Optical Character Recognition Technology. This code will accept PDFs as input, get text from pdfs and writes the output as text files in the text directory.

**Usage:**
```
python jpg_or_pdf2text.py /path/to/pdf-files/
```

```
Options:
  -h, --help            help message
  -d DPI, --dpi=DPI     JPEG Resolution in DPI (default: 400)
  -j JPGDIR, --jpgdir=JPGDIR    JPEG output directory (default: jpg)
  -t TXTDIR, --textdir=TXTDIR   Text output directory (default: text)
  -r, --resume          Resume OCR to Text (default: False)
```
