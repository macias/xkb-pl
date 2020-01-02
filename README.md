# xkb-pl

Extended Polish layout for xkb — with some twists ;-).

# Rationale

I dislike idea of having one <kbd>Alt</kbd> key used as functional modifier and the other one as typographic one, while <kbd>Caps</kbd> is pretty much unused. With regular
layout, Polish or not Polish, not only  a lot of special characters are not available directly but also regular characters are put in odd places, which is especially true
for programmer (two keystrokes to get “+”).

# Execution

Unfortunately I don’t know how to make this layout as add-on, so this is a replacement. Copy all original files (safety) and then copy over provided ones.
The layout itself is proven to help type more comfortable since 2008, these particular files are used with openSUSE Tumbleweed 2019-12-27 snapshot.

# Keyboard mapping

<kbd>Alt</kbd> keys are symmetric and are mapped as “Meta” — they are repurposed as typographic modifiers. <kbd>Caps</kbd> is new “Alt” — functional modifier.
For getting “Caps” effect, which is needed very rarely, I found pressing both <kbd>Shift</kbd> keys works well and it is easy to remember.

# Layout extension

Parentheses and brackets are swapped, same story with back-tick and underscore. Also plus sign and backslash are more intuitive, as well colon and semicolon.
All those changes reflect how often one uses those characters when programming.

There are added German characters “ß” (<kbd>Alt</kbd> + <kbd>~</kbd>) and “äöü” — brackets segment. There rest are special symbols put in numeric row and on the
right side (over regular typographic symbols) — symbols like “€”, “§” or “≥” are available right away. The character “¶”
— <kbd>Alt</kbd> + <kbd>p</kbd> — makes an exception for easier remembering.


