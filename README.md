# Transfer.sh-api
[![License](https://img.shields.io/badge/license-MIT-blue)](https://choosealicense.com/licenses/mit/)
[![Python 3.x](https://img.shields.io/badge/python-3.x-yellow.svg)](https://www.python.org/) 

Transfersh is a Python library for upload files on [transfer.sh](https://transfer.sh/). 

## About
This Python API was created to make uploading and downloading files from [transfer.sh](https://transfer.sh/) simple.

## Installation
```bash
pip install transfersh-cli && pip install wget
```

## Usage
### Upload files
```bash
transfersh "filepath"
```

### Download files
```python
import wget


try:

    download = wget.download("direct URL") # How? https://encrypting.host/uRZkzQnPb8.gif?key=R4WzyRMxLBDjcp
  
except Exception as e:
    print(e)
    # your file can't be downloaded.
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
