## to open a file
```
vi filename
```

## to see help
```
:help
```

## command mode
```
esc
```

## to work with multiple files
to open multiple files
```
vi file1 file2 file3
```

go to the next file
```
:n
```

go to the previous file
```
:N
```

to list all opened files (buffers)
```
:ls
```

to select buffer file (n is number of prefered buffer)
```
:b n
```

go to the next buffer
```
:bn
```

go to the previous buffer
```
:bp
```

to close current buffer
```
:bd
```

to save all files and quit
```
:wqa
```

to discard all changes and quit
```
:q!
```

## to work with tabs
to open a file in a new tab
```
:tabe filename
```

to open multiple files in tab mode from terminal
```
vim -p file1 file2
```

to move to the next tab
```
:tabn
```

to move to the previous tab
```
:tabp
```

## to work with split screen mode
to open a file with split screen
```
:sp filename
```

to open a file with horizontal split
```
:split filename
```

to opne a file with vertical split
```
:vsplit filename
```

to move to the bottom screen (`ctrl`+`w` and then)
```
w
```

to move to the top screen (`ctrl`+`w` and then)
```
W
```

to navigate between splitted screens (`ctrl`+`w` and then)
```
arrow keys
```

## to write (insert mode)
insert
```
i
```
jump and insert at the beginning of the current line
```
I
```
append (insert after current cursor)
```
a
```
jump and append at the end of the current line
```
A
```
insert a new line after the current line
```
o
```
insert a new line before the cuurent line
```
O
```

## to copy/cut/paste 
copy a line
```
yy
```
copy a word
```
yw
```
paste
```
p
```
cut line (also works as delete the line)
```
dd
```
cut word (also works as delete the word)
```
dw
```
select (move cursor, use `y` to copy and `d` to cut, use `p` to paste)

```
v
```

## to save or exit 

save and quit
```
ZZ
```

discard changes and quit
```
:q!
```

just save
```
:w
```

save and quit
```
:wq
```

## to navigate in the editor 
move the cursor
```
Arrow keys
```
move cursur to the beginning of the current line
```
^
```
move cursor to the end of the current line
```
$
```
jump to the first line
```
gg
```
jump to the last line
```
G
```
move to the next word
```
w
```
move to the previous word
```
b
```

## to delete content 

delete a single character
```
x
```
delete the current line
```
dd
```

## to undo 

undo the last change
```
u
```
undo all changes
```
U
```

## to find, or find and replace a word 
to search for a word forward (press `enter` then press `n` to jump to the next match and `N` to jump to the previous match)
```
/word
```

to search for a word backward (press `enter` then press `n` to jump to the next match and `N` to jump to the previous match)
```
?word
```

to search for a whole word (press `enter` then press `n` to jump to the next match and `N` to jump to the previous match)
```
/\<word\>
```

to search for a whole word (case insensitive) (press `enter` then press `n` to jump to the next match and `N` to jump to the previous match)
```
/\<word\>\c
```

to find and replace all matches
```
:%s/word/target_word/g
```

to find and replace with confirmation
```
:%s/word/target_word/gc
```

to find whole word and replace
```
:%s/\<word\>/target_word/g
```

to find and replace (case insensitive)
```
:%s/word/target_word/gi
```

to find and replace in the current line
```
:s/word/target_word/g
```

to find and replace in certain lines
```
:(start_line_number),(end_line_number)s/word/target_word/g
```
