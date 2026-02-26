# cat

The cat command in Linux is a foundational utility that reads files sequentially and writes their contents to the standard output. 

The name cat is an abbreviation of concatenate. 

## options
- -l (long format): Provides a detailed list of information for each item, including file permissions, number of links, owner name, group name, size (in bytes), and time of last modification.
- -a (all): Includes hidden files and directories in the output. In Linux, hidden items have names that start with a dot (.).
- -h (human-readable): Used with the -l option (ls -lh), it displays file sizes in human-readable units like KB, MB, or GB, instead of just bytes, making them easier to read.
- -t (time sort): Sorts the files by modification time, with the most recently modified files appearing first.
- -r (reverse): Reverses the sorting order. For example, when used with -t (ls -ltr), it lists files with the oldest first.
- -F (classify): Appends a symbol to the end of each name to indicate the file type (e.g., a slash (/) for a directory, an asterisk (*) for an executable file).

## example
| Command |	Description	Source |
|---|---|
cat filename.txt |	Displays the contents of filename.txt on the terminal.
| cat file1.txt | file2.txt	Displays the contents of both files sequentially.
| cat file1.txt | file2.txt > combined.txt	Combines the contents of file1.txt and file2.txt and writes them into a new file named combined.txt.
| cat -n filename.txt |	Displays the file contents with line numbers added to each line of output.
| cat -b filename.txt |	Numbers non-blank lines in the output. |