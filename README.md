# Supercharge your workflow

'dmenu-editor-history' is a Bash script that provides an awesome editor indepentend history list of opened files. Also allows you to quickly search for files with find.

The default editor is sublime text, but the text editor, dmenu command, and find command can be changed with command line flags. See --help for details.

Shown below (with a custom dmenu command):

<img src="https://github.com/simtd/dmenu-editor-history/blob/main/img.png" width="500" />

## Usage

There are two basic usages:

1) `dmenu-editor-history --sel` - Select a file or search for a new one via dmenu. This command is intended to be run via a custom hotkey.
2) `dmenu-editor-history --open example.txt` - Open a new file from the terminal. This command is intended to be run via a custom shell alias.

## Installation

1) `git clone https://github.com/simtd/dmenu-editor-history.git`
2) `cd dmenu-editor-history`
3) `sudo ./install`

### Uninstall

`sudo ./install uninstall`
