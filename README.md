# sqlite-migrate

Numbered migration files applied in order, with a version table.

## Why

Mostly written for my own projects, but it may be useful to someone else.

## Install

```bash
pip install sqlite-migrate
```

## Usage

```python
from sqlite_migrate import sqliteMigrate

result = sqliteMigrate("example")
print(result)
```

## Notes

- No runtime dependencies outside the standard library.
- Tested on Python 3.9 and newer.

## License

MIT
