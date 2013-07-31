Git-UNIX-GUI
============

UNIX GUI for git
(GottaGitThat - ggt)

Ideally, ggt will serve as a reasonably functional GUI that allows Unix users to use Git/GitHub without diving into the
terminal. However, terminal is going to be far more powerful. Duh.


Ideas
============
Chunky, stdako ... etc. post ideas here.

I personally think that the main way we should go about this is by using wxPython as our GUI module. Inside the main
window, have buttons that do different things!

- commit button (the commit message should be a prompt)
- add button / add highlighted (for multiple files)
- remove button / remove highlighted
- status button (pop-up window?)
- log button (pop-up?) / log --oneline button? (pop-up?)
- init button! important...
- ssh(RSA) key generator button (make it as convenient as possible)
- push button
- pull button
- remote add (prompt for remote-repo-name
- branch button (prompt for branch-name)
- clone button (somehow make this easy? just prompt for link)
- merge button (god help us)
- fork button (probably just triggers the clone script and then the branch script, not in that order)
- diff button (again god help us)


Interface
===========
What should it look like?

- Buttons in a taskbar? (top/bottom/side?)
- something that shows you what you're working on? (Taking a hint from the OSX GUI, probably all the files you have in your repository right now, and the one you're working on right now is highlighted)
