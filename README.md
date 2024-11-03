# Documentation

This repository contains the code for the application's documentation site. It's built with [mkdocs-material](https://squidfunk.github.io/mkdocs-material/).

## Requirements

In order to develop for this repository you need:

* [Python 3.12](https://www.python.org) (but any `>3.12` should work fine)

## Development

First, clone this repository:

```bash
git clone https://github.com/starpep-web/documentation
```

Create an environment:

```bash
python3 -m venv ./venv
```

Load the environment:

```bash
source ./venv/bin/activate
```

(Or, if you're on Windows, you might have to do it with:)

```powershell
.\env\Scripts\activate.ps1
```

Install the dependencies:

```bash
pip install -r requirements.txt
```

Run the `mkdocs` command to serve the site:

```bash
mkdocs serve -a 0.0.0.0:8080
```

And done, the documentation site should be reachable at `http://localhost:8080`.
