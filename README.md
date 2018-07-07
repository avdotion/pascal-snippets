# Object Pascal Snippets Package for Sublime Text 3

**[Инструкция на русском](http://telegra.ph/Ustanovka-Sublime-Text-dlya-polnocennoj-razrabotki-na-Pascal-06-25) и её [зеркало](http://tgraph.io/Ustanovka-Sublime-Text-dlya-polnocennoj-razrabotki-na-Pascal-06-25)**

## Features
* Syntax support (package knows 27 data types and 62 functions)
* Intelligent Snippets
* Compilation in Windows, macOS and Linux-based OS (via [Free Pascal Compiler](https://www.freepascal.org))
* Cyrillic support in Windows

## Easy installation

You can install this awesome package through the Package Control.

Press `⌘/Ctrl + ⇧ + P` to open the command palette.
Type `Package Control: Install Package` and press enter. Then search for `Object Pascal`.

## Cyrillic Support
To enable to code with cyrillic support follow this steps:
1. Open one `.pas` or `.pascal` file and go to the `Preferences ⇨ Settings - Syntax Specific`.
2. If the window title does not end with "Object Pascal.sublime-settings", go to the step 1.
3. Copy&Paste this lines:
```JSON
{
	"default_encoding": "Cyrillic (Windows 1251)",
	"fallback_encoding": "Cyrillic (Windows 1251)",
}
```
4. Save this setting-file.

Try to compile this file:
```
begin
	write('Привет, мир!')
end.
```
