# GermanDev

GermanDev is a customized **German QUERTZ keyboard layout** designed for software development on Macs. Pressing one of the option keys while typing `d`, `f`, `j` or `k` will give you square braces (eckige Klammern) and curly braces (Mengenklammern).

`⌥` + `d` = `[`

`⌥` + `f` = `[`

`⌥` + `j` = `{`

`⌥` + `k` = `}`

![Alt text](/howto.jpg?raw=true "GermanDev difference")

## Installation
1. Put a copy of _GermanDev.bundle_ into your _/Library/Keyboard Layouts_ folder.
2. open _System Preferences_
3. click _Language & Region_ › _Keyboard Preferences..._ › _Input Sources..._ and add _GermanDev_
4. change the little flag in the menu bar

## Block Indentation
Several text editors use square braces as hot keys for block indentation. This leads to rather bizarre triple-key shortcuts on German keyboards.

I prefer using `⌥` + `⇥`  and `⌥` + `⇤` (option + shift + tab) instead. TextMate supports these shortcuts out of the box (see [manual section 4.6.1](http://manual.macromates.com/en/working_with_text)). Other text editors might need a little help. If you want to use these shortcuts in Xcode, copy the file _Default.idekeybindings_ to _~/Library/Developer/Xcode/UserData/Keybindings_.
