"VSCode netcoredbg debugger" - The first script I made is for VSCodium (or VSCode)
	My motivation was that if you use VSCodium you can't use the built-in debugger to debug .Net
	There's a workaround with the Samsung netcoredbg but you have to create/edit "launh.json" every time if you want to use it.
	Not anymore. This script generates the .vscode folder if it doesn't exist and generates "launch.json" and "tasks.json"
	Currently it's only available on linux bash script but I'm planning on porting to Windows.

	Linux usage:
	1. copy csharp_debug_linux into a folder in your PATH
	2. optionally you can rename it to csharp_debug (or anything else) for esier usage
	3. when in VSCode run chsarp_debug (ir what you renamed it) from terminal and answer to the questions
