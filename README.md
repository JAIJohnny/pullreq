# JAI Python Wrapper

<img src="PythonWrapper.png" Width="150"> 

## About
JAI Python Wrapper is a library for controlling the JAI camera using Python. The eBUS SDK is used for direct control of the camera; while this library provides an interface for Python as an upper layer of eBUS SDK.

**Note**: JAI Python Wrapper is not a pure Wrapper function of eBUS SDK. It provides a more abstract API.

**Caution**: This project is offered with no technical suport by JAI. You are welcome to post any questions or issues on Github (https://github.com/jai-rd/pyJds/issues).
### Supported Operating System
- Windows 10
## Getting Started
### 1. Download and intall the following: 
- **eBUS SDK for JAI** (https://www.jai.com/support-software/jai-software)
- **Python with pip** (https://www.python.org/downloads/)

  **Note**: Python 3.8 and 3.9 are tested with sample codes.
### 2. Install JAI pyJds:
1. Download the whl file from https://github.com/jai-rd/pyJds/releases.
2. Install: `pip install ./pyjds-0.0.5-py3-none-win_amd64.whl`
## Start Development

**Note**: Pull requests to JAI pyJds are welcome!
1. Copy your module file “_module.cp38-win_amd64.pyd” into the project. The module file can be found in the following directory: C:¥Users¥yourname¥AppData¥Roaming¥Python¥Python39¥site-packages¥pyjds.

    **Note**: If you use python 3.8, use “_module.cp39-win_amd64.pyd”.

2. Link the local pyjds source directory into your python installtion: `python xxxx`
## Sample Codes
Sample codes are available here: `xxx`
## API Reference
You can find the API Reference here: https://d2ezksrziasiu7.cloudfront.net/v0/004/_build/pyjds.html
## Known Issues
You can find known issues here: https://github.com/jai-rd/pyJds/issues
