<!-- ABOUT THE PROJECT -->
## Introduction

- Many bulk certificate generators use jpeg or other image formats to create certificates which often results in poor quality of the certificates.
- This project aims to produce certificates that are lossless and are of high quality by using PDF format.
- `generator.py` is a simple python script that can produce multiple certificates from a given template (in PDF).
- The name of the participants are provided by the user in the form of a spreadsheet.
- The font style, size and position of the text to be printed on the certificate is also provided by the user.


<!-- GETTING STARTED -->
## Getting Started

The following instructions would help you run the python script on your local machine.

### Prerequisites

- **Python 3.2 or higher**

Python modules to be installed:
- PyPDF2
- pandas
- reportlab

<!-- USAGE EXAMPLES -->
## Usage

- Move into the directory containing the python script
- Copy the template of the certificate (in .pdf format) into the directory.
- Copy the spreadsheet that contains the name of the participants into the directory.
- Copy a font file (in .ttf format) into the directory. The name will be printed using this font.
- Run the python script: `python3 generator.py`
- Provide the necessary inputs to the program. Pixel dimension specifies the position where the name has to be printed on the certificate.
- The certificates will be generated inside the `certificates` directory.