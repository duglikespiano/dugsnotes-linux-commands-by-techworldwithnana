# cp

The cp command in Linux is used to copy files and directories from one location to another. It is a fundamental tool for file management in the command line interface. 

## options
| Option |	Description	|
| --------- | --------- |
|-i |	Interactive mode: prompts for confirmation before overwriting an existing file. This is often the default behavior in many distributions.	|
|-f |	Force: forces the copy by removing the destination file if necessary, without prompting for confirmation (overrides -i if both are specified).	|
|-r or -R |	Recursive: copies directories and their entire contents.	|
| -p	| Preserve attributes: preserves the original file's attributes, including ownership, permissions, and timestamps.	|
| -a	| Archive: a combination of options (equivalent to -rp and more) that preserves as much of the original file's attributes and directory structure as possible.	|
|  -v	| Verbose: explains what is being done, showing which files are being copied.	|
|  -u |	Update: copies only when the source file is newer than the destination file or when the destination file is missing. |

## usage
`cp [OPTIONS] source_file destination`

## example
`cp file1.txt file2.txt`  
This command creates a copy of file1.txt named file2.txt in the current directory.

`cp file1.txt /home/user/documents/`  
This command copies file1.txt into the documents directory, retaining the original name.

`cp -r dir1/ dir2/`  
The -r (recursive) option is required to copy a directory and its contents, including subdirectories. 
