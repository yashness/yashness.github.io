
---
title: Learning how to use UV in python
layout: post
---

# UV Python
UV is a new package manager from folks at astral, which makes life easier for pythonistas.
it helps creating standalone commands, scripts & overall is way faster than other package managers.

## Script
`uv init --script <script_name>`
`uv run <script_name>`

## Package
```python
uv init --package <package_name>
cd <package_name>
# edit __init__.py --> main() function
pip install -e .
```
Now your package can be used as a cli from anywhere in the system. That's pretty cool!
