# W3C Standard for HTML/CSS

For HTML, CSS and SVG files

Based on 1 API:

* Markup Validator Web Service API

## Requirements

* Python3
* Request: HTTP for humans

## Quickstart

1. Clone this repo
git clone https://github.com/moifore/W3C-Standard.git

2. Run the standard command from within 

Single file:

./w3c_standard.py index.html
./w3c_standard.py css/styles.css

Multiple files:

./w3c_standard.py index.html article.html css/styles.css

All errors are printed in STDERR; Exit status =# of errors (0 on success)

## Troubleshooting

Error: bad interpreter: No such file or directory If you get this error you might not have Python installed correctly; or the system PATH might not be updated to reflect the installed Python version.

Assuming that Python 3 is indeed installed, you can try to run it like so:

python3 w3c_validator.py index.html

Error: ModuleNotFoundError: No module named 'requests' If you get this error you do not have the module requests installed in your system.

You can install requests using pip:

python3 -m pip install requests

If you don't have pip installed, visit pip.pypa.io for instruction on installation
