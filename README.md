# Binwally3
Binwally3 is the python3 version of the original Binwally binary and directory tree comparison tool using the Fuzzy Hashing concept based on ssdeep.

For more information the original blog post of the python2 version is available here: http://w00tsec.blogspot.com/2013/12/binwally-directory-tree-diff-tool-using.html
Also, the python2 version repo is available here: https://github.com/bmaia/binwally
  
# Prerequisites and Installation

Binwally has the following dependencies (required by ssdeep):
- Python 3.8+
- gcc and build essentials
- libffi 
- libfuzzy-dev 
- python-dev 
- [python-ssdeep](https://pypi.python.org/pypi/ssdeep) (pip install ssdeep)

To install all required dependencies on Debian based systems, just run the setup.sh script.

# Screenshots

![Screenshot](http://1.bp.blogspot.com/--QD8iIwA-C4/UpzvIGUF7JI/AAAAAAAAAKQ/Hyjv1lMolYs/s1600/bin1.png)

![Screenshot](http://3.bp.blogspot.com/-zhz-masG9Ic/UpzvIDKP58I/AAAAAAAAAKU/ApZfSNX8MXU/s640/bin2.png)

# Usage
    python binwally3.py dir1 dir2
