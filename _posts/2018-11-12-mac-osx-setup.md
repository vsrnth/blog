---
layout: post
title: Things I install when I get a brand new Mac
tags: [OS X, Setup]
---

### This is the stuff I install to make my life easier.

***


#### Amphetamine
- To prevent the machine from dozing off
- It can be configured in a multitude of ways so check out the preferences to tweak it to your liking.

#### iTerm2
- OS X's terminal is fine, but I find it lacking.
- So that's where iTerm2 comes into the picture.
Couple of tricks to make iTerm2 even better.To jump between words and start/end of lines in iTerm2 follow these steps:

iTerm2 -> Preferences (⌘ + ,)
Open the “Keys” tab
Add the following Global Shortcut Keys
Move cursor one word left

Keyboard Combination: ⌥ + ←
Action: Send Hex Code
Code: 0x1b 0x62
Move cursor one word right

Keyboard Combination: ⌥ + →
Action: Send Hex Code
Code: 0x1b 0x66
Move cursor to beginning of line

Keyboard Combination: ⌘ + ←
Action: Send Hex Code
Code: 0x01
Move cursor to end of line

Keyboard Combination: ⌘ + →
Action: Send Hex Code
Code: 0x05
Delete word

Keyboard Combination: ⌥ + ←Delete
Action: Send Hex Code
Code: 0x1b 0x08
Delete line

Keyboard Combination: ⌘ + ←Delete
Action: Send Hex Code
Code: 0x15
Undo

Keyboard Combination: ⌘ + z
Action: Send Hex Code
Code: 0x1f
Don't forget to remove the previous bindings:

Open the “Profiles” tab
Click the sub-tab ”Keys”
Remove the mappings for key combinations ⌥ + ← and ⌥ + →

#### Scroll Reverser
 - https://pilotmoon.com/scrollreverser/
 - It does exactly what the name suggests.

#### Keyboard Shortcut hacks
- I was looking for a way to lock the screen of their Mac with a simple key shortcut (CMD+L, like on Windows)
- In High Sierra, this will be native with CMD+CTRL+Q.
- But this doesn't mean you cannot change the shortcut. macOS has a built-in way to change shortcuts:

Open System Preferences
Open Keyboard Preference Pane
Go to Shortcuts tab
Select "App Shortcuts"
Click "+"
Select "All Applications", "Lock Screen" and type your shortcut.
Quit System Preferences



{% include image name="lock-screen-shortcut.png" caption="Sharing my blog on LinkedIn" %}


#### Autojump
- Absolutely adore this little nifty utiility.
- https://github.com/wting/autojump

#### icdiff
- Gives a whole new meaning to the command `git diff`
- https://github.com/jeffkaufman/icdiff

#### Hocus Focus
- This app hides any inactive windows.
- http://hocusfoc.us/

---
This post is a work in progress, I'll keep adding stuff as and when I see something shiny.
