Small tool to update your programs that use HandmadeMath to HandmadeMath 2.0, since there have been some breaking changes to the API. It's a C program that takes a list of files and updates their text, along with some scripts to recursively run the program on all code in a directory.

You can compile the tool yourself with any C/C++ compiler:
- Windows (MSVC): cl UpdateTool.c
- Linux (GCC): gcc UpdateTool.c -o UpdateTool

Then run the tool using your terminal like so:
- Windows: UpdateHMM2.0.bat path\to\project
- Unix: UpdateHMM2.0.sh path/to/project
