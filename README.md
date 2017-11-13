# From File  Browser to Terminal

This guide shows you all the ways one can use the terminal in place of the file browser. The intention here is not to completely eliminate use of the file browser entirely, but more as an aid in improving shell skills. It's not implied that all shell commands/methods are easier or more convenient either. This is merely a reference for the sake of practice.

This list is by no means exhaustive. There may be manifold other ways to achieve the same tasks in the terminal but I've listed just one for the sake of brevity and ease of use. I make every effort to list the "standard" way to achieve that task - because to have standards in Linux is [important](https://lwn.net/Articles/658809/).

If you have stumbled across this guide, I hope you find it useful yourself. Possible additions or corrections would certainly be appreciated and of course feel free to fork, clone, or download.

**General Tips:** 
* Make sure you're using [tab completion](https://en.wikipedia.org/wiki/Command-line_completion) whenever you can to speed things up
* Another important tip

**Important Note:** As with all things Linux, each of these commands leads down their own [rabbit hole](https://xkcd.com/456/) of information and history. This means that in practice some may have more onerous consequences than others if used incorrectly. It's also tempting to want to [copy and paste](http://i.imgur.com/SZPjHwz.jpg) some commands wholesale. Therefore, I've added a little asterisk to each one I feel could use some more research before being used [in the style of William Nilly](https://www.merriam-webster.com/dictionary/willy-nilly).

TL;DR

***\**** - Asterisk means: watch out this command can be tricky and/or possibly destructive. See More Info on correct and prudent usage.


| Task | In File Browser | In Terminal | More Info |
| ------- | -------- | ------- | ------- |
| View file type | File browser may have graphical indications of file type, or right-click and choose "Properties" | `file filename.txt` | Link |
| Move file(s) to another directory* | Open two windows/tabs of file browser, select file(s), click and drag from one location to the other | `mv filetomove1.txt filetomove2.txt destinationdirectory` | [Link](http://www.rapidtables.com/code/linux/mv.htm) |
| Create a tar archive(like a zipfile) | Right-click on file, click "Compress" | `tar -cf compressedfile.tar filetocompress.txt` | Link |

## This is what a subheader looks like in case I decide to use subheaders one day
