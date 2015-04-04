# bash_bookmark

A little script to add bookmarks (`cd` alias) to your shell.

### Usage

__Add bookmark : `bm` :__

Use `bm <bookmark-name>` to add a bookmark to your current location.

__Use bookmark : `<bookmark-name>`__

Simply use `<bookmark-name` to use your bookmark.

__List bookmarks : `bml`__

Use `bml` to show your existing bookmarks

__Delete a bookmark : `bmd <bookmark-name>`__

Use `bmd <bookmark-name>` to delete a bookmark.

__Manually edit your bookmarks : `bme`__

`bme` will open your bookmarks file (stored in `~/.bookmarks`) with your default editor.

### Installation

Copy `.bash_bookmark` in your `~` and add this line to your `.bash_profile`or `.bashrc` :

```bash
. ~/.bash_bookmark
```

Or simply execute this line :

```bash
wget -P ~ https://raw.githubusercontent.com/dorian-marchal/bash_bookmark/master/.bash_bookmark && echo ". ~/.bash_bookmark" >> ~/.bashrc
```

Be careful, this script add aliases in your shell global scope.
