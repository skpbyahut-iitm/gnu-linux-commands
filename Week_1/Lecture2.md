# Command line environment

## Terminal emulators

- GNOME Terminal - Default terminal for GNOME
- Terminal - Default terminal for macOS
- GNU Screen - Terminal multiplexer
- guake - Drop down terminal for GNOME
- konsole - Default terminal for KDE
- xfce4-terminal - Default terminal for Xfce
- xterm - Standard terminal for X11
- Termux - Terminal emulator for Android

## Command Prompt

```terminal
username@hostname:~$ 
```

` ~ ` : Symbolic representation for home directory. This is working directory. Terminal opens this directory after launch. 

` @ `,  ` : `, and ` $ ` : command prompt decorators.

A command prompt can be empty.

## Simple Commands
### Syntax
` root@localhost:~$ command [[options] [arguments]] `
  - `option` starts with `-` (single letter as option) or `--` (words as option)

| ` command ` | `[[options] [arguments]] ` | Description |
| ----------- | ----------- | ---------- |
| ` pwd `     |             | Prints path of current/working directory. |
| ` ls `      |             | Lists the files and directories. |
|             | ` -a `      | Include hidden files while listing files. `.` is a prefix for hidden files. |
|             | ` -l `      | Lists the files and directories in long listing format. |
| ` man `     | ` command ` | See the mannual page for command ` command ` | 
| ` uname `   |             | Print the operating system name. |
|             | ` -a `      | Print the system information in a sentence. |
| ` ps `      |             | The users currently running processes. | 
| ` clear `   |             | Clears the screen.  Not possible to navigate the screen by scrolling. |
| ` ctrl + L (l) ` |        | Clears the screen. Possible to navigate screen using scrolling. 
| ` exit `    |             |  Exit shell/shell script |
|             |   number    | Exit with exit status denoted by number. |
| ` ctrl + d (D) ` |        | Exit the shell/shell script/interactive command |
