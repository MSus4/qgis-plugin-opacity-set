# qgis-plugin-findreplace

Right click in the attribute table to open a screen which lets you quickly find and replace text in fields. Similar to CTRL-F/CTRL-G on a column in a spreadsheet. 
Under the hood this is just the regex_replace function in the field calculator. This plugin is a simple screen to make the functionality a bit more easily accessible. Also, there is a preview window to help you perform your replacements in a controlled manner.
Select the field to perform replacements on in the bottom left. 

You can use regular expressions, like [A-Z] (any capital letter) or (Foo|Bar) (Foo or Bar). When using escape codes, use an extra backslash: e.g. \\\s for a whitespace character.

