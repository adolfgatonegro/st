# Gatonegro's st

Custom build of [**st**](https://st.suckless.org/) with various patches applied:

+ **alpha** patch for transparency.
+ **alpha_focus_highlight** to change transparency based on window focus.
+ **anysize** to allow resizing to any pixel size.
+ **blinking_cursor** is self-explanatory.
+ **boxdraw** for drawing lines and blocks properly and without gaps.
+ **externalpipe** to pass information to and from `st` via pipes.
+ **font2** allows having a fallback font besides the default.
+ **ligatures** for drawing proper ligatures.
+ **newterm** allows opening a new terminal in the cwd with `mod + shift + return`.
+ **scrollback** with mouse support.
+ **undercurl** for special underlines.
+ **wide_glyphs** allows `st` to draw glyphs properly instead of cutting them off.
+ **xresources** to configure colours, transparency, and font settings via Xresources.

## Extra stuff

`st` has bindings for copying or following URLs, as well as copying the output
of a command, using `dmenu` and [Luke Smith's](https://github.com/LukeSmithXYZ/st)
custom scripts.
