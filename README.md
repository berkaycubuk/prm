# Personal Relationship Manager

This tool helps you to manage your contacts. It stores your contacts
inside markdown files so you can use it with your favorite text editor.

## Installation

1. Download the latest release.
    - https://github.com/berkaycubuk/prm/releases/latest
2. Extract the files inside the directory you want.
3. Add `prm` script to the PATH.
4. Run `prm init`.

## Commands

### Init

`prm init`

### Contact

#### New

`prm contact new -n "Name" -l "Lastname" -p "Phone" -m "email"`

#### Delete

`prm contact delete -n "Name" -l "Lastname"`

#### View

`prm contact view -n "Name" -l "Lastname"`

or

`prm contact view`

### Version

- `prm version`

### Help

- `prm`
