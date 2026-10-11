# config-loader

Merge configuration from files, environment variables and defaults.

## Why

I wanted something I could read in one sitting and vendor into a project if needed.

## Install

```bash
pip install config-loader
```

## Usage

```python
from config_loader import configLoader

result = configLoader("example")
print(result)
```

## Notes

- No runtime dependencies outside the standard library.
- Tested on Python 3.9 and newer.

## License

MIT
