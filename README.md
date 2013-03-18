# Scroll To Top Middle Bottom

Move cursor to top/middle/bottom of visible lines for Sublime Text 2.

## Installation

### Clone from GitHub

You can clone the repository directly from GitHub into your Packages directory:

    git clone https://github.com/SublimeTextTW/scroll-to-top-middle-bottom.git

## Usage

### Key Bindings

For OS X user:

``` json
[
  { "keys": ["super+m", "super+t"], "command": "move_caret_top" },
  { "keys": ["super+m", "super+m"], "command": "move_caret_middle"},
  { "keys": ["super+m", "super+b"], "command": "move_caret_bottom"}
]
```

For Windows/Linux user:

``` json
[
  { "keys": ["ctrl+m", "ctrl+t"], "command": "move_caret_top" },
  { "keys": ["ctrl+m", "ctrl+m"], "command": "move_caret_middle"},
  { "keys": ["ctrl+m", "ctrl+b"], "command": "move_caret_bottom"}
]
```

## TODO

* Submitting to Package Control...
