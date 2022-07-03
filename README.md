# Supercharge your workflow

'dmenu-editor-history' is a Bash script that provides an awesome editor indepentend history list of opened files. With this you can keep track of previously opened files in order to quickly reopen them again. You can also search for new unopened files under the home directory. If you are the sort of person that frequently edit the same files this is for you!

The default editor is sublime text, but the text editor, dmenu command, and find command can be changed with command line flags. See --help for details.

Shown below (with a custom dmenu command):

<img src="https://github.com/simtd/dmenu-editor-history/blob/main/img.png" width="500" />

## Usage

There are two basic usages:

1) `dmenu-editor-history --sel` - Select a file or search for a new one via dmenu. This command is intended to be run via a custom hotkey.
2) `dmenu-editor-history --open example.txt` - Open a new file from the terminal. This command is intended to be run via a custom shell alias and replaces the normal command you use to open files like `subl`, `vim`, `code`.

## Installation

1) `git clone https://github.com/simtd/dmenu-editor-history.git`
2) `cd dmenu-editor-history`
3) `sudo ./install`

### Uninstall

`sudo ./install uninstall`

## Version log

#### 2.0

- File paths are displayed differently in dmenu
- Major bug fixes related to opening paths from the terminal