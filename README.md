# ZMK for Unix60
Unix60 is a HHKB clone developed by mkdl. You can find its repo [here](https://github.com/mkdl/Unix60).
## Current state
- compiles without any issues :)
- every key works :))
- keymap works as it should and the keymap file is somewhat readable now
- bluetooth works as well
- short left shift does not work with keys on the same matrix row (j, k, l, ;, ', and enter) and I have no idea why
## Layout
Since I could not get the short left shift to work with other keys, I decided to use the classic HHKB layout, without much modifications. Everything you need 
to know is in the .overlay file.
~~I'm using following layout that I mapped in the .overlay file.~~ <br>
![My Layout](layout.png)<br>
If you wish to use different layout, you'll have to edit both overaly and keymap. The matrix numbers of alternative keys are probably as follows, but I have not tested that. <br> 
![Alternative layout](alt.png)

## Keymap
My keymap is aimed to be as close to HHKB as possible.  ~~I added one extra key to the right of LSHIFT. Reason being my default language have terrible support for symbols used in programming, so I'm hoping to experiment with this and add a layer for characters such as <> and [] etc.~~
That being said, I placed my alt keys right next to the spacebar, you may want to chagne that if you.
