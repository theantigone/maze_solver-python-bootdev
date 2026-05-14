# [Build a Maze Solver in Python](https://www.boot.dev/courses/build-maze-solver-python)

## prereqs

- python 3.10+
- [tkinter](https://docs.python.org/3/library/tkinter.html)

## getting started

1. check if `tkinter` works

```sh
python3 -m tkinter
```

> [!WARNING]
> for issues regarding `tkinter` (e.g., if `tkinter` fails), go to the [troubleshooting][#troubleshooting] section

2. if it does work, then run the game

```sh
python3 main.py
```

## troubleshooting

If you're seeing an error like this:

```sh
ModuleNotFoundError: No module named '_tkinter'
```

You're missing the dependency. Check to see which version of Python you're using:

```sh
python3 --version
```

You should be on `3.10` or higher. If you're not, update your Python version and try `python3 -m tkinter` again.

If that's still not working, it's important to understand that `tkinter` depends on the `Tcl/Tk` library. Installing the `tk-dev` or `python-tk` packages are usually the easiest way to install and link it to your Python version. On Ubuntu (Linux), run:

```sh
sudo apt-get install python3-tk
```

on fedora, run:

```sh
sudo dnf install python3-tkinter
```

On MacOS, make sure you have [Homebrew](https://brew.sh/) installed, and then run:

```zsh
brew install python-tk
```

_Your versions of python-tk and Python should match!_

If `python3 -m tkinter` still isn't working, try uninstalling and reinstalling Python so that it links to the now-available `Tcl/Tk` library.

## dates

- started: 5/14/2026 ~9:30 am est
- finished:

