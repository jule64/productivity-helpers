## Contents
* [Intellij \[OSX\]](#intellij-for-osx) [\[WIN\]](#intellij-for-windows)
* [VIM \[OSX\]](#vim-for-osx)
* [Eclipse \[WIN\]](#eclipse-windows)
* [Atom \[OSX\]](#atom-osx)
* [Markdown Tips](#markdown-tips)


## IntelliJ for OSX

<pre>
⌘ J                           live template  
⌥ ⌘                           Jsurround with live template  
⌘ F12                         file structure  
^ J                           quick doc (also F1)  
⌘ Y or ⌥ &lt;spacebar&gt;           quick definition  
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
</pre>

## VIM for OSX

<pre>
registers:
"gy                           copy content of visual mode selection in register, "gp to paste  
:reg                          display all registers

ZQ                            close file  (ZZ close without saving)

</pre>



## IntelliJ for Windows  

<pre>
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
^ ⇧ &lt;spacebar&gt;                smartType code completion  
^ ⇧ F                         find in path (same as normal find but searches all source files  
^ ⇧ A                         find actions e.g. settings, their shortcut if exists  
^ E                           recently opened files  
^ ⇧ E                         recently edited files  
F2                            any error in file  
⌥ &lt;insert&gt;                    generate getter/setter  
⌥ &lt;backtick&gt;                  bring up VCS operations pop up dialogue (++)  
^ W  or ^ ⇧ W                 select/De-select word at caret (repeat to expand to enclosing expressions)  
⌥ F1, Enter                   shows the file in project window   
^ Y                           Delete line  
F12                           Switch to project view  
^ ⇧ F12                       hides everything but editor, press again restore  
</pre>


## Markdown Tips

- create line break: add two spaces at end of line and press return key (github markdown)  
- create block: use &lt;pre&gt;some content&lt;/pre&gt; tag to create a table like-alignment (like done in this document)  
- create link in doc:  [visible text](#title-to-link-to)


<a href="#top">top</a>
