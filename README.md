# hello-git

A small practice repo for learning Git: committing, branching, pull requests, and merging.

## What's here

| File | Purpose |
| --- | --- |
| `hello.py` | A Python script that prints a few greetings and defines `reverse_string` |
| `notes.txt` | A running note on Git milestones |
| `.gitignore` | Keeps secrets and generated files (`.env`, `__pycache__/`, `.venv/`, and others) out of the repo |

## Running it

You need Python 3.

```sh
python3 hello.py
```

Output:

```
hello world
learning git, with help from Claude
hi from a branch
```

## Using `reverse_string`

```python
from hello import reverse_string

reverse_string('hello')  # 'olleh'
```

Importing `hello` also runs its `print` lines, so the greetings appear on import.

## Git workflow practised so far

- Committing directly to `main`
- Making a change on a branch (`add-greeting`) and merging it through a pull request
- Adding a `.gitignore` so local files such as `.env` stay untracked
