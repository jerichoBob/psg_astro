# psg_astro

`psg_astro` is a demo app showing how we might use [PySimpleGUI](https://www.pysimplegui.org/en/latest/#install) to re-surface (as in road resurfacing) [rbcodes/GUIs](https://github.com/rongmon/rbcodes/tree/master/GUIs).

## Setup

Do the following steps to prep your environment

```bash
git clone git@github.com:jerichoBob/psg_astro.git
cd psg_astro
python3 -m venv venv
source ./venv/bin/activate
```

And, because we will be using tkinter as our graphical front-end, we'll need to install it
```bash
brew install python-tk
```

This obviously assumes that 1. you're on a mac and 2. you've already [installed homebrew](https://docs.brew.sh/Installation). If either of these aren't true, please call me!


## Installation

Now you're ready to install the things

```bash
pip install -r requirements.txt
```