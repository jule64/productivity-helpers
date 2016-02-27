## Contents
* [Intellij \[OSX\]](#intellij-for-osx) [\[WIN\]](#intellij-for-windows)
* [VIM \[OSX\]](#vim)
* [Eclipse \[WIN\]](#eclipse-windows)
* [Atom \[OSX\]](#atom-osx)
* [Markdown Tips](#markdown-tips)


## IntelliJ for OSX

```
⌘ J                           live template  
⌥ ⌘                           Jsurround with live template  
⌘ F12                         file structure  
^ J                           quick doc (also F1)  
⌘ Y or ⌥ <spacebar>           quick definition  
⌘ P                           view parameter info  
⌘ B                           navigate to declaration  
^ H                           inheritance hierarchy  
⌥ ⌘ O                         open any particular method or field in the editor quickly  
^ G or ⌥ .                    find next occurrence of word  
^ M                           matching bracket  
F3                            bookmark. Also ⌥ F3 (mnemonic) and ⌘ F3 (show bookmarks)  
⌘ F8                          create break point  
⇧ ⌘ A                         find action  
⌘ ^ T                         compile typescript  
⇧ ⌘ ↩︎                         to complete a current statement such as if, do-while, try-catch  
⌥ R                           Replace  
⌥ ⌘ O                         open any particular method or field in the editor quickly  
⌥ F8 or ^ U                   evaluate expression when debug  
⌘ K                           git commit directory popup  
⌘ ⇧ K                         git push  
⇧ ⌘ ←                         last edit location  
⇧ ⌘ F7                        highlight usages in the file  
⌘ G and ⇧ ⌘ G                 navigate through highlighted usages  
^ ⇧ Q                         shows declaration of current method  
⌘ E                           view recent files  
⌥ ⌘ ↑/↓                       jump between compiler errors or search results
```

## VIM

```
- editor:

zz, zt, zb                    position cursor at middle, top, or bottom of screen
<C-C>                         switch out of insert mode (much better than ESC!)
=                             format selected code (in visual mode)
%                             match brackets
* #                           find word under cursor
/<C-R><C-W>                   Pull <cword> onto search/command line
CTRL-R %                      pull file name (also #)
:so %                         reload current file
<C-O> or <C-I>                retrace your movements in file backward/forward
U/u                           convert selected text to uppercase/lower case
<C-N>                         autocomplete word
g Ctrl-g                      info about current file (line numbers etc.)
ciw                           change inner word


- registers:

"gy                           copy content of visual mode selection in register, "gp to paste  
:reg                          display all registers
"1p                           paste from register 1


- macros:

qX                            start recording a macro (X = key to assign macro to)
q                             stop recording
@X                            playback macro
@@                            replay previously played macro
100@w                         playback w macro 100 times


- bookmarks:

mX  / `X                    bookmark current cursor place / jump to bookmark
:marks                        show all bookmarks
:delm X / :delm!              delete X bookmark / all bookmarks


- search replace:

:%s/fred/joe/igc              general substitute command
:g/^\s*$/d                    delete all blank lines
:%s//someword                 // will pickup the last regex used


- help:

:h someword<C-D>              shows list of help topics matching someword
:h ctrl<C-D>                  list help of all control keys
:h i_CTRL-R                   help for say <C-R> in insert mode (c_ and v_ for command and visual mode)


- screens:

:split  / :vsplit             split screen horiz / vert
:<C-W>j                       move to next split
:only                         close all other splits


- panels and buffers:
:bd                           remove file from buffer list
:bn                           next buffer
:sp fred.txt                  open fred.txt into a split
:n                            next file in argument list
:tabe                         open new tab page


```



## IntelliJ for Windows  

```
^ Q                           quick doc
^ B                           navigate declaration
^ ⌥ B                         go to implementation
^ F12                         file structure  
F6                            refactor | rename  
^ O                           override method  
^ ⌥ O                         organize imports  
^ I                           implement method  
^ ⌥ I                         format code  
^ ⇧ I                         definition of the method,class where cursor is pointing    
^ ⇧ <spacebar>                smartType code completion  
^ ⇧ F                         find in path (same as normal find but searches all source files  
^ ⇧ A                         find actions e.g. settings, their shortcut if exists  
^ E                           recently opened files  
^ ⇧ E                         recently edited files  
F2                            any error in file  
⌥ <insert>                    generate getter/setter  
⌥ `                           bring up VCS operations pop up dialogue (++)  
^ W  or ^ ⇧ W                 select/De-select word at caret (repeat to expand to enclosing expressions)  
⌥ F1, Enter                   shows the file in project window   
^ Y                           Delete line  
F12                           Switch to project view  
^ ⇧ F12                       hides everything but editor, press again restore  
```


## Markdown Tips

- create line break: add two spaces at end of line and press return key (github markdown)  
- create block: use `<pre>some content</pre>` tag to create a table like-alignment (like done in this document)  
- create link in doc:  `[visible text](#title-to-link-to)`


<a href="#top">top</a>
