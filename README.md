# traceanalyzer
this library provides tools for analyzing ns2 trace file using python
## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install traceanalyzer.

```bash
pip3 install traceanalyzer

```

## Usage

```python
import  traceanalyzer as tr
#analysis of end-to-end delay
eedelay=tr.Eedelay('tracefile1.tr','33') # returns 'words'
foobar.pluralize('goose') # returns 'geese'
foobar.singularize('phenomena') # returns 'phenomenon'
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
