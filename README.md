
# PDF Structure and Syntactic Analysis for Metadata Extraction and Tagging

 https://code.google.com/archive/p/pdfssa4met/

PDFSSA4MET attempts to provide metadata extraction and tagging based on 
structural and syntactic analysis of content in XML.

## Installation

This programs uses Python 2.7

Also, you have to install next

```bash
pip2 install lxml
```
and make the **pdf2text** executable

```bash
cd pdf2xml
sudo chmod +x pdftoxml.linux64.exe.1.2_7
```

The following scripts can be used directly to output results to STDOUT:
pdf2xml.py
headings.py
references.py
socialtags.py

Help, options and arguments for each are available using -h or --help option
e.g.
python references.py --help
