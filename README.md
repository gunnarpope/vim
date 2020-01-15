# vim tricks
A personal collection of Vim tricks that I use for typing, searching, sifting, duplicating, and thrashing any general plain text.

## Installation

Open a terminal by typing the Home key and type in "Terminal" and select it.
Then, open a file in vim

```
$ vim hello.py 

```

## Finding words and patterns in text

```
:g/PATTERN					# returns the numbers of lines matching PATTERN

:g//						# return the lines of the last search items
```


## Search and Replace Text

```
:%s/PATTERN/PATTERN2/g		# replace PATTERN with PATTERN2, across the whole file

:%s/PATTERN/PATTERN2/gc		# replace PATTERN with PATTERN2, across the whole file, but check the user for each one

```

## Visual Mode
```
Ctrl+v 						# select data columns vertically


```

# Navigation
```
:e file.txt					# opens a new file named file.txt

:bn 						# Switch between buffers displayed

:vimgrep /pattern/ {file}   # search for pattern in multiple files

```
