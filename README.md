# Sun Type 7 Keyboard HWDB file.
I produced this HWDB file to remap keys on a more standard way.

You must move the keycaps to match the appied layout:

 - Move `[ESC]` on the left of `[F1]`, instead previous `[ ]` position
 - Move `[\]` onn the left of `[1]`, instead previous `[ESC]` position
 - Move `[Caps Lock]` on the left of `[A]`, instead previous `[Control]` position
 - Move `[Control]` on the left of `[Alt]`, instead previous `[Caps Lock]` position
 - Move `` [`] `` on the right of `[=]`, instead previous `[\]` position
 - Move `[ ]` on the right of `` [`] ``, instead previous `` [`] `` position

Caveat: The `[Props]` and the `[ ]` keys emit the same scancode (70076). Applying the new layout, `[Props]` will be equivalent to `[Esc]` key. I'm sorry for this inconvenience.

Useful references:

 - https://wiki.archlinux.org/index.php/Map_scancodes_to_keycodes
 - https://yulistic.gitlab.io/2017/12/linux-keymapping-with-udev-hwdb/
