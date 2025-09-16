# GDB Helper

This VS Code extension is random helper commands to enhance gdb debugging experience.

## How to Use

1. Place your cursor on the line you want to copy.
2. Press `Alt+L` (Windows/Linux) or run the command `Copy Relative Path and Line Numbers for Breakpoint Location` from the Command Palette (`F1` or `Ctrl+Shift+P`).
3. The following format will be copied to your clipboard:

	```
	- "b relative/path/to/file:lineNumber"
	```

	Example:
	```
	- "b src/main.cpp:42"
	```

