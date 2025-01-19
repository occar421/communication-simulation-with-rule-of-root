# communication-simulation-with-rule-of-root

## Requirements
* `pygraphviz` https://pygraphviz.github.io/documentation/stable/install.html#manual-download
  * Don't use scoop! The path should be `C:\Program Files\Graphviz\` because some library do not support scoop path.

## Note

To export the result as an image, add this code. `search.draw()` exposes Graphviz Graph class.

```python
g = search.draw()
g.draw("a.svg", prog="dot")
```