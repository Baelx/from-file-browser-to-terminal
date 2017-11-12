# From file  Browser to Terminal

This guide shows you all the ways one can use the terminal in place of the file browser. The intention here is not to completely eliminate use of the file browser entirely, but more as an aid in improving shell skills. It's not implied that all shell commands/methods are easier or more convenient either. This is merely a reference for the sake of practice.

If you have stumbled across this guide, I hope you find it useful yourself. Possible additions or corrections would certainly be appreciated and of course feel free to fork, clone, or download.

**General Tips:** 
* Make sure you're using [tab completion](https://en.wikipedia.org/wiki/Command-line_completion) whenever you can to speed things up
* Another important tip

**Important Note:** As with all things Linux, each of these commands leads down their own rabbit hole of information and history. This means that some of these commands may have more onerous consequences than others if used incorrectly. It's also tempting to want to [copy and paste](http://i.imgur.com/SZPjHwz.jpg) some commands wholesale. Therefore, I've added a little asterisk to each command I feel could use some more research before being used [in the style of William Nilly](https://www.merriam-webster.com/dictionary/willy-nilly).

TL;DR

***\**** - Asterisk means: watch out this command can be tricky and/or possibly destructive. See More Info on correct and prudent usage.


| Task | In File Browser | In Terminal | More Info |
| ------- | -------- | ------- | ------- |
| Create a zipfile/archive | Right-click on file, click "Compress" | `tar -cf compressedfile.tar filetocompress.txt` | Link |
| View file type | File browser may have graphical indications of file type, or right-click and choose "Properties" | `file filename.txt` | Link |
| Move file(s) to another directory* | Open two windows/tabs of file browser, select file(s), click and drag from one location to the other | `mv filetomove1.txt filetomove2.txt destinationdirectory` | [Link](http://www.rapidtables.com/code/linux/mv.htm) |


## Subheader
