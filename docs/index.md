# MapLibre for Python

[MapLibre for Python](https://github.com/eoda-dev/py-maplibregl) provides Python bindings for [MapLibre GL JS](https://github.com/maplibre/maplibre-gl-js).

It integrates seamlessly into [Shiny for Python](https://github.com/posit-dev/py-shiny) and [Jupyter](https://jupyter.org/).

## Installation

```bash
# Stable
pip install maplibre # minimal

pip install "maplibre[all]"

pip install "maplibre[shiny]" # shiny bindings

pip install "maplibre[ipywidget]" # marimo and jupyter bindings

uv add "maplibre[all]"

# Unstable
pip install git+https://github.com/eoda-dev/py-maplibregl@dev
```

## Basic usage

### Standalone

```python
-8<-- "getting_started/basic_usage.py"
```

### Shiny integration

```python
-8<-- "getting_started/basic_usage_shiny.py"
```

### Jupyter widget

```Python
from maplibre.ipywidget import MapWidget as Map

m = Map()
m
```
