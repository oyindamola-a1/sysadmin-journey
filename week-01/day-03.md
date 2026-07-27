**VIEWING FILES**

There are a few linux commands available to view the content fo files;
- The [cat] command, which stands for "concatenate" is often used to quickly view the content of small files.
- It displays the entire content of the files, so it's highly recommended for smaller files where the output is limited and does not require scrolling.

- Pager commands include "more" and "less" commands. Another way to view the content of files is by using "head" and "tail". They are used a selected number of files from the bottom or top of a file. Some files are frequently updated with new entries such as system log. The [-n] option with the "head" and "tail" command can be used to specify the amount of lines to display.

- **COPYING FILES**

- Creating copies of files can be useful for many reasons;
- A copy of an existing document can be used as a new template for a new document.
- If a copy of a file is created before changes are made, then it is possible for it to revert back to original.
- A copy of a file can be used to transfer a file to removeable media devices.

The "cp" command is used to copy files, similar to the "mv" command. It requires at least two arguments; A source and a destination. 

The "dd" command is a utility for copying files or entire partition at the bit level. The "dd" command uses special arguments to specify how it works. The "dd" command has several features like ;
- It can be used to clone or delete an entire disk or partitions.
- It can be used to copy raw data to removeable devices, such as USB drives and CD Roms.
- It can backup and restore the MBR [Master Boot Record].

**MOVING FILES**

The "mv" command is used to move a file from one location in the file system to another. It is able to move multiple files, as long as the final argument provided to the command is the destination.

**REMOVING FILES**

The "rm" command is used to delete files and directories, deleted files and directories dont go into a "trash can", when a file is deleted, it's almost permanently gone.

**REGULAR EXPRESSIONS**

They have two common forms which are the basic and the extended, most command that uses regular expressions can interprete basic regular expressions, Extended regular expressions are not available for all command and a command option is typically required for them to work correctly. 
