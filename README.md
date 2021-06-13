
# Seavatar

Seavatar is a python library which generates beach-MLH themed avatars

![alt text](https://svgshare.com/i/Y5M.svg)
#### A seavatar generated for the string surfsuphack
## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install Seavatar

```bash
pip install seavatar
```

## Usage

```python
import seavatar

svgtext=seavatar.generate_seavatar("GitHub","github.svg")
#The first argument is the string which needs to be 
#converted to an avatar ,the second argument is the filename
#where the file should be stored, by default the filename is
#seavatar.svg

print(svgtext)
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
