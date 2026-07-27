**SUMMARY FOR WEEK 01**

**DAY 01**

- I learnt that linux is a software operating system that allow other programs and web brower be installed and run on a computer.everyone can use linux too and it's not difficult to learn it and it helps giving a better computing skill.
- linux desktops uses a GUI [GRAPHICAL USER-INTERFACE] but it has a more efficient tool for carrying out the same action is the CLI [command line interface].
- Linux skills are basic skills needed for many IT professional tracks and it is also an open source.
- CLI is a powerful tool that is often the primary method used to administer small lo-power devices, extremely capable cloud computing servers and everything in between.
- A command is a software program that when executed on the CLI performs an action on the computer. The ls command displays a listing of information about files.
- An argument can be used to specify something for the command to act upon.
- Options can be used to alter the behaviour of a command.
- They are two types of paths ; ABSOLUTE PATHS and RELATIVE PATHS
- Absolute paths allows you to specify the exact location of a directory.
- Relative paths gives direction to a file relative to the current location in the file system.

**DAY 02**

- The ls command [listing files] is used to listing the content of a directory.
- The ls command is sorted slphabetically by file name but with the option [-t], it will sort the files by time stamp.
- Logging in as the root user provides administrative access, allowing for the execution of some of the privileged commands.
- The su command allows you to temporarily act as a different user.
- The sudo command allows a user to execute a command as another user without creating a new shell.
- Permissions determines the way different users can interact with a file or directory.
- The chmod command is used to change the permission of a file or directory.
- The chown command is used to change ownership of files and directories.
- To change directory to the document directory is cd ~/Documents.

**DAY 03**

- There are a few linux commands available to view the content of files, the [cat] command is often used to quickly view the content of small files.
- It's highly recommended for smaller files where the output is limited and not require scrolling.
- "head" and "tail" is another way of viewing content of files, they are used to view a selected number of lines from the bottom or top of a file.
- The [-n] option with the "head" and "tail" command can be used to specify the amount of lines to display.
- A copy of an existing document can be used as a new template for a new document.
- If a copy of file is created before changes are made, then it is possible to revert back to original.
- A copy of file can be used to transfer a file to removeable media devices.
- The "cp" command is used to copy files, similar to the "mv" command, ir requires two arguments, a source and a destination.
- The "dd" command for copying files or entire partitions at the bit level.
- It can be used to clone or delete entire disks or partitions.
- It can be use to copy raw data to removeable devices, such as USB drives and CDRoms.
- It can backup and restore the MBR [master boot record].
- The "mv" comand is used to vove a file from one location in the filesystem to another.
- The "rm" command is used to delete files and directories, deleted files and directories are almost permanently gone.
- Regular expressions have two common forms; basic and extended, most command that use regular expressions can interprete basic regular expressions.
- Extended regular expressions are not available for all commands and a command option is typically required for them to work correctly.

 **DAY 04**

- Regular patterns are patterns that only certain commands are able to interprete.
- They are one of the ways regular expressions can be used to narrow down search results.
- **MATCH A SINGLE CHARACTER WITH [ . ]**
- One of the most useful expression is the period [.] character, it will match any character except for the new line character.
- **MATCH A SINGLE CHARACTER WITH [ ]**
- The square brackets [ ] match a single character from the list of possible character contained within the brackets.
- When other expression characters are placed inside of square brackets, they are treated as literal characters.
- **MATCH A REPEATED CHARACTER OR PATTERN WITH [*]**

**DAY 05**
- If a file is not given, the "grep" will read from standard input, which normally comes from the keyboard with input provided by the user who runs the command.
- The "shutdwon" command arranges for the system to be brought down in a safe way, the command requires a time argument specifying when the shut down should begin.
- The "ifconfig" command stands for interface configuration and is used to display network configuration interfaces and it can be used to temporarily modify work settings.
- The "lo" device is referred to the loopback device and it's a special device used by the system when sending network based data to itself.
- The "ping" command is used to verify connectivity between two computers.
- Running a command results in something called PROCESS and they are executed with the privileges of the user who executes the command.
- Package management is a systen by which software can be installed, updated, quieried or remove from a file system.
- The two most popular are those from DEBIAN and RED HAT.
- Package files are commonly installed by downloading them directly from repositories located on internet servers.
- The "apt-get install" command can also update a package, if that package is installed and a newer version is installed.
- The "apt-get" command is able to either remove or purge a package.
- The difference between the two is that purging deletes all package files, while removing deletes all the configuration file for the package.

**DAY 06**

- The "passwd" command is used to update a user's password.
- Users can only change their passwords, whereas the root user can update the password for any user.
- Adding content to files in linux can be done in a variety of ways.
- Linux add quickly add content to a file using a command line feature called INPUT/OUTPRT [I/O] redirection.
- The I/O redirection allows for information in the command line to be sent to files, devices and other commands.
- The premier text sditor for linux and UNIX is a program called {vi}, there are several advantages to the [vi] editor.
- The [vi] editor is available in every linux distribution in the world and the {vi} editor can be executed both in a CLI and a GUI.
- The three modes used in [vi] COMMAND MODE, INSERT MODE and EX-MODE
- Programs starts in the command mode, it's used to type commands, such as those used to move around a document, manipulate text and access the other two modes [COMMAND MODE MOVEMENT]
- The standard convention for editing content with word processors is to use, copy, paste and cut. [COMMAND MODE ACTIONS]
- It's used to add text to the document. [INSERT MODE]
- The [vi] editor was called the [ex] editor, the name [vi] was the abbreviation of the visual command in the [ex] editor which switched the editor to 'visual' mode. [EX-MODE]





