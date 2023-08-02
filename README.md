# py-modernoth-v2

An easy theming method for PyQt5

## How to use?
In `source/gui.py`, copy the `_convert_stylesheet` function, and paste it into your code.

Then, make 2 new variables **before** the `_convert_stylesheet` function: `theme_folder` (set the theme folder), `theme_list` (the json file, that has the list with themes)
  - for `theme_list`: It needs to be a json file. You can see in `source/resources/themes/theme_list.json` how it is structured.

You ___can___ remove the `print_Theme_Debug` and `file_Theme_Debug` variable.

(Recommended: Just download this repo and build your application with gui.py (renameable btw))
