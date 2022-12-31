

<div align="center">
<h1>TUIFI Manager</h1>
<p>
    <a href="https://github.com/GiorgosXou/TUIFIManager/pulse">
      <img src="https://img.shields.io/github/last-commit/GiorgosXou/TUIFIManager?color=%4dc71f&label=Last%20Commit&logo=github&style=flat-square"/>
    </a>
    <a href="https://github.com/GiorgosXou/TUIFIManager/blob/master/LICENSE.md">
      <img src="https://img.shields.io/github/license/GiorgosXou/TUIFIManager?label=License&logo=GNU&style=flat-square"/>
	</a>
</p>
</div>

A cross-platform terminal-based termux-oriented file manager *(and component)*, meant to be used with a [Uni-Curses](https://github.com/unicurses/unicurses) project or as is. This project is mainly an attempt to get more attention to the [Uni-Curses](https://github.com/unicurses/unicurses) project.


## Installation
```terminal
sudo pip3 install tuifimanager --upgrade
```
```terminal
pip3 install TUIFIManager --upgrade
```
or just ^^^ if it works for you. *(eg. on termux?)*


## Usage
Run `tuifi` in your terminal to use it as is or import it in one of your [Uni-Curses](https://github.com/unicurses/unicurses) project as a component like:
```python
from TUIFIManager import *
```
for more details look into the `__main__.py`

[![Preview]][#]

<sub>FONT: Cartograph CF</sub>

## Features & Shortcuts  
### *Current:*
* Supports most of the common mouse events so far
* It is somewhat fully customizable?
* Can be used as a component
* Uses only ~30MB of RAM
* It is pretty snappy <!-- Kinda lol -->
* Supports [Termux](https://github.com/termux) 
* Cross Platform 
* and more

### *Desired:*
* Undo\Redo
* tool-tips
* Scroll bar
* Multiple tabs
* Better performance
* Effect on cutted Files
* [Drop files into GUI apps](https://github.com/GiorgosXou/TUIFIManager/issues/21)

<br>
<br>

## Keybindings

<br>

### Common

| Shortcuts | Vim Mode | Action
|:---------:|:--------:|:-------:
| <kbd>  Shift  </kbd>  +  <kbd>  Tab  </kbd>  || Move items to <br> previous directory
| <kbd>  Backspace  </kbd> | <kbd>  J  </kbd> | Previous Directory
| <kbd>  Alt  </kbd>  +  <kbd>  🠗  </kbd> || Context Menu
| <kbd>  Home  </kbd> | <kbd>  H  </kbd> | Home Directory
| <kbd>  F5  </kbd> || Refresh Directory
| <kbd>  Ctrl  </kbd>  +  <kbd>  V  </kbd> | <kbd>  p  </kbd> | Paste
| <kbd>  Delete  </kbd> | <kbd>  Ctrl  </kbd>  +  <kbd>  D  </kbd> | Delete
| <kbd>  Ctrl  </kbd>  +  <kbd>  F  </kbd> | <kbd>  i  </kbd> | File Search
| <kbd>  Ctrl  </kbd>  +  <kbd>  O  </kbd> | <kbd>  O  </kbd> | Open Directory
| <kbd>  Ctrl  </kbd>  +  <kbd>  C  </kbd> | <kbd>  y  </kbd> | Copy Items
| <kbd>  Ctrl  </kbd>  +  <kbd>  K  </kbd> || Copy Item
| <kbd>  Ctrl  </kbd>  +  <kbd>  X  </kbd> | <kbd>  c  </kbd> | Cut
| <kbd>  Ctrl  </kbd>  +  <kbd>  R  </kbd> | <kbd>  r  </kbd> | Rename 
| <kbd>  Ctrl  </kbd>  +  <kbd>  N  </kbd> | <kbd>  W  </kbd> | New Folder
| <kbd>  Ctrl  </kbd>  +  <kbd>  W  </kbd> | <kbd>  w  </kbd> | New File
| <kbd>  🠔  </kbd>  <kbd>  🠕  </kbd>  <kbd>  🠗  </kbd>  <kbd>  🠖  </kbd> | <kbd>  l  </kbd>  <kbd>  k  </kbd>  <kbd>  j  </kbd>  <kbd>  h  </kbd> | Navigate
| <kbd>  Enter  </kbd> | <kbd>  K  </kbd>  <kbd>  o  </kbd> | Open
| <kbd>  Escape  </kbd> || Exit

<br>

### TERMUX Only

| Shortcut | Action
|:---------|:--------
| <kbd>  Ctrl  </kbd>  +  <kbd>  🠗  </kbd> | Goes in & out of select-mode while also automatically copies the selected file(s)
| <kbd>  Ctrl  </kbd>  +  <kbd>  🠔  </kbd> | Goes out of select-mode while also cuts the seleccted file(s)
| <kbd>  Ctrl  </kbd>  +  <kbd>  End  </kbd> | Goes out of select-mode while also deleting the selected file(s)
| <kbd>  Ctrl  </kbd>  +  <kbd>  🠕  </kbd> | Same as `CTRL + V`, Pastes the Copied or Cuted files
| <kbd>  End  </kbd> | Deletes selected files

<br>
<br>

# Donation

I do really need money to survive, I have no job, living in a basement, making things for free, because I love to.

- ***Monero Address:*** 

`897ehhSQJQpGF7tYDhQM51jiX7nnHmzuYAW4q8JGwJxu8JKXvaK6AivCzatuJxnifjZ2qy98ks2g2PhmTaYCMMta2Ga2LJx`

<div align="center">

[![Logo]][#]

</div>



# Special thanks to
- [Bryan Lunduke for this article](https://lunduke.substack.com/p/tuifi-manager-a-file-manager-in-the)
- [Brodie Robertson for this video](https://youtu.be/9laxdMKTZLA)
- [r/commandline community for their comments](https://www.reddit.com/r/commandline/comments/zt30v9)

# Help
Any Idea with this issue https://github.com/unicurses/unicurses/issues/21 ?


[Preview]: Resources/Preview.gif
[Logo]: Resources/Logo.png

[#]: #

