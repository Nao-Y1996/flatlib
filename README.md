# flatlib

This is forked repository of [Flatlib]([https://pypi.python.org/pypi/flatlib]) library for Traditional Astrology.

```python

>>> date = Datetime('2015/03/13', '17:00', '+00:00')
>>> pos = GeoPos('38n32', '8w54')
>>> chart = Chart(date, pos)

>>> sun = chart.get(const.SUN)
>>> print(sun)
<Sun Pisces +22:47:25 +00:59:51>

```

## Documentation

original Flatlib's documentation is available at [http://flatlib.readthedocs.org/](http://flatlib.readthedocs.org/).


## Installation

Add following line to your `pyproject.toml` file:

```toml
[tool.poetry.dependencies]
flatlib = { git = "https://github.com/Nao-Y1996/flatlib.git", tag = "v0.2.4" }
```
