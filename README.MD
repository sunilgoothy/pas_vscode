# PASolutions tools for VSCode

## Syntax Highlight for Director Script
1. Copy __pascfg__ folder to __C:\Users\\{user}\\.vscode\extensions\pascfg\syntaxes__ folder to enable syntax highlighting for .cfg files.
2. Restart VSCode
3. Open a cfg file.
### VSCode should detect file extension and apply highlighting automatically. If it does not then follow below steps.
4. Press `Ctrl + Shift + P` keys and search for "**Change Language** Mode" and click on it.
5. In the dropdown click on "**Configure File Association for '.cfg' files**"
6. In the list of languages displayed select "**PASCFG**" 
7. This will apply the syntax highlighting for PAS cfg files.
***
- Colors of the keywords depends on the theme selected in VSCode. This syntax has been developed and tested on Dark themes. Hence, they will be the preference.
- To apply/force custom colors for keywords modify settings.json file of VSCode.
- See example code for settings.json in  __vscode-custom-token-color-settings.json__ file.

## References
- https://macromates.com/manual/en/language_grammars#naming_conventions
- https://github.com/microsoft/vscode/blob/main/extensions/python/syntaxes/MagicPython.tmLanguage.json
- https://www.youtube.com/watch?v=5msZv-nKebI