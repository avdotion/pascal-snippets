# Object Pascal Snippets Package for Sublime Text 3

## Features
* Syntax support (package knows 26 data types and 62 functions)
* Intelligent Snippets
* Compilation in Windows, macOS and Linux-based OS (via [Free Pascal Compiler](https://www.freepascal.org))
* Cyrillic support in Windows

## Easy installation

You can install this awesome package through the Package Control.

Press `⌘/Ctrl + ⇧ + P` to open the command palette.
Type Package Control: Install Package and press enter. Then search for `Object Pascal`.

## Cyrillic Support
*Make sure that your OS is Windows.*
To enable to code with cyrillic support follow this steps:
1. Open one `.pas` or `.pascal` file and go to the `Preferences ⇨ Settings - Syntax Specific`.
2. If the windows title does not ends with "Object Pascal.sublime-settings", go to the step 1.
3. Copy&Paste this lines:
```JSON
{
	"default_encoding": "Cyrillic (Windows 866)",
	"fallback_encoding": "Cyrillic (Windows 866)",
}
```
4. Save this setting-file.

Try to compile this file:
```
begin
write('Привет, мир!')
end.
```
