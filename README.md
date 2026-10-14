# log-parser

A line-oriented log parser that turns key=value logs into dictionaries.

## Why

I wanted something I could read in one sitting and vendor into a project if needed.

## Install

```bash
pip install log-parser
```

## Usage

```python
from log_parser import logParser

result = logParser("example")
print(result)
```

## Notes

- No runtime dependencies outside the standard library.
- Tested on Python 3.9 and newer.

## License

MIT
