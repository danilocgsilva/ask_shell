# ask_shell
Utility to facilitate some commons ways to do questions and validate anwer trough shell.

Available functions:
askshell_ask: just ask something. The answer is not required.

askshell_notempty: ask something, but empty answer is not allowed. Uses the askshell_ask function as base.

askshell_file: ask something. Empty answer is not allowed. And the answer is awaited to be valid file path.

askshell_directory: ask something. Empty answer is not allowed. And the answer is awaited to be valid directory path.